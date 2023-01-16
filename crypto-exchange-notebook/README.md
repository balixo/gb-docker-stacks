# Based on Minimal Jupyter Notebook Stack to include ccxt and some other additional one might need for trade analytics. 

## build setps

### step 1
docker build -t crypto:basic .

### step 2
docker run -it crypto:basic

### step 3
got to docker ui and container
select crypto:basic and give following run parameters
host port to be set to 8888
and addtional NASDAQ_DATA_LINK_API_KEY (key can be obtained from 
https://data.nasdaq.com/account/profile
