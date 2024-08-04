---
pageClass: routes
---

# 蓝奏云文件直链 <徽章文本="正常" 类型="tip"/>

##接口地址 https://wwr.lanpv.com/hyi

``` 
https://tenapi.cn/v2/lanzou
```

## 请求示例

```猛敲
curl https://tenapi.cn/v2/lanzou -X POST -d 'url=https://xiaodao.lanzoux.com/iTusf0k5p9pa'
```

## 请求参数

| 参数名 | 类型 | 必填 | 说明 |
| --- | --- | --- | --- |
|统一资源定位系统|线| 是 | 蓝奏云分享链接 |

## 返回数据

```json
{
“日期”：“真实”，
“msg”：“获取成功”，
“数据”：{
“name”：“爱奇艺_v9.12.171.6597_（64）com，
“time”：“12小时前”，
“作者”：“小刀娱乐网 x6g.com”，
“尺寸”：“58.2米”，
"ext": ".exe ",
“网址”：“https://I01.lanzoug.com/0105230096052130bb/2023/01/05/4d9F2679fb059aca678eedc64303aaf3.exe?st=wYTOpC_eN3INt-IMxPZAXg&E=1597909974&b=VFELblU3A1VWa1dkCzxpwAECtwEAvq_bCxqnzj9VTI_C&fi=96052130&pid=13-255-955&up=2&mp=1&co=1”
  }
}
```

## 返回参数

| 参数名 | 类型 | 说明 |
| --- | --- | --- |
| name | string | 文件名 |
| time | string | 上传时间 |
| author | string | 作者 |
| size | string | 文件大小 |
| ext | string | 文件后缀 |
| url | string | 文件直链 |

<ads></ads>
