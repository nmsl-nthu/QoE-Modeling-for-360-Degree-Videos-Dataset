# QoE-Modeling-for-360-Degree-Video-Dataset
This is the dataset collected and used in the article titled "Modeling the User Experience ofWatching 360° Videos with
Head-Mounted Displays", which is submitted to ACM Transactions on Multimedia Computing, Communications, and Applications.
## Videos are from Joint Video Exploration Team (JVET)
(03) Landing, (05) Balboa, (07) PoleVault, (08) BranCastle, (09) Harbor, (10) SkateboardTrick
## Directory Tree
- dataset
  - userXX
    - user_profile
    - orienation_log
      - uxx_t01_vxx.log
      - uxx_t02_vxx.log
      ...
      - uxx_t24_vxx.log
    - rating_log
- models
  - MOS_model
  - IS_model
### File Content
1. user_profile:
  user_no, gender, age, frequency, education
2. uxx_txx_vxx.log:
  frame_no, head_yaw, head_pitch, head_roll, gaze_x, gaze_y, gaze_z
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
