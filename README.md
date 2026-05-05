# Dataset Description

## Overview
This dataset was collected from a smart learning system and is designed for research in Educational Data Mining (EDM), Learning Analytics (LA), and Multimodal Learning Analytics (MLA). The dataset combines students’ online learning behaviors and emotional states extracted from images to support academic performance prediction tasks.

The data include anonymized student information, learning interaction logs, emotional states during study sessions, and learning performance indicators.

---

## Data Fields

| No | Data Field | Description |
|----|-------------|-------------|
| 1 | `studentID` | Anonymized student ID |
| 2 | `classID` | Anonymized class ID |
| 3 | `timeStamp` | Study time |
| 4 | `emotion` | Emotional state during learning (recognized from images, including three states: Neutral, Happy, Sad) |
| 5 | `diemTB_baitap` | Assignment/test score |
| 6 | `soAnhChup` | Number of images captured during the learning process |
| 7 | `soLanHoc` | Total number of study sessions |
| 8 | `baiHoanThanh` | Total number of completed tasks |
| 9 | `tbThoiGian1LanHoc` | Average duration per study session |
| 10 | `tbThoiGianHoanThanhBai` | Average time to complete a task |
| 11 | `tbPhanTramMoiLanHoc` | Average completion percentage per session |
| 12 | `tgianHocTrongTuan` | Total study time per week |
| 13 | `tgianHocGioHanhChinh` | Total study time during working hours |
| 14 | `tgianHocNgoaiHanhChinh` | Total study time outside working hours |
| 15 | `trongTuan` | Total study time on weekdays |
| 16 | `cuoiTuan` | Total study time on weekends |

---

## Dataset Characteristics

- The dataset integrates multimodal learning data, including:
  - Behavioral learning logs
  - Emotion recognition data extracted from images
- Emotional states are categorized into three classes:
  - Neutral
  - Happy
  - Sad
- Student and class identifiers are anonymized to protect privacy.
- The dataset can be used for:
  - Academic performance prediction
  - Learning analytics research
  - Educational data mining
  - Multimodal machine learning
  - Emotion-aware learning systems

---

## Possible Research Tasks

- Student performance prediction
- Emotion-aware learning analytics
- Multimodal data fusion
- Behavioral pattern analysis
- Deep learning for educational data
- Transformer-based prediction models

---

## License

This dataset is intended for academic and research purposes only.

---

## Citation

If you use this dataset in your research, please cite the corresponding publication or repository.

