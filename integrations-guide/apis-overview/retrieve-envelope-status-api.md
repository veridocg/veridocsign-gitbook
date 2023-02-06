# Retrieve Envelope Status API

Retrieving a document is done by performing a GET request for the `/api/get-status` path&#x20;

{% hint style="info" %}
**AccessToken** parameter in header is the **APIKEY** which is available under application's Integrations page.
{% endhint %}

{% hint style="info" %}
**HashToken** parameter in header is SHA256 Hash of **APIKEY** and **SECRETKEY** combined.
{% endhint %}



{% swagger src="../../.gitbook/assets/swagger (1).json" path="/api/get-status" method="post" %}
[swagger (1).json](<../../.gitbook/assets/swagger (1).json>)
{% endswagger %}

