# Bachelor_work

### This program basically needs tensorflow version 1.5.0. Because the above is the AVX command CPU, which does not work with many CPUs, also causes some errors.

#### Running the script with Docker:
###### Step 1 - Clone the project:
```
git clone https://github.com/Threadripper1/Bachelor_work.git
```
###### Step 2 - Extracting Dataset:
```
docker build -t captcha-solve .
```

###### Step 2 - Starting docker container with port :5000
```
docker run --rm -it -p 5000:5000 captcha-solve
```