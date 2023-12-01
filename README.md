# new-backend

## 架構

有 6 個 Containers：
- mysqld：資料的儲存
- named：BIND9 DNS server
- flask：API server
- backend_app：domain 回收機制
- fluentd：log 收集器
- elasticsearch：log 分析工具

## 請執行以下指令

```
# make pull
# make init
```

## 建構
```
# sudo make build
```

## 運行

```
# sudo make run
```

## 測試

```
# sudo make test
```
