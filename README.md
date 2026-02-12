# ASPEED BMC Prebuilt Binaries (bmc-pb)

This repository hosts prebuilt firmware binaries and images for various ASPEED BMC SoCs. These binaries are essential for hardware initialization, security features (Caliptra), and system booting.

## Repository Structure

The content is organized by SoC model and silicon revision to ensure compatibility:

- `ast2700a1/`: Binaries for AST2700 A1
- `ast2700a2/`: Binaries for AST2700 A2
- `ast2755a0/`: Binaries for AST2755 A0
- `ast1040a0/`: Binaries for AST1040 A0

## Usage

These binaries are typically used during the image composition process (e.g., Yocto/OpenBMC recipes). Ensure you select the correct folder matching your hardware silicon revision.

## License

Please refer to the ASPEED official documentation or contact ASPEED support for the licensing terms of these prebuilt binaries.
