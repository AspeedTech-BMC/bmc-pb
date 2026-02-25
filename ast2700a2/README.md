# AST2700 A2 Prebuilt Binaries

This folder contains prebuilt firmware specifically for ASPEED AST2700 A2 silicon.

## Firmware List

### Caliptra Firmware
- **caliptra-fw.bin**
  - **Source**: [chipsalliance/caliptra-sw (rt-1.2.1)](https://github.com/chipsalliance/caliptra-sw/tree/rt-1.2.1)
  - **Features**: Includes ASPEED 4 ECC public keys, 32 LMS public keys, 1 ECC signature and 1 LMS signature.

### DDR PHY Firmware
- **ddr4_pmu_train_imem.bin / ddr4_pmu_train_dmem.bin**: DDR4 PMU training firmware.
- **ddr4_2d_pmu_train_imem.bin / ddr4_2d_pmu_train_dmem.bin**: DDR4 2D PMU training firmware.
- **ddr5_pmu_train_imem.bin / ddr5_pmu_train_dmem.bin**: DDR5 PMU training firmware.

### Display and System
- **dp_fw.bin**: DisplayPort controller firmware.
- **uefi_ast2700.bin**: UEFI reference BIOS image.
