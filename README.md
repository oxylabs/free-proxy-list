
# Free Proxy List


[![Free Proxies](https://raw.githubusercontent.com/oxylabs/free-proxies/refs/heads/main/Free%20Proxies-1090x275px-new.png)](https://oxylabs.io/products/free-proxies?utm_source=877&utm_medium=affiliate&groupid=877&transaction_id=102c8d36f7f0d0e5797b8f26152160)


[![](https://dcbadge.vercel.app/api/server/eWsVUJrnG5)](https://discord.gg/GbxmdGhZjq)

Claim your access to [free US proxy servers](https://oxylabs.io/products/free-proxies) from Oxylabs. Sign up on the [dashboard](https://dashboard.oxylabs.io/) to unlock premium features including:

- [x] Free HTTP/HTTPS/SOCKS5 proxies
- [X] 20 concurrent sessions
- [X] 5GB of traffic per month across 5 US IPs
- [X] Exceptional performance & speed

## 🛠️ How to get free proxy server IPs

1. Register an account on the [Oxylabs dashboard](https://dashboard.oxylabs.io/).
2. Head to the [Datacenter Proxies page](https://dashboard.oxylabs.io/en/overview/datacenter-proxies) and create a proxy user.
3. Test the connection using a proxy manager or send a web request via cURL, Python, or your preferred setup.

![](images/free_proxies.png)


## 🧩 Easy proxy management on Chrome

[Oxy® Proxy Manager](https://oxylabs.io/products/chrome-proxy-extension) is a **free Chrome extension** enabling you to easily switch between multiple IP addresses during browsing sessions. See the [integration steps](https://developers.oxylabs.io/proxies/integration-guides/shared-datacenter-proxies-guides/oxy-proxy-extension-for-chrome) to find out more.

![](images/oxy_proxy.png)

## 🔗 Simple integration

Oxylabs' free premium proxies easily integrate with various third-party tools and enhance their functionality. Explore detailed [integration guides](https://oxylabs.io/resources/integrations) and  [documentation](https://developers.oxylabs.io/proxies/datacenter-proxies/free-datacenter-ips).

[![cURL](https://img.shields.io/badge/cURL-073551?style=for-the-badge&logo=curl&logoColor=white)](https://curl.se) [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net) [![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev) [![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com) [![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://dotnet.microsoft.com/languages/csharp)

### Python integration example

Install the [requests](https://requests.readthedocs.io/en/latest/) library using `pip` via your terminal:

```bash
pip install requests
```

Then, create a new Python file and utilize this code sample: 

```python
import requests

# Replace with your proxy user credentials.
username = 'USERNAME'
password = 'PASSWORD'

# Port `8000` rotates IPs from your proxy list.
address = 'dc.oxylabs.io:8000'

proxies = {
   'https': f'https://user-{username}:{password}@{address}'
}

response = requests.get('https://ip.oxylabs.io/location', proxies=proxies)

print(response.text)
```

## Contacts
Email - hello@oxylabs.io
<br><a href="https://oxylabs.drift.click/oxybot">Live chat</a>
