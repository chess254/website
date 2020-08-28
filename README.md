# Website

Stock2Shop website and documentation built with Hugo.

## Contents

1. [Getting Started](#1-getting-started)
2. [Sections](#2-sections)
    1. [Articles](#21-articles)
    2. [Case Studies](#22-case-studies--success-stories)
    3. [Developers](#23-developers)
    4. [Help Centre](#24-help-centre)
    5. [Integrations](#25-integrations)
    6. [User Docs](#26-user-docs)
3. [Appendix](#3-appendix)
    1. [Front Matter Glossary]((#31-front-matter-glossary))

* * *

## 1. Getting Started

- Install GoHugo
- Clone the project
- Navigate to project and run ```hugo server```
- View in your browser with http://localhost:1313/

* * *
 
## 2. Sections

The site consists of [six main sections](#contents), each with its own distinct purpose. User Docs, Help Centre and
Developers share the same page layout and top menu whereas the rest differ in layout but share the default top menu. 

### 2.1. Articles

Summary to follow

#### Create a new page

1. Run ```hugo new articles/<filename>.md```
2. Open newly created file and update [Front Matter](#31-front-matter-glossary)

#### [Front Matter](#31-front-matter-glossary)
```
---
title:
heading:
titleList:
description:
summary:
lead:
image:
imageAlt:
date:
author:
---
```

### 2.2. Case Studies / Success Stories

Summary to follow

#### Create a new page

1. Run ```hugo new case-studies/<filename>.md```
2. Open newly created file and update [Front Matter](#31-front-matter-glossary)

#### [Front Matter](#31-front-matter-glossary)
```
---
title:
heading:
description:
lead:
summary:
summary2:
image:
imageAlt:
weight:
---
```

### 2.3. Developers

Summary to follow

#### Create a new page

1. Run ```hugo new developers/<filename>.md```
2. Open newly created file and update [Front Matter](#31-front-matter-glossary)

#### [Front Matter](#31-front-matter-glossary)
```
---
title:
description:
---
```

### 2.4. Help Centre

Summary to follow

#### Create a new page

Instructions to follow

#### [Front Matter](#31-front-matter-glossary)
```
---
title:
heading:
description:
image:
---
```

### 2.5. Integrations

This section gets divided into platforms and combinations. Platform pages gets listed on the ```/integrations``` page and need to be marked with ```type:platform``` in the Front Matter.

#### Create a new plaform page

1. Run ```hugo new --kind platforms integrations/platforms/<filename>.md```
2. Open newly created file and update [Front Matter](#31-front-matter-glossary)

#### Create a new combination page

1. Run ```hugo new --kind combinations integrations/combinations/<filename>.md```
2. Open newly created file and update [Front Matter](#31-front-matter-glossary)  

#### [Front Matter](#31-front-matter-glossary)
```
---
title:
titleList:
summary:
type:
image:
imageAlt:
weight:
---
```

### 2.6. User Docs

The User Docs is divided into five subsections

getting-started
configuration
key-concepts
workflows
product-data

#### Create a new page

1. Run ```hugo new --kind subsection user-docs/subsection/<filename>.md```
2. Open newly created file and update [Front Matter](#31-front-matter-glossary)

#### [Front Matter](#31-front-matter-glossary)
```
---
title:
description:
lead:
toc:
menu:
  docside:
    parent:
    name:
---
```
* * *

## 3. Appendix

### 3.1. Front Matter Glossary

**title**: Page meta title for SEO  
**heading**: Page heading when different from title  
**titleList**: Displayed on list page  
**linkTitle**: Hardcoded menu item title  
**description**: Page Meta Description for SEO  
**summary**: Page summary displayed in the articles list page  
**summary2**: Additional summary parameter for different styling eg. bold   
**lead**: Lead paragraph  
**lead2**: Second lead paragraph  
**toc**: Show page table of content  
**image**: Image used from social media sharing and for list page  
**date**: Used for sorting with yyyy-mm-dd format  
**weight**: The default menu item and listing sort order 