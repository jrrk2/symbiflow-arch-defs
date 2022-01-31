add_xc_device_define(
  ARCH kintex7
  PART xc7k325tffg900-2
  USE_ROI
  DEVICES xc7k325t-genesys2-uart xc7k325t-genesys2-swbut xc7k325t-genesys2-swbut-pr1 xc7k325t-genesys2-switch-processing-pr1 xc7k325t-genesys2-switch-processing-pr2

)
add_xc_device_define(
  ARCH kintex7
  PART xc7k325tffg900-2
  USE_OVERLAY
  DEVICES xc7k325t-genesys2-swbut-overlay xc7k325t-genesys2-switch-processing-overlay
)
