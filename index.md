# Todd Fleming

Selected Projects and Experiments

All the live links work in **Chrome**. All of them except LaserWeb4 also work in **Firefox**.

| Live | Source | Description | Technologies |
| --- | --- | --- | --- |
| [Clang In Browser](https://tbfleming.github.io/cib/) | [cib](https://github.com/tbfleming/cib) | Clang runs in the browser, generating wasm which also runs in the browser. | llvm, emscripten, custom wasm linker
| [em-shell](https://tbfleming.github.io/em-shell/) | [em-shell](https://github.com/tbfleming/em-shell) | busy-box running in the browser | emscripten, service worker
| [maze](https://godbolt.org/g/HF9Yjj) | [maze](https://github.com/tbfleming/compile_maze_solver) | Solve a maze at compile time. Solution is in the disassembly. | C++17 constexpr |
| [OffsetMesh](https://tbfleming.github.io/OffsetMesh/) | [OffsetMesh](https://github.com/tbfleming/OffsetMesh) | Uses GPU to offset STL meshes. Potential use in 3D CAM. | Computation in WebGL |
| [LaserWeb4](https://laserweb.github.io/LaserWeb4) | [LW4](https://github.com/LaserWeb/LaserWeb4) | Control your laser cutter or CNC machine. I joined forces with the LaserWeb team to create a fresh rewrite based on React and raw WebGL. I also brought in and improved jscut technology. | react+redux, emscripten, raw WebGL
| [jscut](http://jscut.org) | [jscut](https://github.com/tbfleming/jscut) | Convert SVG into gcode for your CNC machine. First plugin-free browser-based CAM. | emscripten, raw WebGL |
| | [grbl-lpc](https://github.com/gnea/grbl-LPC) | I ported grbl to the LPC1769 for driving laser cutters and CNC machines. Has step rates up to 200 kHz. | Embedded real-time control |
