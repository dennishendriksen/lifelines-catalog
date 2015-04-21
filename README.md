# lifelines-catalog
Proxy classes for the lifelines catalog service

To query the version number, log onto a service that can contact the service and send a [GetVersion](src/test/resources/GetVersionRequest.xml) request:

```
wget https://*servername*/Umcg.Tcc.GenericLayer.CatalogService-1/CatalogService.svc --post-file=GetVersionRequest.xml --header="Content-Type: text/xml; charset=utf-8" --header="SoapAction: http://hl7.umcg.nl/GenericLayerCatalogService/GetVersion"
```

Current version: 1.7.11.0
