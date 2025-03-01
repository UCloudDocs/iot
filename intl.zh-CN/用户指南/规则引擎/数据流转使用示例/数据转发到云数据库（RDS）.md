# 数据转发到云数据库（RDS） {#concept_lc3_5pt_tdb .concept}

您可以设置规则引擎数据流转，将处理后的数据转发到云数据库（以下简称RDS）的VPC实例中。

## 使用须知 {#section_y5v_fv3_wdb .section}

-   只支持同地域转发，不支持跨地域转发。比如，华东2节点的平台数据只能转发到华东2的RDS数据表中。
-   只支持转发到专有网络RDS实例。
-   支持MySQL实例和SQL Server实例。

    **说明：** 目前，不支持MySQL 8.0。

-   支持普通数据库和高权限数据库的转发。
-   不支持二进制格式数据转发至RDS。

## 准备工作 {#section_tyl_hv3_wdb .section}

-   请参见[设置数据流转规则](intl.zh-CN/用户指南/规则引擎/数据流转/设置数据流转规则.md#)创建规则和编写用于处理数据的SQL。
-   购买与您的物联网服务地域相同的RDS实例，并创建数据库和数据表。

## 操作步骤 {#section_yfn_vgh_ygb .section}

1.  单击**数据转发**一栏的**添加操作**，出现添加操作页面。选择**存储到云数据库\(RDS\)中**。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/7547/15597531982856_zh-CN.png)

2.  按照界面提示，设置参数。

    |参数|描述|
    |:-|:-|
    |选择操作|选择存储到云数据库\(RDS\)中。|
    |RDS实例|需选择与您的物联网服务地域相同的专有网络RDS实例。|
    |数据库|输入数据库名。 **说明：** 如果是高权限数据库，需要您手动输入数据库名称。

 |
    |账号|输入RDS实例的用户账号。此账号应具有该数据库的读写权限，否则规则引擎无法将数据写入RDS。 **说明：** 规则引擎获得账号后，仅将规则匹配的数据写进数据库中，不会做其他操作。

 |
    |密码|输入登录RDS实例的密码。|
    |表名|输入数据库中已建立的数据表名。规则引擎将把数据写入这张表上。|
    |键|输入RDS数据表的一个字段。规则引擎将把数据存入该字段中。|
    |值|输入您在数据处理SQL中指定的Topic中的消息的一个字段，作为输入数据表字段（键）的值。 **说明：** 

    -   值与键的数据类型需保持一致，否则无法存储成功。
    -   可输入一个变量，如`${deviceName}`。
 |
    |角色|授权物联网平台向RDS数据表写入数据的角色。 若您还没有创建相关角色，请单击**创建RAM角色**进入访问控制（RAM）控制台创建。

 |

3.  在数据流转列表中，单击该规则对应的**启动**按钮启动规则。
4.  配置完成后，规则引擎为了连接RDS，会在RDS的白名单中添加下列IP。若这些IP未出现，请手动添加。

    -   华东2：100.104.123.0/24
    -   亚太东南1（新加坡\)：100.104.106.0/24
    -   美国（硅谷）：100.104.8.0/24
    -   美国（弗吉尼亚）：100.104.133.64/26
    -   德国（法兰克福）：100.104.160.192/26
    -   日本（东京）：100.104.160.192/26
    在RDS控制台数据安全性页，设置和查看白名单。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/7547/15597531983010_zh-CN.png)


