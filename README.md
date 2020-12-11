JSON Template for 0.3.X presets:
```
   "Xinch-CellCount-motorSize-motorKV-Pilot-flyStyle":{
      "preset_note":                   "Additional notes and information about the tune or to help end-users with application. For example for what quads suitable, better, etc.",
      "build_motors":                  "MOTORS name, size etc",
      "build_frame":                   "FRAME name, size etc",
      "build_props":                   "Props size etc",
      "build_battery":                 "Battery (4S,6S etc.)",
      "__comment":                     "!!! PIDs !!!",
      "p_roll":                        45,
      "i_roll":                        70,
      "d_roll":                        20,
      "p_pitch":                       45,
      "i_pitch":                       70,
      "d_pitch":                       20,
      "p_yaw":                         45,
      "i_yaw":                         70,
      "d_yaw":                         20,
      "__comment":                     "!!! Filters IMUF !!!",
      "imuf_roll_q":                   3000,
      "imuf_pitch_q":                  3000,
      "imuf_yaw_q":                    3000,
      "imuf_w":                        32,
      "imuf_pitch_lpf_cutoff_hz":      90,
      "imuf_roll_lpf_cutoff_hz":       90,
      "imuf_yaw_lpf_cutoff_hz":        90,
      "imuf_sharpness":                2500,
      "__comment":                     "!!! Filters Gyro !!! type: 0=PT1, 1=BiQuad; ON for nonHelio, OFF for Helio",
      "gyro_lowpass_enabled":          "ON",
      "gyro_lowpass_type":             0,
      "gyro_lowpass_hz":               115,
      "gyro_lowpass_hz_roll":          115,
      "gyro_lowpass_hz_pitch":         115,
      "gyro_lowpass_hz_yaw":           105,
      "gyro_lowpass2_enabled":         "OFF",
      "gyro_lowpass2_type":            0,
      "gyro_lowpass2_hz":              0,
      "gyro_lowpass2_hz_roll":         0,
      "gyro_lowpass2_hz_pitch":        0,
      "gyro_lowpass2_hz_yaw":          0,
      "gyro_notch1_enabled":           "OFF",
      "gyro_notch1_hz":                0,
      "gyro_notch1_cutoff":            0,
      "gyro_notch2_enabled":           "OFF",
      "gyro_notch2_hz":                0,
      "gyro_notch2_cutoff":            0,
      "__comment":                     "!!! Filters dTerm !!! type: 0=PT1, 1=BiQuad",
      "dterm_lowpass_enabled":         "ON",
      "dterm_lowpass_type":            0,
      "dterm_lowpass_hz":              100,
      "dterm_lowpass_hz_roll":         100,
      "dterm_lowpass_hz_pitch":        100,
      "dterm_lowpass_hz_yaw":          100,
      "dterm_lowpass2_enabled":        "ON",
      "dterm_lowpass2_hz":             250,
      "dterm_lowpass2_hz_roll":        250,
      "dterm_lowpass2_hz_pitch":       250,
      "dterm_lowpass2_hz_yaw":         250,
      "dterm_notch_enabled":           "OFF",
      "dterm_notch_hz":                0,
      "dterm_notch_cutoff":            0,
      "yaw_lowpass_enabled":           "OFF",
      "yaw_lowpass_hz":                0,
      "__comment":                     "!!! Other settings !!! iterm_relax: 0=RP, 1=RPY, relax_type: 0=gyro, 1=setpoint",
      "throttle_boost":                5,
      "abs_control_gain":              0,
      "i_decay":                       4,
      "emu_boost":                     15,
      "emu_boost_limit":               20,
      "emu_boost_yaw":                 40,
      "emu_boost_limit_yaw":           40,
      "dterm_boost":                   0,
      "dterm_boost_limit":             0,
      "feathered_pids":                100,
      "iterm_rotation":                "ON",
      "vbat_pid_gain":                 "OFF",
      "__comment":                     "!!! NEW iRelax v2 !!!",
      "iterm_relax2_cutoff":           11,
      "iterm_relax2_cutoff_yaw":       25,
      "__comment":                     "!!! TPA !!!",
      "tpa_breakpoint":                1600,
      "tpa_rate_p":                    75,
      "tpa_rate_i":                    125,
      "tpa_rate_d":                    65,
      "spa_rate_p_roll":               110,
      "spa_rate_i_roll":               85,
      "spa_rate_d_roll":               110,
      "spa_rate_p_pitch":              110,
      "spa_rate_i_pitch":              85,
      "spa_rate_d_pitch":              110,
      "spa_rate_p_yaw":                130,
      "spa_rate_i_yaw":                70,
      "spa_rate_d_yaw":                130,
      "smart_dterm_smoothing_roll":    0,
      "smart_dterm_smoothing_pitch":   0,
      "smart_dterm_smoothing_yaw":     0,
      "witchcraft_roll":               2,
      "witchcraft_pitch":              2,
      "witchcraft_yaw":                0
   }
```
