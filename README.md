# sonic-wistron-binaries

## Description
SONiC binaries for Wistron platforms (firmware, kernel modules, and utility tools).

## Directory Layout
The following directory layout reflects the current released binaries.
```text
├── 6512-32R
│   ├── docs
│   ├── driver
│   │   ├── kernel_5.10.0-8-2
│   │   │   └── gpio_i2c.ko
│   │   └── kernel_6.1.0-29-2
│   │       └── gpio_i2c.ko
│   ├── firmware
│   │   ├── bmc
│   │   │   ├── Y211TR1_BMC_v1.06_260122_enc.ima
│   │   │   └── Y211TR1_BMC_v1.06_260122.ima
│   │   ├── cpld
│   │   │   ├── Main_board_CPLD0_firmware.jed
│   │   │   └── Main_board_CPLD1_firmware.jed
│   │   └── fpga
│   │       ├── CPU_board_FPGA_firmware.jbc
│   │       └── Main_board_FPGA_firmware.jbc
│   └── tools
│       ├── FPGA_CPLD_Upgrade_tool.txt
│       ├── jbimain
│       └── updateCPLD
├── ES-1227-36TS-B
│   └── cpld
│       ├── mojito_syscpld_release_v1.1.0_251030.jed
│       ├── mojito_syscpld_release_v1.2.0_251113.jed
│       ├── mojito_syscpld_release_v1.3.0_251120.jed
│       └── mojito_syscpld_release_v1.4.0_260114.jed
├── ES-1227-54TS-B
│   └── cpld
│       ├── kyoto_syscpld_release_v1.0.0_250905.jed
│       ├── kyoto_syscpld_release_v1.1.0_250924.jed
│       └── kyoto_syscpld_release_v1.3.0_260116.jed
├── ES-2227-54TS-P
│   └── cpld
│       └── yamazaki_mb_syscpld_release_v2.1_20231030.jed
└── README.md
```
