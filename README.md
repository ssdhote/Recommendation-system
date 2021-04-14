# Recommendation-system

It works based on Collaborative Filtering

How Collaborative Filtering Works:

step 1: Preprocessing before building matrix

step 2: Build a matrix between customers and products

step 3: Find similarity between customers

        we have 2 methods:
        
          1. cosine based similarity
                      cos(A,B) = A.B / (|A|.|B|)
          
          2. correlation based similarity
                        corr(A,B) = Covariance(A,B)/(std(A)*std(B))
step 4: once we find similarity items will be recommended

Negatives of Collaborative Filtering:

Memory based - as it needs a huge amount of matrix with data

As big matrix computationally heavy

How to reduce Computation

Randomly sample customers
Discard infrequent buyers
Discard items that are very popular or unpopular
clustering can decrease number of rows
PCA can reduce number of columns
Data used:

Book Recommendation is done using Book data set
Programming Language: Python

The Code regarding Book recommendation are present in this Repository in detail.
