# 创建LoRa设备 {#concept_zy1_z2d_zgb .concept}

物联网平台支持创建LoRa产品和设备。根据[创建产品](cn.zh-CN/用户指南/产品与设备/创建产品.md#)创建LoRa产品后，可以根据本文操作，创建LoRa设备。您可以单个创建LoRa设备，也可以批量操作。

## 单个创建 {#section_nw1_cfd_zgb .section}

1.  登录[物联网平台控制台](http://iot.console.aliyun.com/)。
2.  左侧导航栏选择**设备管理** \> **设备**，单击**添加设备**。
3.  选择已创建的连网方式为LoRaWAN的产品。新创建的设备将继承该产品定义好的功能和特性。
4.  填入DevEUI和PIN Code。

    **说明：** 

    -   DevEUI 是LoRa设备的唯一标识符，采用LoRaWAN协议标准规范，不可为空。请确保DevEUI产品下唯一，且已烧录到设备中。
    -   DevEUI和PIN Code一般印刷在设备外显标签上。
    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/134336/156376637939864_zh-CN.png)

5.  单击**确认**。完成设备创建。

    设备创建完成后，将自动弹出**查看设备证书**弹框。您可以查看、复制LoRa设备的证书信息，包括JoinEUI和DevEUI。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/134336/156376638039872_zh-CN.png)


## 批量创建 {#section_kp4_cfd_zgb .section}

1.  登录[物联网平台控制台](http://iot.console.aliyun.com/)。
2.  左侧导航栏选择**设备管理** \> **设备**，单击**批量添加**。
3.  选择已创建的连网方式为LoRaWAN的产品。新创建的设备将继承该产品定义好的功能和特性。
4.  单击**下载.csv模板**下载表格模板，在模板中填写DevEUI和PIN Code，然后将填好的表格上传至控制台。

    **说明：** DevEUI 是LoRa设备的唯一标识符，采用LoRaWAN协议标准规范，不可为空。请确保DevEUI产品下唯一，且已烧录到设备中。

5.  单击**确认**。完成设备创建。

## 下一步 {#section_fpg_dfd_zgb .section}

您可以参考[物联网络管理平台文档](https://help.aliyun.com/document_detail/96549.html)搭建物联网所需的网络服务和开发设备端（即网关开发和节点开发）。

**说明：** 在物联网平台创建LoRa设备后，您无需再在物联网络管理平台录入节点（即设备）信息和配置数据流转。

