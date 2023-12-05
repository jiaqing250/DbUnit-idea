原项目是 DbUnit-idea 插件，但是原格式是xml格式，不是我想要的，为了符合dbunit单元测试数据的格式，我稍微修改了一下

![](https://raw.githubusercontent.com/kTT/dbunit-extractor/master/dbunit-extractor.png)

效果如下

```groovy
    @DbUnit(content = {
    //下面两条是生成的数据
    roster_family_member(roster_family_member_id: "1", customer_id: "85570204515450880", roster_id: "1", member_name: "成员姓名", member_mobile: "18888888888", member_company: "成员单位", relationship: "10", create_date: "2023-12-04 08:15:22", update_date: "2023-12-04 08:15:22")
    roster_work_experience(roster_work_experience_id: "1", customer_id: "85570204515450880", roster_id: "1", company_name: "单位名称", start_date: "2023-12-04 16:15:21", end_date: "2023-12-04 16:15:21", position: "职务", salary: "1000", resignation_reason: "不用", create_date: "2023-12-04 08:15:22", update_date: "2023-12-04 08:15:22")
})
```

# License

This project is licensed under the MIT License.