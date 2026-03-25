# rv32i-soc

This repository is intended to host the **RV32I SoC** project (a 32-bit RISC-V Integer base ISA system-on-chip implementation).

At the moment, this repository is in an **initial scaffold state** with a minimal file layout. This README documents the complete current structure and serves as a starting point for future expansion.

---

## Repository Structure (Current)

```text
rv32i-soc/
└── README.md
```

There are currently **no source subfolders** (for example `rtl/`, `tb/`, `sim/`, or `docs/`) checked into the repository yet.

---

## File-by-File Inventory

### `README.md`
- Primary documentation entry point for the repository.
- Defines the project purpose and current status.
- Tracks the complete, up-to-date folder/file structure.

---

## Subfolder Inventory

The repository currently contains **no project subfolders**.

When development begins, the following folders are commonly added in RV32I SoC projects:

- `rtl/` — synthesizable Verilog/SystemVerilog source files.
- `tb/` — testbench code.
- `sim/` — simulation scripts and wave setup.
- `sw/` — bare-metal software/tests for CPU validation.
- `constraints/` — FPGA timing and pin constraints.
- `docs/` — architecture, memory map, block diagrams.
- `scripts/` — build/automation helpers.

---

## Repository Status

- **Project state:** Bootstrapped / documentation-only.
- **Code files present:** No.
- **Verification assets present:** No.
- **Build scripts present:** No.

---

## Notes

If you add new files or subfolders, update this README so it continues to provide a complete inventory of the repository.
