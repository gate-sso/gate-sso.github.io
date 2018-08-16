---
layout: post
title:  "Welcome to Gate!"
date:   2016-07-05 09:00:00 +0000
categories: gate update
---
Every organisation ends up using LDAP as primary single sign on, also they end up using Active Directory. while active directory is great, in this age of web based interfaces, we looked around and found few good solution, but then over weekend thought why not just do it on our own?

While Gate was conceived as providing rest based authentication, I hope it evolves into a better **Identity Management** and authentication and authorisation tool.

Gate allows us to do following things

1. You can easily setup and control VPN access - required at every client, you can use either OpenVPN or IPSec client as per your choice, we provide support for both of them.
2. You can centralise logging to Linux boxes, while you may not need this in current container age, but you can stil might need jump boxes and you can have user based access, with or without sudo
3. You can centralise all web app login to SSO using cas-gate module.

Gate is deployed at [GoJek][gojek] and many more companies.

Check out the [Gate docs][gate-portal] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [GitHub repo][gate-portal]. If you have questions, you can ask them by raising issue on main gate repo, we don't track issues on other repos.

Thanks

Ajey

[gate-portal]: http://github,com/gate-sso/gate
[gojek]: http://go-jek.com
