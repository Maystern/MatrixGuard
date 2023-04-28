# CS201 Project：Optimization of Matrix Multiplication on CPU

The final assignment for the course `CS201 Discrete Mathematics` at the Southern University of Science and Technology aims to implement a fast matrix multiplication algorithm on both the `ARM` and `x86` architectures. The primary objective of the project is to test and compare the performance of the two architectures with different optimization techniques.

If you find our work useful, please consider citing our work using the bibtex:
```
@Article{ssformers,
	author  = {Jiacheng Luo},
	title   = {Matrix Blocking, Instruction Set and Parallelization:
Optimization of Matrix Multiplication on
Hierarchical CPUs},
	year    = {2023},
}
```
Click here for report: [>> Report <<](https://github.com/Maystern/SUSTech_CS201_Matrix_Multiplication/blob/main/doc/report.pdf)


## 如何运行 

项目推荐在 `Ubuntu` 环境下运行。

1. 使用命令 `git clone https://github.com/Maystern/SUSTech_CS201_Matrix_Multiplication.git` 将项目下载到当前目录。
2. 在当前目录下执行`cd SUSTech_CS201_Matrix_Multiplication` 进入项目根目录。
3. 在项目根目录执行`sh Run_Matmul.sh` 命令，该命令执行后，将在`./build`中自动使用 `cmake` 编译原代码文件，并将位于`./build/bin`目录下的生成的二进制可执行程序`matmulTest`移动至项目根目录处。
4. 您可以在项目根目录中，使用`./matmulTest matmulSizeLists` 运行所有$matmulSize \times matmulSize$ 大小的矩阵乘法，作为例子。
5. 您可以在 `src` 下的 `CMakeLists.txt` 中选择是否开启多线程优化、指令集优化、编译优化，需要重新 `build`。
