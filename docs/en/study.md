---
pageClass: routes
---

# Study

## gradCafe

### gradCafe result

<RouteEn author="liecn" example="/gradcafe/result" path="/gradcafe/result" />

### gradCafe result by key words

<RouteEn author="liecn" example="/gradcafe/result/computer" path="/gradcafe/result/:type" :paramsDesc="['Keyword']"/>

## Great Britain China Centre

### Educational Trust

<RouteEn author="HenryQW" example="/gbcc/trust" path="/gbcc/trust" />

## iciba

### Daily English Sentence

<RouteEn author="mashirozx" example="/iciba/7/poster" path="/iciba/:days?/:img_type?" :paramsDesc="['number of items to show (min = 1, max = 7, default = 1)', 'image style']">

| `:img_type` | image style    |
| ----------- | -------------- |
| original    | Original size  |
| medium      | Medium size    |
| thumbnail   | Thumbnail size |
| poster      | Art poster     |

</RouteEn>

## LinkResearch

### theses

<RouteEn author="yech1990" example="/linkresearcher/category=theses&subject=生物" path="/linkresearcher/theses/:param" supportScihub="1" :paramsDesc="['key=value，eg. subject=生物']">

| `:param` | example         | definition                             |
| -------- | --------------- | -------------------------------------- |
| category | category=thesis | **one of**，theses/information/careers |
| subject  | subject=生物    | string / undefined                     |
| columns  | columns=健康    | string / undefined                     |
| columns  | columns=virus   | string / undefined                     |

</RouteEn>

## ORCID

### Works List

<RouteEn author="OrangeEd1t" example="/orcid/0000-0002-4731-9700" path="/orcid/:id" :paramsDesc="['Open Researcher and Contributor ID']"/>

## X-MOL

### News

<RouteEn author="cssxsh" example="/x-mol/news/3" path="/x-mol/news/:tag?" :paramsDesc="['数字编号，可从新闻列表URL得到。为空时从新闻主页获取新闻。']" />

## XMind

### Mindmap Gallery

<RouteEn author="nczitzk" example="/xmind/mindmap" path="/xmind/mindmap/:lang?" :paramsDesc="['language code, all languages by default']">

| English | Español | Deutsch | Français | 中文 | 日本語 |
| ------- | ------- | ------- | -------- | ---- | ------ |
| en      | es      | de      | fr       | zh   | jp     |

</RouteEn>

## ZhiShiFenZi

### News

<RouteEn author="yech1990" example="/zhishifenzi/news/ai" path="/zhishifenzi/news/:type" :paramsDesc="['type，eg. ai']">

| `:type`   | type name |
| --------- | --------- |
| biology   | Biology   |
| medicine  | Medicine  |
| ai        | AI        |
| physics   | physics   |
| chymistry | Chymistry |
| astronomy | Astronomy |
| others    | Others    |

> leave it blank（`/zhishifenzi/news`）to get all

</RouteEn>

### depth

<RouteEn author="yech1990" example="/zhishifenzi/depth" path="/zhishifenzi/depth" />

### innovation

<RouteEn author="yech1990" example="/zhishifenzi/innovation/company" path="/zhishifenzi/innovation/:type" :paramsDesc="['type，eg. company']">

| `:type`       | type name     |
| ------------- | ------------- |
| ~~multiple~~  | ~~Multiple~~  |
| company       | Company       |
| product       | Product       |
| technology    | Technology    |
| ~~character~~ | ~~Character~~ |
| policy        | Policy        |

> leave it blank（`/zhishifenzi/innovation`）to get all

</RouteEn>
