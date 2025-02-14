# Polyrhythmic Challenges

Repository supporting the CMMR 2023 post-symposium proceedings paper "Challenging Beat Tracking: Tackling Polyrhythm, Polymetre, and Polytempo with Human-in-the-Loop Adaptation", to be published by Springer Verlag in the LNCS series.

This repository contains the *Piano Phase* dataset used in our study, including:
- Audio files (`/pianophase/audio`): The main files are `pianophaseM_A` and `pianophaseM_B`, which contain the mixed audio of both streams with ground-truth annotations for streams A and B, respectively, each with a duration of 2 minutes. Additionally, `pianophaseA_A` and `pianophaseB_B` provide solo renditions of streams A and B, with corresponding annotations, and are included (as well as `pianophaseA_B` and `pianophaseB_A`)for testing purposes. 
- Beat annotations (`/pianophase/annotations/beats`): The ground-truth beat annotations;
- Pd patch (`/pd_patch`): used for generating the audio.
 

## Citation
If you use this dataset in your research, please cite the following paper:
```bibtex
@inproceedings{polyrhythmic2023,
    title={Challenging Beat Tracking: Tackling Polyrhythm, Polymetre, and Polytempo with Human-in-the-Loop Adaptation},
    author={António Sá Pinto, Gilberto Bernardes, and Matthew E. P. Davies},
    booktitle={Computer Music Multidisciplinary Research Post-Proceedings (CMMR 2023)},
    year={2025},
    publisher={Springer},
    series={Lecture Notes in Computer Science}
}
```

## Corresponding Author

António Sá Pinto
asapinto [at] fe [dot] up [dot] pt


## Acknowledgments

A previous version of this work, entitled "Bridging the Rhythmic Gap: A User-Centric Approach to Beat Tracking in Challenging Music Signals" was presented at the 16th International Symposium on Computer Music Multidisciplinary Research (CMMR 2023), organized by Keiji Hirata and colleagues, November 13th-17th, Tokyo, Japan.