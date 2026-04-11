# Influence Fingerprint Comparison

*Running the same analysis on Ray's stated influences — The Fall, Built to Spill, Captain Beefheart — and comparing their fingerprints to his. Does the data match the feelings?*

---

## The Comparison

```chart
type: radar
labels: [Power Chord %, Density (n/s x10), Tempo (BPM/20), Bass %, Ascending %]
series:
  - title: Le Rug
    data: [53, 70, 98, 56, 45]
  - title: The Fall
    data: [73, 44, 90, 66, 42]
  - title: Built to Spill
    data: [49, 88, 102, 57, 46]
  - title: Captain Beefheart
    data: [76, 45, 92, 54, 44]
width: 75%
labelColors: true
fill: true
```

| Artist | Tracks | n/s | BPM | Power % | Sus2 % | Sus4 % | Major % | Minor % | Bass % |
|---|---|---|---|---|---|---|---|---|---|
| **Le Rug** | 439 | **7.0** | **196** | **53.0%** | **5.8%** | **5.1%** | **13.8%** | **6.7%** | **56.0%** |
| Built to Spill | 44 | 8.8 | 205 | 49.3% | 4.6% | 3.4% | 25.5% | 8.2% | 56.6% |
| Captain Beefheart | 57 | 4.5 | 184 | 75.9% | 5.8% | 5.5% | 6.0% | 4.1% | 53.5% |
| The Fall | 66 | 4.4 | 179 | 73.1% | 5.2% | 7.9% | 7.1% | 4.6% | 65.5% |

*Influence tracks analyzed across full albums: The Fall (6 albums, 66 tracks), Beefheart (3 albums, 57 tracks), Built to Spill (5 albums + Doug Martsch solo, 44 tracks).*

---

## What the Data Shows

### Built to Spill Is the Closest Structural Match

With full album samples, Built to Spill is clearly the closest fingerprint to Le Rug (similarity: 0.0382). The numbers are strikingly close:

- **Power chords:** 49.3% vs 53.0% — nearly identical chord foundation
- **Bass register:** 56.6% vs 56.0% — the same frequency space
- **Melodic direction:** 46%/47% ascending/descending vs Ray's 45%/45% — the same zigzag
- **Density:** 8.8 vs 7.0 n/s — both dense, both fast

```chart
type: bar
labels: [Power Chord %, Major Triad %, Sus2 %, Minor Triad %, Density (n/s)]
series:
  - title: The Fall
    data: [73.1, 7.1, 5.2, 4.6, 4.4]
  - title: Le Rug
    data: [53.0, 13.8, 5.8, 6.7, 7.0]
  - title: Built to Spill
    data: [49.3, 25.5, 4.6, 8.2, 8.8]
width: 80%
labelColors: true
beginAtZero: true
```

The one clear difference: Built to Spill uses twice the major triads (25.5% vs 13.8%). Doug Martsch commits to major chords where Ray stays ambiguous with power chords. Ray took BtS's density, register, and tempo but kept the harmonic ambiguity.

### The Fall and Beefheart Are Simpler Than They Sound

With 66 Fall tracks and 57 Beefheart tracks analyzed, both come in at ~74-76% power chords. That's 20+ points higher than Ray. The perception of The Fall as complex and chaotic is driven by Mark E. Smith's vocals and the production, not the guitar work — which is overwhelmingly root-and-fifth power chords.

Both are also significantly sparser (4.4-4.5 n/s vs Ray's 7.0) and slower (179-184 BPM vs Ray's 196). Ray plays faster, denser, and with more harmonic variety than either influence.

### The Sus2/Sus4 Story — Revised

With 3 tracks, The Fall showed 0% suspended chords, which led to the conclusion that Beefheart was the sole source of Ray's sus2/sus4 habit. With 66 tracks, The Fall actually has **5.2% sus2 and 7.9% sus4** — more sus4 than Ray (5.1%). All three influences use suspended chords:

| Artist | Sus2 % | Sus4 % | Combined |
|---|---|---|---|
| **Le Rug** | 5.8% | 5.1% | 10.9% |
| The Fall | 5.2% | 7.9% | 13.1% |
| Beefheart | 5.8% | 5.5% | 11.3% |
| Built to Spill | 4.6% | 3.4% | 8.0% |

The sus2/sus4 balance is not unique to Beefheart — it's present in The Fall as well (and in greater total proportion). What Beefheart likely contributed is the *attitude* toward dissonance: the willingness to let suspended chords sit unresolved. But the voicings themselves are common across all three influences.

### The Fall Gave Ray the Register, Not the Speed

The clearest Fall → Le Rug inheritance: **bass-heavy register** (65.5% vs 56.0%). The Fall lives lower on the fretboard than either BtS or Beefheart. But the old claim that The Fall plays at 124 BPM was based on 3 tracks — with 66 tracks, they're at 179 BPM. Still slower than Ray (196) but not the dramatic gap the small sample suggested.

What Ray took from The Fall isn't the chord vocabulary (they're 20 points apart on power chords) — it's the aesthetic of low-register, power-chord-driven guitar as a vehicle for intensity.

### Where Ray Sits

| Trait | Closest To | Evidence |
|---|---|---|
| Chord balance (power %) | **Built to Spill** | 49% vs 53% — nearest of the three |
| Harmonic richness (major triads) | Between BtS and Fall | BtS 25.5%, Ray 13.8%, Fall 7.1% |
| Sus2/Sus4 balance | Beefheart | 5.8%/5.5% vs Ray's 5.8%/5.1% — nearest match |
| Density | **Built to Spill** | 8.8 vs 7.0 n/s — both dense |
| Tempo | **Built to Spill** | 205 vs 196 — both fast |
| Bass register | **The Fall** | 65.5% vs 56.0% — both bass-heavy |
| Melodic direction | **Built to Spill** | 46/47% vs 45/45% — identical zigzag |
| Overall fingerprint | **Built to Spill** | Similarity 0.0382 (closest by a wide margin) |

---

## Albums Analyzed

**The Fall (66 tracks):** Hex Enduction Hour, Perverted by Language, This Nation's Saving Grace, Grotesque (After the Gramme), Slates, Room to Live

**Captain Beefheart (57 tracks):** Trout Mask Replica, Lick My Decals Off Baby, Safe as Milk

**Built to Spill (44 tracks):** Keep It Like a Secret, Perfect From Now On, There's Nothing Wrong with Love, Ultimate Alternative Wavers, You in Reverse, Doug Martsch — Now You Know

---
