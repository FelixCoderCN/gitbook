# RiSE App接口文档 V1

```text
{ //零件信息查询 part_info:[ { id:'零件号', name:'零件名称', supplier_abbr:'供应商缩写', car_type:'车型', cur_price:'Current Price' } ],  //生产采购，一般采购 rfq:{  {  p_pur:[ id:'RFQ号', name:'RFQ项目名称', type:'类型', car_type:'车型', count_times:‘轮次’, end_date:'本轮RFQ截止日期', rate:'MQ完成，EP/PL/CF未完成'  ],  g_pur:[ id:'RFQ号', name:'RFQ项目名称', type:'单据类型', purchase:'采购员', contact:'021-00000888' car_type:'车型', count_times:‘轮次’, price_status:'竞价/询价' end_date:'本轮RFQ截止日期', rate:true //是否评定  ] } },  //供应商 supplier:[ { sname:'供应商', svw_no:'svw号' } ],  //车型项目 model_project:[ { car_type:'车型名字', car_year:'车的年份', car_platform:'车的平台', plant:'工厂', tips:'tips', sop_date:'2021KW40', like:true //是否收藏 } ],   //会议议题查询 meeting_agenda:[ { type:'csc', title:'会议标题', address:'会议地点' date:'2021-09-09 09:12:00' } ]}
```

