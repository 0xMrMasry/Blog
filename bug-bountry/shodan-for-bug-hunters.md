---
description: A goldmine to discover vulnerable devices and services.
---

# Shodan For Bug hunters

## What is Shodan?

Shodan is often called the "search engine for the Internet of Things (IoT)". Unlike traditional search engines that index web pages, Shodan indexes devices connected to the internet, such as webcams, routers, servers, and more. For bug bounty hunters.

## Why is Shodan Important for Bug Bounty Hunters?

1. **Discover Vulnerable Devices:** Shodan can help identify devices running outdated or vulnerable software.
2. **Identify Misconfigurations:** Devices that are misconfigured and exposed to the internet can be easily spotted.
3. **Gather Intelligence:** Shodan provides a wealth of information about a target, including open ports, services running, banners, and more.



## Important Shodan Dorks with Explanations:

* **`org:"http://target.com"`**: Explore a specific organization's assets.
* **`http.status:"<status_code>"`**: Find web pages with a specific HTTP status code.
* **`product:"<Product_Name>"`**: Target specific software or product names.
* **`port:<Port_Number> "Service_Message"`**: Search for services by port number and service message.
* **`port:<Port_Number> "Service_Name"`**: Filter by port and service name.
* **`http.component:"<Component_Name>"`**: Discover specific web components.
* **`http.component_category:"<Component_Category>"`**: Focus on a specific category of web components.
* **`http.waf:"<firewall_name>"`**: Identify websites protected by a specific firewall.
* **`http.html:"<Name>"`**: Search for HTML content with a specific name.
* **`http.title:"<Title_Name>"`**: Hunt for web pages with a specific title.
* **`ssl.alpn:"<Protocol>"`**: Target servers supporting a specific ALPN protocol.
* **`http.favicon.hash:"<Favicon_Hash>"`**: Find websites based on favicon hashes.
* **`net:"<Net_Range>"`**: Search within a specific IP range.
* **`http://ssl.cert.subject.cn:"http://Domain.com"`**: Locate SSL certificates for a given domain.
* **`asn:"<ASnumber>"`**: Explore assets based on Autonomous System Numbers.
* **`hostname:"<hostname>"`**: Discover assets based on specific hostnames.
* **`ip:"<IP_Address>"`**: Target assets with a specific IP address.
* **`all:"<Keyword>"`**: Search for assets based on a keyword.
* **`"Set-Cookie: phpMyAdmin"`**: Identify systems using phpMyAdmin.
* **`"Set-Cookie: lang="`**: Hunt for systems with a specific language cookie.
* **`"Set-Cookie: PHPSESSID"`**: Locate sessions using PHPSESSID.
* **`"Set-Cookie: webvpn"`**: Find systems using web VPN cookies.
* **`"Set-Cookie:webvpnlogin=1"`**: Discover systems with specific web VPN login cookies.
* **`"Set-Cookie:webvpnLang=en"`**: Target systems with web VPN language cookies.
* **`"Set-Cookie: mongo-express="`**: Identify systems with mongo-express cookies.
* **`"Set-Cookie: user_id="`**: Hunt for systems with user\_id cookies.
* **`"Set-Cookie: phpMyAdmin="`**: Uncover systems using phpMyAdmin cookies.
* **`"Set-Cookie: _gitlab_session"`**: Locate GitLab session cookies.
* **`"X-elastic-product: Elasticsearch"`**: Discover systems using Elasticsearch.
* **`"x-drupal-cache"`**: Identify systems with Drupal cache headers.
* **`"access-control-allow-origin"`**: Hunt for permissive CORS configurations.
* **`"WWW-Authenticate"`**: Locate systems requiring authentication.
* **`"X-Magento-Cache-Debug"`**: Discover Magento cache debugging information.
* **`"kbn-name: kibana"`**: Identify systems using Kibana.

***

:warning:**Remember, while Shodan is a powerful tool, it's essential to use it responsibly. Always ensure you have permission before probing or accessing any device or service you find.**
