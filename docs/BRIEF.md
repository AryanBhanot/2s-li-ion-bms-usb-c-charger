# 2S Li-ion BMS USB-C Charger

The previous run only created the planning documents and did not create
a schematic.

Now proceed to the next stage.

Using the existing SPEC.md, SUBSYSTEMS.md, BOM.md and DECISIONS.md:

1. Resolve the exact components required for the 2S Li-ion BMS and
   USB-C 5 V to 8.4 V charger.
2. Verify every IC pinout and critical specification against official
   manufacturer datasheets.
3. Create the complete KiCad schematic.
4. Include all battery connections:
   B-, B1, B+
5. Include P+ and P- protected output.
6. Include USB-C input and 5.1 kΩ CC resistors.
7. Include the 5 V to 8.4 V CC/CV charger.
8. Include BMS protection, balancing and back-to-back MOSFETs.
9. Assign real footprints.
10. Run KiCad ERC.

Do NOT create the PCB layout yet.

If any component or pinout cannot be verified, stop and report it
instead of guessing.
