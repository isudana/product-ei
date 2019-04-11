### 1.6.3-Replace-a-value-of-the-incoming-message-using-enrich-mediator


| Test Case ID| Test Case| Test Case Description| Status|
| ----------| --------| ----------| ------|
| 1.6.3.1 | Replacing body of payload using a payload stored in a property| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload using a payload stored in a property. </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.2 | Replacing target message defined through xpath by source body| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined through xpath by source body. </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.3 | Replacing target message defined through xpath by source property| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined through xpath by source property. </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.4 | Replacing target message defined through xpath by source inline content| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined through xpath by source inline content. </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.5 | Replacing body of payload using source defined inline through governance registry| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload using source defined inline through governance registry. </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.6 | Replacing body of payload using source defined inline through configuration registry| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined through xpath by source inline content loaded from governance registry </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.7 | Replacing target message defined through xpath by source inline content loaded from governance registry| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined through xpath by source inline content loaded from governance registry </br> **Then**:Payload should be enriched.| Automated|
| 1.6.3.8 | Replacing target message defined through xpath by source inline content loaded from configuration registry| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined through through xpath by source inline content loaded from configuration registry. </br> **Then**:Payload should be enriched.| Not Automated|
| 1.6.3.9 | Replacing a payload using content defined as local entry using inline| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload using content defined as local entry using inline. </br> **Then**:Payload should be enriched.| Not Automated|
| 1.6.3.10| Replacing target message by source defined through custom get property| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload by source defined through custom get property. </br> **Then**:Payload should be enriched.| Not Automated|
| 1.6.3.11| Replacing body of payload using source defined inline through local entry| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich a payload defined inline through local entry. </br> **Then**:Payload should be enriched.| Not Automated|
| 1.6.3.12| Source envelope replacing target message property| **Given**:Test environment is set properly. </br> **When**:A request sends to wso2 EI to enrich an envelope by target message property </br> **Then**:Payload should be enriched.| Not Automated|