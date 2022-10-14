# -*- coding: utf8 -*-
from rainbow_sdk.rainbow_client import RainbowClient
init_param = {
    "connectStr": "api.rainbow.woa.com:8080",
    "tokenConfig": {
        "app_id": "5ecac09e-a390-4070-a10d-c0b28d42b652",
        "user_id": "$user_id",
        "secret_key": "$secret_key",
        # 使用时请替换为项目信息页中自助添加的user_id 和 secret_key
    },
}
rc = RainbowClient(init_param)
res = rc.get_configs_v3("test_group_001", env_name="Default")
print("result:")
# print(res)


test_num = 700

for i in range(1,test_num+1):
    init_param = {"connectStr": "api.rainbow.oa.com:8080",
     "tokenConfig": {
     "app_id": "5ecac09e-a390-4070-a10d-c0b28d42b652",
     "user_id": "$user_id",
     "secret_key": "$secret_key", # 使用时请替换为项目信息页中自助添加的user_id 和 secret_key
     },}
    rc = RainbowClient(init_param);
    res = rc.get_configs_v3("test_group_001", env_name="Default");
    if i%100==0:
        print("======================");
        print("download num:",i)
print("all finished")
