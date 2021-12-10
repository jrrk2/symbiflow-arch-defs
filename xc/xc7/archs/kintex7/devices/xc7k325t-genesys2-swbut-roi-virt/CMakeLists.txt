add_xc_device_define_type(
  ARCH kintex7
  DEVICE xc7k325t-genesys2-swbut
  ROI_DIR ${PRJXRAY_DB_DIR}/kintex7/harness/arty-a7/swbut
  TILE_TYPES
    CLBLL_L
    CLBLL_R
    CLBLM_L
    CLBLM_R
    BRAM_L
  PB_TYPES
    SLICEL
    SLICEM
    BRAM_L
)
