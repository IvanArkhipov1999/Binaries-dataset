# Binaries-dataset
This repository contains dataset of executable binaries for analysis and calculated statistics.

Directory [arm32-g++-ubuntu](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/arm32-g%2B%2B-ubuntu) contains executable binaries files, compiled by arm-linux-gnueabihf-g++ compiler version 7.5.0 on Ubuntu 18.04 with -std=gnu++11 flag for processor with architecture arm.

Directory [arm64-g++-ubuntu](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/arm64-g%2B%2B-ubuntu) contains executable binaries files, compiled by aarch64-linux-gnu-g++ compiler version 7.5.0 on Ubuntu 18.04 with -std=gnu++11 flag for processor with architecture AArch64.

Directory [mips64el-g++-ubuntu](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/mips64el-g%2B%2B-ubuntu) contains executable binaries files, compiled by mips64el-linux-gnuabi64-g++ compiler version 7.5.0 on Ubuntu 18.04 with -std=gnu++11 flag for processor with architecture MIPS R3000.

Directory [x86_64-g++-ubuntu-O0](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/x86_64-g%2B%2B-ubuntu-O0) contains executable binaries files, compiled by g++ compiler version 7.5.0 on Ubuntu 18.04 with -std=gnu++11 and -O0 flags for processor with architecture x86_64.

Directory [x86_64-g++-ubuntu-O3](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/x86_64-g%2B%2B-ubuntu-O3) contains executable binaries files, compiled by g++ compiler version 7.5.0 on Ubuntu 18.04 with -std=gnu++11 and -O3 flags for processor with architecture x86_64.

Directory [x86_64-g++-ubuntu](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/x86_64-g%2B%2B-ubuntu) contains executable binaries files, compiled by g++ compiler version 7.5.0 on Ubuntu 18.04 with -std=gnu++11 flag for processor with architecture x86_64.

Directory [data](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/data) contains zip archives with csv file, where every column contains propotions for given sequence in every file. Csv files contains properties for binary sequences up to 10 in length.

Directory [primary-statistics](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/primary-statistics) contains text files with mean, standard deviation, variance, median, minimum and maximum for binary sequences up to 10 in length.

Directory [rare_sequences](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/rare_sequences) contains text files with sequences up to 10 in length, which are not found in all binary files. These files contains mean of such sequences and percentage of files that do not contain the sequence.

Directory [norm-distribution-p-value](https://github.com/IvanArkhipov1999/Binaries-dataset/tree/main/norm-distribution-p-value) contains text files with sequences up to 10 in length, the distribution of which is normal distribution. These files contains p-value, mu and sigma paraneters of normal distribution.
