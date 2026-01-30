# 安裝
```bash
# 1. 安裝官方 PHP SDK
composer require temporal/sdk

# 2. 安裝 RoadRunner (這是運行 Worker 的高效能引擎)
composer require spiral/roadrunner
```
# 下載roadrunner二進制檔案
```bash
./vendor/bin/rr get-binary 
```

# 根據docker配置在docker裡面寫下mysql的配置檔案

- docker/mysql/init.sql
![alt text](image.png)

# 記得填寫env數值
![alt text](image-1.png)
