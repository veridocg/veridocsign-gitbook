# Create New Envelope API

Creating a document is done by performing a POST request for the `/api/create-envelope` path

{% hint style="info" %}
**AccessToken** parameter in header is the **APIKEY** which is available under application's Integrations page.
{% endhint %}

{% hint style="info" %}
**HashToken** parameter in header is SHA256 Hash of **APIKEY** and **SECRETKEY** combined.
{% endhint %}

{% swagger src="../../.gitbook/assets/swagger.json" path="/api/create-envelope" method="post" %}
[swagger.json](../../.gitbook/assets/swagger.json)
{% endswagger %}
