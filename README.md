# MatrixGuard: Secure and Efficient Matrix Operations on ARM and x86

**Note:** Click [here](https://github.com/Maystern/SUSTech_CS201_Matrix_Multiplication/blob/main/doc/report.pdf) for report.

The primary objective of the project is to implement efficient matrix multiplication algorithms for both `ARM` and `x86` architectures, and to compare their performance using different optimization techniques, such as `multi-threading`, `instruction set optimization`, and `compilation optimization`.

If you find our work useful, please consider citing our work using the bibtex:
```
@Article{MatrixMultiplicationOptimization,
	author  = {Jiacheng Luo},
	title   = {MatrixGuard: Secure and Efficient Matrix Operations on ARM and x86},
	year    = {2023},
}
```

Running the project on the `Ubuntu` operating system is recommended, and `Git` and `CMake` tools are used for code version control, compilation and building.

The detailed steps for building the project code using `Git` and `CMake` are as follows:

1. Use the command `git clone https://github.com/Maystern/MatrixGuard.git` in the current directory to download the project code.
2. Use `cd MatrixGuard` command to navigate to the root directory of the project.
3. Execute the command `sh Run_Matmul.sh` in the root directory of the project to automatically compile the project code using `CMake`, which generates binary executable `matmulTest` and moves it to the `./build/bin` directory of the project root folder.
4. In the root directory of the project, run the command `./matmulTest matmulSizeLists` to perform and test matrix multiplication of size $matmulSize \times matmulSize$ as an example.
5. To enable and execute the optimization techniques, modify the `src/CMakeLists.txt` file in the root directory of the project.
