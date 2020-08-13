# QoE-Modeling-for-360-Degree-Video-Dataset
This is the dataset collected and used in the article titled "Modeling the User Experience ofWatching 360° Videos with
Head-Mounted Displays", which is submitted to ACM Transactions on Multimedia Computing, Communications, and Applications.
## Videos are from Joint Video Exploration Team (JVET)
(03) Landing, (07) PoleVault, (08) BranCastle, (10) SkateboardTrick, (05) Balboa, (09) Harbor
## Folders
- dataset
  - data_samples: All data samples with QoE scores and factor values
  - user01: log files of user 01
    - user_profile
    - orienation_log
      - u01_v03_b9.log
      - u01_v09_b3.log
      .
      .
      .
      - u01_v03_b1.log
    - rating_log
- models
  - MOS_A_OQ.model
  - MOS_A_IQ.model
  ...
  - IS_A_OQ.model
  ...
- features
  - all_ft_oq: all features -> predicting OQ
  - all_ft_iq: all features -> predicting IQ
  ...
- scripts
### File Content
1. user_profile:
  user_no, gender, age, frequency, education
2. uxx_txx_vxx.log:
  frame_no, head_yaw, head_pitch, gaze_yaw, gaze_pitch
3. rating_log:
  video_no, br, overall_QoE, image_quality, fragmentation, immersion, cybersickness, attractive
