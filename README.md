# QoE-Modeling-for-360-Degree-Video-Dataset
This is the dataset collected and used in the article titled "Modeling the User Experience ofWatching 360° Videos with
Head-Mounted Displays", which is submitted to ACM Transactions on Multimedia Computing, Communications, and Applications.
## Videos are from Joint Video Exploration Team (JVET)
(03) Landing, (05) Balboa, (07) PoleVault, (08) BranCastle, (09) Harbor, (10) SkateboardTrick
## Directory Tree
- dataset
  - user01
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
  - MOS_model
  - IS_model
- scripts
### File Content
1. user_profile:
  user_no, gender, age, frequency, education
2. uxx_txx_vxx.log:
  frame_no, head_yaw, head_pitch, gaze_yaw, gaze_pitch
3. rating_log:
  video_no, overall_QoE, image_quality, fragmentation, immersion, cybersickness, attractive
4. MOS Models:
  OQ^M_A: equation
  IQ^M_A: equation
  ...
  CS^M_F: equation
5. IS Models:
  OQ^I_A: equation
  IQ^I_A: equation
  ...
  CS^I_F: equation
