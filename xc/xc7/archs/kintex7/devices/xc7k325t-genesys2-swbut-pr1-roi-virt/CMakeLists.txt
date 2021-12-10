add_xc_device_define_type(
  ARCH kintex7
  DEVICE xc7k325t-genesys2-swbut-pr1
  ROI_DIR ${symbiflow-arch-defs_SOURCE_DIR}/xc/xc7/archs/kintex7/devices/xc7k325t-genesys2-swbut-pr1-roi-virt
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
