---
title: "{{ replace .Name "-" " " | title }}"
slug: {{ .Name | urlize }}
description: 
keywords: 
# meta keywords for SEO 

date: {{ dateFormat "Mon, 02 Jan 2006 15:04:05 PST" .Date }}
publishDate: {{ dateFormat "Mon, 02 Jan 2006 15:04:05 PST" .Date }}
lastmod: {{ dateFormat "Mon, 02 Jan 2006 15:04:05 MST" .Date }}
draft: true
# change to "false" to publish 

---

<!-- link -->
{{< link
    href="" >}}
    Link Text
{{< /link >}}

<br> 

<!-- link target-blank -->
{{< target-blank
    href="" >}}
    Link Text
{{< /target-blank >}}

<br>

<!-- img/figure -->
{{< img 
    src="" 
    type="" 
    alt="" 
    caption="" >}}