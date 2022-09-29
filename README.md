# toy-api
Toy example API in R

### what to improve
- write a interface to your favorite database(postgres, ...) from R and store calculated yearly data in UTC date format (columns Date stored as timestamp and is primary key and Value stored as numeric)
see: R/rest_operations.R
- write unit tests to check whether data are stored and read correctly
see: tests/testthat/test-read_quandl_unemployement_data.R
see: tests/testthat/test-rest_operations.R
- add automated build (for example via github action)
- dockerize app

### recommendations
- You can run skeleton API using function: ' toyAPI::run_api()' after loading package throught 'devtools::load_all(".")'
- We recommend to use RStudio IDE for development (u can used our dockerized version with preinstalled common libs https://hub.docker.com/repository/docker/powerex/pwx-rstudio) 


### Usefull links:
- https://r-pkgs.org/workflows101.html 
- https://www.rplumber.io/
