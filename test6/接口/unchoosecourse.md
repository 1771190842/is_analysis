<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：unchooseCourse [返回](../README.md)
用例： [退选](../用例/退选.md)

- 权限：
    老师

- 功能：
    退选课程。

- API请求地址：
   接口基本地址/v1/api/chooseCourse

- 请求方式 ：
    GET

- 请求参数说明:
    无

- 返回实例：

        {
            "status": true,
            "info": null,
            "data": [
                {
                "course_id":"2233"
                "user_id": "4545",
                "UPDATE_DATE": "2018-04-02 13:48:01"},
                {
                }
            ]
        }


- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|
  |course_id |课程id|
  |user_id|用户id|
