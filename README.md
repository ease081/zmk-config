# ZMK Config for Charybdis 4x6 (nice!nano v2)

## Quick steps (no Git needed)
1. Upload this whole ZIP to a new GitHub repository (keep folder structure).
2. Open the **Actions** tab -> run starts automatically (or click "Run workflow").
3. When it finishes, open the run and download the **firmware-uf2** artifact -> you'll get `left.uf2` and `right.uf2`.
4. Put each half into bootloader (double-tap reset), then drag the matching UF2 file onto the `NICENANO` drive.

## Non-RGB boards
- Edit `config/build.yaml` and change shields to `charybdis_4x6_left` and `charybdis_4x6_right`, then push to rebuild.
