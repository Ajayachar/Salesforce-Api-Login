# Salesforce-Api-Login

Salesforce Api login

URL: https://test.salesforce.com/services/Soap/u/42.0

Request:
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:urn=:urn:partner.soap.sforce.com">
<soapenv:Header>
<urn:CallOpions>
<urn:client>?</urn:client>
<urn:defaultNamespace>?<urn:defaultNamespace>
</urn:CallOpions>
<urn:LoginScopeHeader/>
</soapenv:Header>
<soapenv:Body>
<urn:login>
<urn:username></urn:username>
<urn:password></urn:password>
</urn:login>
</soapenv:Body>
</soapenv:Envelope>

Content type: text/xml
SOAPAction: Login

Composite Delete
DELETE /vXX.X/composite/sobjects?ids=recordId,recordId

DELETE /composite/sobjects?ids=001xx000003DGb2AAG,003xx000004TmiQAAS&allOrNone=false

Query
Content type: application/json;charset=UTF-8
Authorization: Bearer token
