---
title: Pitfalls
layout: default
section: "Pitfalls"
filterDocumentation: pitfall
---
# Pitfalls and FAQs

#### Why are my REST calls failing on a self-issued certificate?
This usually occurs if ServiceNow is not accepting self-issued certificates. In order to allow self-issued certs, navigate to `System Properties > Security ` and scroll down to the Miscellaneous section. Check the **By default, ServiceNow trusts a certificate's Certificate Authority(CA)...**.
![](/assets/img/screenshots/CA_Screenshot.png)

#### Where can I find logs in ServiceNow?
