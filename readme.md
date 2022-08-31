# Keithley KickStart 2.0 Performance Verification and Operation Introduction

## System Requirement: CPU: 4-Core Processor, RAM: 16GB, Display: 192X1080, Disk Sapce: 100GB

![image](https://user-images.githubusercontent.com/55008636/187593966-8dd1d0e0-d2bb-4b99-bc5b-b42bb7dfd413.png)

## Software Version: KickStart 2.9

![image](https://user-images.githubusercontent.com/55008636/187593706-01bb6d0e-9525-4a36-b7e9-d84fa54385f5.png)

## Verification Instrument

https://www.tek.com/tw/products/keithley/source-measure-units/2600b-series-sourcemeter

## Verification Items

1. Does KickStart use Trigger Model for dual channel sweep? Ans: Yes, trigger model is used in the dual SMU sweep!! Excellent!

![Screenshot 2022-08-31 12-44-38](https://user-images.githubusercontent.com/55008636/187594557-5bc4d27f-e70e-4e5e-9410-772fbae2927c.png)

2. Can the max sweep points exceed 100K/60K/30K/29K pts?　Ans: Error Message - IOTimeoutException

![image](https://user-images.githubusercontent.com/55008636/187595148-660ee83f-311d-4169-970e-19cea501bb29.png)

If the max point is over 25K pts, it's not recommended. 25K pts is still accepted in ths experiment as follow,

![image](https://user-images.githubusercontent.com/55008636/187596170-d7451ca6-7db9-47d2-af59-8b9dd26ff032.png)


