【发布内容】

  1. 运营端-5.17prd所有需求，erp，已发布qa
  


【发布配置】
  ERR新增接口：
	Get /data/bikeUnlock/detail/export  单车开锁统计excel 导出 
	POST /dbikeoperation/erp/no_parking_zone/updateTolerance2Null 删除停车带容错
  

【修改配置】
  系统设置->权限设置->权限管理 -> 运营城市管理 -> 城市信息管理(添加接口：删除停车带容错)
	
  系统设置->权限设置->权限管理 -> 城市运营 -> 车辆运营 -> 车辆运营数据 -> 开锁成功失败数据 -> 导出详情(添加接口：单车开锁统计excel 导出 )



【发布环境】

  发布到qa环境，发布分支：qa