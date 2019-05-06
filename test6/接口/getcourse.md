﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getcourse  [返回](../README.md)
用例： [选课](../用例/选课.md)

- 权限：
    老师

- 功能：
    返回可选课程的列表。

- API请求地址：
   接口基本地址/v1/api/getcourse

- 请求方式 ：
    GET

- 请求参数说明:
    无

- 返回实例：

        {
            "status": true,
            "info": null,
            "total": 121,
            "data": [
                {
                "grade":"3"
                "capacity": "90",
                "adress": "10555",
                "repository": "is_ass",
                "teacher": "xxxx",
                "UPDATE_DATE": "2018-04-02 13:48:01"},
                {
                ...其他课程
                }
            ]
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |total|返回课程|
  |grade|适用学期|
  |capacity|课程容量|
  |adress|上课地点|
  |repository|指定的github仓库名|
  |teacher|选择这门课的老师|
