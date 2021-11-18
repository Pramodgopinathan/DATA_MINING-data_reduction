# DATA MINING - DATA REDUCTION

## Abstract
It is a process of reducing the size of the data, however we should be preserving the integrity of data while doing data reduction process. It is also know as pre-processing technique that helps in obtaining the reduced representation of dataset from the available dataset. As we all know that complex data may take very long time to run on the complete dataset. Hence we need to do some form of data reduction before modeling.

## Reduction strategies
There are many strategies which could be used for reduce data. 
* Data cube aggregation
* Data compression
* Dimensionality reduction
* Numerosity reduction
* Discretization and concept hierarchy generation

### Data Cube Aggregation
Consider you have the data of some company where sales per quarter for the year 2010 to the year 2021. In case you want to get the annual sale per year then you just have to aggregate the sales per quarter for each year. In this way, aggregation provides you with the required data which is much smaller in size and thereby we achieve data reduction even without losing any data.

Limitation: 
The data that is pulled into data cubes has already been summarized. Detail can be found in the source system, but users can’t drill into it from the cube. 

Example: [here](https://github.com/Pramodgopinathan/DATA_MINING-data_reduction/blob/main/Data_Cube_Aggregation.ipynb)

Outcome: 1035 row size is downsize to 23 row using aggregation

### Data compression
Data Compression is a technique in which the size of data is reduced without loss of information.
We have two method which would help for data compression:
* Lossless Method: Mainly confidential information and sensitive documents make use of lossless data compression. File formats like BMP, GIF etc., also use this technique. Some very crucial techniques of lossless data compression are: Arithmetic Coding, Huffman Coding, LZW (Lempel Ziv – Welch) ,RLE (Run Length Encoding).
* Lossy Method: Mainly MP3 audio, MPEG video, and JPEG image formats make use of the technique of lossy data technique. Some very crucial techniques of lossy data compression are: DWT (Discrete Wavelet Transform), DCT (Discrete Cosine Transform), Transform Coding.

### Dimensionality Reduction
Reducing the dimension of the feature space is called dimensionality reduction.
