# Polyrhythmic Challenges

Repository supporting the CMMR 2023 post-symposium proceedings paper "Challenging Beat Tracking: Tackling Polyrhythm, Polymetre, and Polytempo with Human-in-the-Loop Adaptation", to be published by Springer Verlag in the LNCS series.

This repository contains the *Piano Phase* dataset used in our study, including:
- Audio files; 
- Beat annotations;
- *PureData* (Pd) patch used for generating the dataset.
 

## Repository Structure

```
/audio          - Piano Phase audio files with varying tempo conditions
/annotations    - Ground truth beat annotations
/pd_patches     - Pure Data patch for *Piano Phase* generation
```

## Dependencies

* Pure Data [Extended] (v0.53)
* [Piano Phase] externals (details in /pd_patches/README.md)

## Citation

```bibtex
@inproceedings{polyrhythmic2023,
    title={Challenging Beat Tracking: Tackling Polyrhythm, Polymetre, and Polytempo with Human-in-the-Loop Adaptation},
    author={[Author Names]},
    booktitle={Computer Music Multidisciplinary Research (CMMR 2023)},
    year={2023},
    publisher={Springer},
    series={Lecture Notes in Computer Science}
}
```

## Corresponding Author

António Sá Pinto
asapinto@fe.up.pt

## Acknowledgments

A previous version of this work, entitled "Bridging the Rhythmic Gap: A User-Centric Approach to Beat Tracking in Challenging Music Signals" was presented at the 16th International Symposium on Computer Music Multidisciplinary Research (CMMR 2023), organized by Keiji Hirata and colleagues, November 13th-17th, Tokyo, Japan.