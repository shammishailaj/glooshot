
---
title: "solo-kit.proto"
weight: 5
---

<!-- Code generated by solo-kit. DO NOT EDIT. -->


### Package: `core.solo.io` 
#### Types:


- [Resource](#resource)
  



##### Source File: [github.com/solo-io/solo-kit/api/v1/solo-kit.proto](https://github.com/solo-io/solo-kit/blob/master/api/v1/solo-kit.proto)





---
### Resource



```yaml
"shortName": string
"pluralName": string
"clusterScoped": bool
"skipDocsGen": bool

```

| Field | Type | Description | Default |
| ----- | ---- | ----------- |----------- | 
| `shortName` | `string` | becomes the kubernetes short name for the generated crd |  |
| `pluralName` | `string` | becomes the kubernetes plural name for the generated crd |  |
| `clusterScoped` | `bool` | the resource lives at the cluster level, namespace is ignored by the server |  |
| `skipDocsGen` | `bool` | indicates whether documentation generation has to be skipped for the given resource, defaults to false |  |





<!-- Start of HubSpot Embed Code -->
<script type="text/javascript" id="hs-script-loader" async defer src="//js.hs-scripts.com/5130874.js"></script>
<!-- End of HubSpot Embed Code -->
