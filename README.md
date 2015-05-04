# WHC_XMLParser
自动解析xml为字典对象
####Use Example
```objective-c
    NSString  * xml = @"<?xml version=\"1.0\" encoding=\"utf-8\"?>\
    <ebMobileStartupInqRq xmlns=\"http://ns.chinatrust.com.tw/XSD/CTCB/ESB/Message/BSMF/ebMobileStartupInqRq/01\">\
        <REQHDR>\
            <TrnNum>INHB2015042900000001</TrnNum>\
            <TrnCode>1957747793</TrnCode>\
        </REQHDR>\
        <REQBDY>\
            <OS>iPhone</OS>\
            <App>CC</App>\
            <IconVersion></IconVersion>\
        </REQBDY>\
    </ebMobileStartupInqRq>";
    
    NSDictionary * dict = [WHC_XMLParser dictionaryForXMLString:xml];

```
