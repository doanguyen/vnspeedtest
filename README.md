# Speedtest
Kiểm tra tốc độ server khi kết nối tới các địa chỉ ở Việt Nam

Bước 1: 
Tải speedtest.py bằng cách sử dụng:
```
wget https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py 
```
Bước 2:
Tải vns (vnspeedtest) - trong đó bao gồm danh sách server tại Việt Nam:
```
wget https://raw.githubusercontent.com/doanguyen/vnspeedtest/master/vns
```
Bước 3:
Cài đặt quyền và chạy:
```
chmod +x vns
./vns

```

Cách lấy ra số liệu tốc độ download, upload:
```
grep Download output.txt | awk '{print $2}'
```
