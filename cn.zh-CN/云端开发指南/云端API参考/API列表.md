# API列表 {#reference_kd4_l4z_wdb .reference}

以下是物联网平台 API 列表。

## 产品管理相关 API {#section_sqj_czc_xdb .section}

|API|描述|
|:--|:-|
|[CreateProduct](cn.zh-CN/云端开发指南/云端API参考/产品管理/CreateProduct.md#)|创建产品。|
|[UpdateProduct](cn.zh-CN/云端开发指南/云端API参考/产品管理/UpdateProduct.md#)|修改产品信息。|
|[QueryProductList](cn.zh-CN/云端开发指南/云端API参考/产品管理/QueryProductList.md#)|查询产品列表。|
|[QueryProduct](cn.zh-CN/云端开发指南/云端API参考/产品管理/QueryProduct.md#)|查询产品详细信息。|
|[DeleteProduct](cn.zh-CN/云端开发指南/云端API参考/产品管理/DeleteProduct.md#)|删除指定产品。|
|[CreateProductTags](cn.zh-CN/云端开发指南/云端API参考/产品管理/CreateProductTags.md#)|创建产品标签。|
|[UpdateProductTags](cn.zh-CN/云端开发指南/云端API参考/产品管理/UpdateProductTags.md#)|更新产品标签。|
|[DeleteProductTags](cn.zh-CN/云端开发指南/云端API参考/产品管理/DeleteProductTags.md#)|删除产品标签。|
|[ListProductTags](cn.zh-CN/云端开发指南/云端API参考/产品管理/ListProductTags.md#)|查询产品的所有标签。|
|[ListProductByTags](cn.zh-CN/云端开发指南/云端API参考/产品管理/ListProductByTags.md#)|根据标签查询产品。|

## 设备管理相关 API {#section_dcj_qzc_xdb .section}

|API|描述|
|:--|:-|
|[RegisterDevice](cn.zh-CN/云端开发指南/云端API参考/设备管理/RegisterDevice.md#)|注册设备。|
|[QueryDeviceDetail](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceDetail.md#)|查询设备详情。|
|[BatchQueryDeviceDetail](cn.zh-CN/云端开发指南/云端API参考/设备管理/BatchQueryDeviceDetail.md#)|批量查询设备详情。|
|[QueryDevice](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDevice.md#)|查询产品的设备列表。|
|[DeleteDevice](cn.zh-CN/云端开发指南/云端API参考/设备管理/DeleteDevice.md#)|删除设备。|
|[GetDeviceStatus](cn.zh-CN/云端开发指南/云端API参考/设备管理/GetDeviceStatus.md#)|获取设备的运行状态。|
|[BatchGetDeviceState](cn.zh-CN/云端开发指南/云端API参考/设备管理/BatchGetDeviceState.md#)|批量获取设备状态。|
|[DisableThing](cn.zh-CN/云端开发指南/云端API参考/设备管理/DisableThing.md#)|禁用设备。|
|[EnableThing](cn.zh-CN/云端开发指南/云端API参考/设备管理/EnableThing.md#)|解禁设备。|
|[BatchCheckDeviceNames](cn.zh-CN/云端开发指南/云端API参考/设备管理/BatchCheckDeviceNames.md#)|批量检查设备名称。|
|[BatchRegisterDeviceWithApplyId](cn.zh-CN/云端开发指南/云端API参考/设备管理/BatchRegisterDeviceWithApplyId.md#)|根据 ApplyId 批量申请设备。|
|[BatchRegisterDevice](cn.zh-CN/云端开发指南/云端API参考/设备管理/BatchRegisterDevice.md#)|批次申请特定数量设备。|
|[QueryBatchRegisterDeviceStatus](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryBatchRegisterDeviceStatus.md#)|查询批量注册设备状态。|
|[QueryPageByApplyId](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryPageByApplyId.md#)|查询批次设备列表。|
|[QueryDeviceEventData](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceEventData.md#)|查询设备的事件历史数据。|
|[QueryDevicePropertyData](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDevicePropertyData.md#)|查询设备的属性历史数据。|
|[QueryDevicePropertiesData](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDevicePropertiesData.md#)|批量查询指定设备的多个属性的历史数据。|
|[QueryDeviceServiceData](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceServiceData.md#)|获取设备的服务记录历史数据。|
|[InvokeThingService](cn.zh-CN/云端开发指南/云端API参考/设备管理/InvokeThingService.md#)|调用设备的服务。|
|[InvokeThingsService](cn.zh-CN/云端开发指南/云端API参考/设备管理/InvokeThingsService.md#)|批量调用设备的服务。|
|[QueryDevicePropertyStatus](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDevicePropertyStatus.md#)|查询设备的属性快照。|
|[SetDeviceProperty](cn.zh-CN/云端开发指南/云端API参考/设备管理/SetDeviceProperty.md#)|设置设备的属性。|
|[SetDevicesProperty](cn.zh-CN/云端开发指南/云端API参考/设备管理/SetDevicesProperty.md#)|批量设置设备属性。|
|[SaveDeviceProp](cn.zh-CN/云端开发指南/云端API参考/设备管理/SaveDeviceProp.md#)|设置设备标签。|
|[QueryDeviceProp](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceProp.md#)|查询设备标签列表。|
|[DeleteDeviceProp](cn.zh-CN/云端开发指南/云端API参考/设备管理/DeleteDeviceProp.md#)|删除设备标签。|
|[GetThingTopo](cn.zh-CN/云端开发指南/云端API参考/设备管理/GetThingTopo.md#)|查询网关设备或子设备所具有的拓扑关系。|
|[NotifyAddThingTopo](cn.zh-CN/云端开发指南/云端API参考/设备管理/NotifyAddThingTopo.md#)|通知云端增加设备拓扑关系。|
|[RemoveThingTopo](cn.zh-CN/云端开发指南/云端API参考/设备管理/RemoveThingTopo.md#)|移除网关设备或子设备所具有的拓扑关系。|
|[QueryDeviceStatistics](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceStatistics.md#)|获取设备的统计数量。|
|[GetGatewayBySubDevice](cn.zh-CN/云端开发指南/云端API参考/设备管理/GetGatewayBySubDevice.md#)|根据挂载的子设备信息查询对应的网关设备信息。|
|[QueryDeviceByTags](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceByTags.md#)|根据标签查询设备。|
|[SetDeviceDesiredProperty](cn.zh-CN/云端开发指南/云端API参考/设备管理/SetDeviceDesiredProperty.md#)|为指定设备批量设置期望属性值。|
|[QueryDeviceDesiredProperty](cn.zh-CN/云端开发指南/云端API参考/设备管理/SetDeviceDesiredProperty.md#)|查询指定设备的期望属性值。|
|[QueryDeviceFileList](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceFileList.md#)|查询指定设备上传到物联网平台的所有文件。|
|[QueryDeviceFile](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryDeviceFile.md#)|查询指定设备上传到物联网平台的指定文件信息。|
|[DeleteDeviceFile](cn.zh-CN/云端开发指南/云端API参考/设备管理/DeleteDeviceFile.md#)|删除指定设备上传到物联网平台的指定文件。|
|[BatchUpdateDeviceNickname](cn.zh-CN/云端开发指南/云端API参考/设备管理/BatchUpdateDeviceNickname.md#)|批量更新设备备注名称。|
|[QueryLoRaJoinPermissions](cn.zh-CN/云端开发指南/云端API参考/设备管理/QueryLoRaJoinPermissions.md#)|查询账号下的LoRaWAN入网凭证列表。|
|[CreateLoRaNodesTask](cn.zh-CN/云端开发指南/云端API参考/设备管理/CreateLoRaNodesTask.md#)|创建批量注册LoRaWAN设备的任务。|
|[GetLoraNodesTask](cn.zh-CN/云端开发指南/云端API参考/设备管理/GetLoraNodesTask.md#)|查询批量注册LoRaWAN设备任务的状态。|

## 分组管理相关API {#section_atx_lcg_mfb .section}

|API|描述|
|:--|:-|
|[CreateDeviceGroup](cn.zh-CN/云端开发指南/云端API参考/分组管理/CreateDeviceGroup.md#)|创建分组。|
|[DeleteDeviceGroup](cn.zh-CN/云端开发指南/云端API参考/分组管理/DeleteDeviceGroup.md#)|删除分组。|
|[UpdateDeviceGroup](cn.zh-CN/云端开发指南/云端API参考/分组管理/UpdateDeviceGroup.md#)|修改分组信息。|
|[QueryDeviceGroupInfo](cn.zh-CN/云端开发指南/云端API参考/分组管理/QueryDeviceGroupInfo.md#)|查询分组详情。|
|[QueryDeviceGroupList](cn.zh-CN/云端开发指南/云端API参考/分组管理/QueryDeviceGroupList.md#)|分页查询分组列表。|
|[BatchAddDeviceGroupRelations](cn.zh-CN/云端开发指南/云端API参考/分组管理/BatchAddDeviceGroupRelations.md#)|添加设备到分组。|
|[BatchDeleteDeviceGroupRelations](cn.zh-CN/云端开发指南/云端API参考/分组管理/BatchDeleteDeviceGroupRelations.md#)|删除分组中已添加的指定设备。|
|[SetDeviceGroupTags](cn.zh-CN/云端开发指南/云端API参考/分组管理/SetDeviceGroupTags.md#)|添加或更新分组标签。|
|[QueryDeviceGroupTagList](cn.zh-CN/云端开发指南/云端API参考/分组管理/QueryDeviceGroupTagList.md#)|查询分组标签列表。|
|[QueryDeviceGroupByDevice](cn.zh-CN/云端开发指南/云端API参考/分组管理/QueryDeviceGroupByDevice.md#)|查询指定设备所在的分组列表。|
|[QuerySuperDeviceGroup](cn.zh-CN/云端开发指南/云端API参考/分组管理/QuerySuperDeviceGroup.md#)|根据子分组ID查询父分组信息。|
|[QueryDeviceListByDeviceGroup](cn.zh-CN/云端开发指南/云端API参考/分组管理/QueryDeviceListByDeviceGroup.md#)|查询分组中的设备列表。|
|[QueryDeviceGroupByTags](cn.zh-CN/云端开发指南/云端API参考/分组管理/QueryDeviceGroupByTags.md#)|根据标签查询设备分组。|

## 规则引擎相关 API {#section_enr_vbd_xdb .section}

|API|描述|
|:--|:-|
|[ListRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/ListRule.md#)|查询规则列表。|
|[CreateRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/CreateRule.md#)|创建规则。|
|[GetRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/GetRule.md#)|查询规则信息。|
|[UpdateRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/UpdateRule.md#)|修改规则。|
|[DeleteRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/DeleteRule.md#)|删除规则。|
|[ListRuleActions](cn.zh-CN/云端开发指南/云端API参考/规则引擎/ListRuleActions.md#)|查询规则动作列表。|
|[GetRuleAction](cn.zh-CN/云端开发指南/云端API参考/规则引擎/GetRuleAction.md#)|查询规则动作信息。|
|[CreateRuleAction](cn.zh-CN/云端开发指南/云端API参考/规则引擎/CreateRuleAction.md#)|创建规则动作。|
|[UpdateRuleAction](cn.zh-CN/云端开发指南/云端API参考/规则引擎/UpdateRuleAction.md#)|更新规则动作。|
|[DeleteRuleAction](cn.zh-CN/云端开发指南/云端API参考/规则引擎/DeleteRuleAction.md#)|删除规则动作。|
|[StartRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/StartRule.md#)|启动规则。|
|[StopRule](cn.zh-CN/云端开发指南/云端API参考/规则引擎/StopRule.md#)|停止规则。|

## Topic 管理相关 API {#section_bqz_v42_xdb .section}

|API|描述|
|:--|:-|
|[QueryProductTopic](cn.zh-CN/云端开发指南/云端API参考/Topic管理/QueryProductTopic.md#)|查询产品Topic类。|
|[CreateProductTopic](cn.zh-CN/云端开发指南/云端API参考/Topic管理/CreateProductTopic.md#)|创建产品Topic类。|
|[UpdateProductTopic](cn.zh-CN/云端开发指南/云端API参考/Topic管理/UpdateProductTopic.md#)|修改产品Topic类。|
|[DeleteProductTopic](cn.zh-CN/云端开发指南/云端API参考/Topic管理/DeleteProductTopic.md#)|删除产品Topic类。|
|[CreateTopicRouteTable](cn.zh-CN/云端开发指南/云端API参考/Topic管理/CreateTopicRouteTable.md#)|添加Topic路由表。|
|[QueryTopicRouteTable](cn.zh-CN/云端开发指南/云端API参考/Topic管理/QueryTopicRouteTable.md#)|查询Topic路由表。|
|[QueryTopicReverseRouteTable](cn.zh-CN/云端开发指南/云端API参考/Topic管理/QueryTopicReverseRouteTable.md#)|查询Topic反向路由表。|
|[DeleteTopicRouteTable](cn.zh-CN/云端开发指南/云端API参考/Topic管理/DeleteTopicRouteTable.md#)|删除Topic路由表。|

## 消息通信相关 API {#section_oyc_jp2_xdb .section}

|API|描述|
|:--|:-|
|[Pub](cn.zh-CN/云端开发指南/云端API参考/消息通信/Pub.md#)|发布消息到Topic。|
|[RRpc](cn.zh-CN/云端开发指南/云端API参考/消息通信/RRpc.md#)|发消息给设备，并同步返回响应。|
|[PubBroadcast](cn.zh-CN/云端开发指南/云端API参考/消息通信/PubBroadcast.md#)|发布广播消息。|

## 设备影子相关 API {#section_ptd_vp2_xdb .section}

|API|描述|
|:--|:-|
|[GetDeviceShadow](cn.zh-CN/云端开发指南/云端API参考/设备影子/GetDeviceShadow.md#)|查询设备影子。|
|[UpdateDeviceShadow](cn.zh-CN/云端开发指南/云端API参考/设备影子/UpdateDeviceShadow.md#)|更新设备影子。|

## 数据开发API管理 {#section_0yx_8d7_fkm .section}

|API|描述|
|---|--|
|[CreateDataAPIService](cn.zh-CN/云端开发指南/云端API参考/数据开发API管理/CreateDataAPIService.md#)|创建数据算法服务API。|
|[GetDataAPIServiceDetail](cn.zh-CN/云端开发指南/云端API参考/数据开发API管理/GetDataAPIServiceDetail.md#)|获取数据算法服务API详情。|
|[InvokeDataAPIService](cn.zh-CN/云端开发指南/云端API参考/数据开发API管理/InvokeDataAPIService.md#)|调用数据算法服务API，获取SQL查询结果。|

