# LU_decomposition
In numerical analysis and linear algebra, lower–upper (LU) decomposition or factorization factors a matrix as the product of a lower triangular matrix and an upper triangular matrix. The product sometimes includes a permutation matrix as well. LU decomposition can be viewed as the matrix form of Gaussian elimination.


The basic principle here is – “A square matrix [A] can be written as the product of a lower triangular matrix [L] and an upper triangular matrix [U], one of them being unit triangular, if all the principal minors of [A] are non-singular.

A=LU

# LU_Decomposition Algorithm

Start

Read the elements of augmented matrix into arrays a and b

Calculate elements of L and U

Print elements of L and U

Find V by solving LV = B by forward substitution

Find X by solving UX = V by backward substitution

Print Array X as the solution

Stop

# Steps to run program

%%writefile filename.c
[this will provide file_name to a program ]

For compiling :

%%shell

gcc file_name.c -o output

For Running Program :

./output
