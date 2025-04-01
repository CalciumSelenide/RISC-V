# RISC-V
RISC-V is an open standard instruction set architecture (ISA) based on established reduced instruction set computer (RISC) principles. Curiosity has led to the creation of this repository, and potentially a chip design. For now, though, only time will tell what this will become. :)

Proposed tool flow for the project is all open source and should enable all essential aspects of circuit design/simulation upto chip place and route. This is a rough draft so tools may be added, changed, removed, etc. The proposed output of this project is a RISC-V processor made using the Sky130 process.

Tool Flow Rough Draft: 
1. Download **Sky 130nm PDK**: https://skywater-pdk.readthedocs.io/en/main/
2. Download **NGSpice**: https://ngspice.sourceforge.io/
3. Download **\<insert circuit capture tool here>**: https://www.electronicsforu.com/special/cool-stuff-misc/open-source-circuit-design-software
4. Download **KLayout**: https://www.klayout.de/
5. Download **OpenRoad**: https://theopenroadproject.org/
6. Download **Chisel**: https://www.chisel-lang.org/

**Next Step**: Check what data actually comes with the Sky130 PDK. Essentials would be LEF/DEF, liberty timing files, verilog behavioral code, GDS standard cells, pad cells, CDL netlists (or equivalent SPICE derivative), and device models
