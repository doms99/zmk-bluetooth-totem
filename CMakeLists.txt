if ((NOT CONFIG_ZMK_SPLIT) OR CONFIG_ZMK_SPLIT_ROLE_CENTRAL)
  target_sources_ifdef(CONFIG_ZMK_BEHAVIOR_HOLD_TAP_LONG app PRIVATE src/behaviors/behavior_hold_tap_long.c)
endif()
