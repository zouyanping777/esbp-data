#接口说明
1、根据IMSI获取车辆缓存信息
地址 http://10.0.0.143:9098/vehicleInfo/getUnameCache/460040261611768
返回：{
    "code":"1000",
    "msg":null,
    "data":{
        "uname":"460040261611768",
        "vinCode":"14F0034527",
        "license":"川BUM823",
        "iccid":"898602B2221500011768"
    }
}
2、根据IMSI获取车辆网车辆信息
地址：http://10.0.0.143:9098/vehicleInfo/getUnameIov/460040261611768
返回：{
    "code":"1000",
    "msg":null,
    "data":{
        "uname":"460040261611768",
        "vinCode":"14F0034527",
        "license":"川BUM823",
        "iccid":"898602B2221500011768"
    }
}
3、根据IMSI修改缓存信息
地址：http://10.0.0.143:9098/vehicleInfo/getUnameCache/460040261611768
返回：{
    "code":"1000",
    "msg":null,
    "data":{
        "uname":"460040261611768",
        "vinCode":"14F0034527",
        "license":"川BUM823",
        "iccid":"898602B2221500011768"
    }
}


参数说明：
/**
	 * IMSI
	 */
	private String uname;
	
	/**
	 * 车架号
	 */
	private String vinCode;			
	
	/**
	 * 车牌号
	 */
	private String license;		
	
	/**
	 * iccid
	 */
	private String iccid;
