---
title: Component Content Management Systems
author: Heinz Wittenbrink
date: 2021-11-09
---

# Questions

## Component Content Management/Content Management
1. What are the relationships between component content management and content management in general?

## Content Management/Content Strategy
2. Is there a mutual dependency between content management and content strategy?

## Component Content Management/Web Content Management
3. Are component content management and web content management completely compatible?

## Component Content Management/Knowledge Management
4. What are the relationships between component content management and knowledge management/knowledge graphs?

## Component Content Management/Enterprise Content
5. Is the goal of an encompassing *enterprise content strategy* an illusion?


# CMS Types

## File management

- Examples: Windows Explorer, Mac Finder

- [What is a File Management System? - Definition from Techopedia](https://www.techopedia.com/definition/1832/file-management-system "What is a File Management System? - Definition from Techopedia")

## Document Management

> A document management system aims to digitally organize all files and documents within an organization so that they can be easily accessible and placed in a single central location. This way, information is easy to find, and the time saved can be channelled towards more essential tasks required for company operation.

[Benefits of a Document Management System and 9 Things to Look For | Ash Conversions International](https://www.ashconversions.com/blog/document-management/benefits-document-management-system-9-things-look/ "Benefits of a Document Management System and 9 Things to Look For | Ash Conversions International")

- Examples: [15 Best Document Management Systems of 2020 - Financesonline.com](https://financesonline.com/top-15-document-management-systems/ "15 Best Document Management Systems of 2020 - Financesonline.com")

## Digital Asset management

> Digital Asset Management (DAM) manages information, systems and processes that enable the management of assets from ideation to creation, curation, analysis and archiving.

[Home - DAM Maturity Model](http://www.dammaturitymodel.org/ "Home - DAM Maturity Model")

## Web CMs

- File based systems: [List of the Best Flat File CMS](https://www.cmscritic.com/flat-file-cms/ "List of the Best Flat File CMS")
- Templates
- Databases
- Content APIs and headless systems

## Component Content Management System

https://www.empolis.com/blog/digitale-transformation/component-content-management/

> So here is our proposed definition. I’m sure it will elicit lots of comments and maybe a few “flames”, but it provides a starting point we can work with.  

> Component Content Management systems manage content at a granular level (component) of content rather than at the document level. Each component represents a single topic, concept or asset (e.g., image, table). Components are assembled into multiple content assemblies (content types) and can be viewed as components or as traditional “documents”. Each component has its own lifecycle (owner, version, approval, use) and can be tracked individually or as part of an assembly. CCM is typically used for multichannel customer-facing content (marketing, usage, learning, support). CCM can be a separate system or be a functionality of another content management type (e.g., ECM or WCM).

[Forrester Wave vs. Component Content Management](https://web.archive.org/web/20070205021018/http://www.cmpros.org/resources/newsletter/cm-pros-newsletter-2007-01/forrester-wave-vs.-component-content-management "CMPros")

# Basics

## Definition

> A centralized system that helps organizations capture, manage, store, preserve, and deliver topic-based content (components), whether the content is proprietary or follows a standard architecture, like DITA.

[Term of the Week: Component Content Management System – The Language of Technical Communication](https://tlotc.xmlpress.net/2016/12/20/term-of-the-week-component-content-management-system/ "Term of the Week: Component Content Management System – The Language of Technical Communication")

> The specific CMS systems used in technical documentation are also referred to as component content management system (CCMS).

[Component Content Management Systems](https://www.people-text.de/en/competences-content-management-systems.html "Component Content Management Systems")

## Affordances

- Centralized Control
- Content and Media Enrichment
– Referential Integrity
- Cross-functional Collaboration
- Process Management
- Process Integration

::: notes

Centralized Control: concentrates knowledge and enables sharing, swapping, reusing, and reviewing content. It can answer content audit questions such as, who did what, when and why did they do it, on what content did they work, and where was that content delivered.
Content and Media Enrichment: helps create metadata that facilitate discovery by both CCMS users and information product users.
Referential Integrity: manages and maintains the links between objects – particularly important when the content is reused in multiple documents, versions, and formats.
Cross-functional Collaboration: integrates and adapts to the organization’s roles and access needs, facilitating experts’ collaboration in adding and reviewing content.
Process Management: adapts and enforces the organization’s business rules and processes, including planning, translation monitoring, final processing, and output delivery.
Process Integration:  interfaces with delivery platforms, such as dynamic delivery systems, learning management systems, and other storage sources.

[Term of the Week: Component Content Management System – The Language of Technical Communication](https://tlotc.xmlpress.net/2016/12/20/term-of-the-week-component-content-management-system/ "Term of the Week: Component Content Management System – The Language of Technical Communication")

:::

# "Component Content Management in Depth"

## Trippe 2005

## Repository Functions

- Roles-based access control for check-in, check-out
- Management of both content and metadata
- Reuse at any level
- Enable components to be freely moved around, with link integrity guaranteed

## Linking, Link Integrity and Management

- Components managed through all kinds of links, sources are managed,
multiple links and link types are supported. Standards like XInclude and XLink are supported.
- Automated consistency checks

## Content and Document History, Versioning

- All content components versioned and complete history tracked
- Any individual component or collection of components (document) at any
version can be reproduced

## Workflow

- Task Management
- Role Based

## Content Lifecycle

- Central storage for schemas
- “Impact analysis” for possible changes to schemas, content
- Instance modifications using style sheets
- Metadata can be handled, filtered at the same time
- Content can be enhanced, refactored over time within the repository

## Conditional Publishing

- Publish variant versions of content based on variables, schema constructs, abstract links
- Examples: publish based on dates, variables in the text (product name and numbers), varying schemas, varying stylesheets, varying based on the toplevel component
- Images stored separately, and can be generated or manipulated at publish time

## General Requirements

- Scalability
- High performance
- Flexible and comprehensive security
- Maintainability
- Low total cost of ownership

# CCMS Use cases

## Reusability

## Multichannel

## Translations

## Context sensitivity

> Wie kann man möglichst viel Inhalt wiederverwenden, ohne ihn zu kopieren?
Bedienung unterschiedlicher Publikationsformen, ohne separate Dokumente vorhalten zu müssen
Kostenreduzierung bei Übersetzungen
Kontextabhängige Verfügbarmachung der Inhalte

# CMS Features

## Collaboration

## Review

## Approval

## Translation

## Search

## Reports

## Editing

## Publishing

## Integration

## Internationalization

- http://www.econtentmag.com/Articles/Resources/Defining-EContent/What-is-Content-Globalization-123875.htm

# History of CCMSs

## Origins

> Bill Trippe first coined the term in a Gilbane Group Content Management Technology Whitepaper sponsored by xHive called Component Content Management in Practice. Interestingly, while he describes it and compares it to other types of content management, he never really provides a simple definition for it.

[Forrester Wave vs. Component Content Management](https://web.archive.org/web/20070205021018/http://www.cmpros.org/resources/newsletter/cm-pros-newsletter-2007-01/forrester-wave-vs.-component-content-management "CMPros")

## Before DITA

> In addition to expanding the types of content that are now managed, ECM has also ushered ina recognition that content management is a peer application to other kinds of enterprise applications, such as enterprise resource planning (ERP) and customer relationship management (CRM).  (Trippe 2005)

> One complex business process involves technical documentation, catalogs, and other kinds of content used in product support, where reusable content “components” can be managed in a way that complex content products can be assembled, reassembled, and published.  This kind of application is especially critical in markets such as manufacturing, electronics, aviation and other transportation, and the military. (Trippe 2005)

::: notes

> The capital investment made by the aircraft buyers is fully realized when the aircraft is properly maintained by following a comprehensive, long-term—and content-intensive—maintenance program. (Trippe 2005, p.4)

> Many enterprises have the volume of content that offers re-purposing opportunities. The practice of producing multiple media formats—print, online, CD-ROM, HTML—from a single-source is well-established, but enterprises face even greater volume of content across more and more versions, channels, markets, and languages. As the enterprise’s requirements for multi-channel publishing expands, the enterprise must invest in platform architectures that can efficiently automate these processes.  (Trippe 2005, p.5)

> Single-source publishing involves repurposing content into other formats, but when a content component is used in www.gilbane.com5
Component Content Management in Practice multiple content types, it is called reuse. (Trippe, p. 5f)

> Identifying the redundant pieces that make up the content can be thought of as one means of identifying content “components,” and is central to the reuse strategy.  (Trippe, p. 6)

> The key to the successful re-use of content is to manage it at a granular level. These grains of content—components—can be shared, reviewed, updated, or combined and compiled intodifferent document aggregations and collections. Each component can be separately edited and re-used, and workflow processes enforced. Content components can have their own lifecycles and properties—version, owner, and approval—that support fine-grained reuse andthe ability to track such usage. (Trippe, p. 6)

> In addition to providing a format-neutral data structure, XML encoding of the content also cansupport reuse by providing a ready mechanism for dividing the content into logical elements or components.  For example, a repair manual for a transmission could be divided into the various tasks that can be performed, a parts catalog could be divided by part number, partdescription, and so on.  Analysts and consultants have used terms like “minimum reusable unit” or MRU to describe the level at which content is logically stored for maximum efficiency.  (Trippe, p. 7)

:::

## After DITA

2005: [Gilbane Group Content Management White Papers](https://web.archive.org/web/20070210052129/http://gilbane.com/whitepapers.pl?view=14 "Gilbane Group Content Management White Papers")

2006: IXIASOFT DITA CMS launched (initial version of IXIASOFT CCMS), the first component content management system designed specifically for DITA XML-based content

2007: [Forrester Wave vs. Component Content Management](https://web.archive.org/web/20070205021018/http://www.cmpros.org/resources/newsletter/cm-pros-newsletter-2007-01/forrester-wave-vs.-component-content-management "CMPros")

2008: [Component Content Management: Overlooked By Analysts; Required By Technical Publications Departments](https://web.archive.org/web/20080724002927/http://www.dclab.com/component_content_management.asp "Component Content Management: Overlooked By Analysts; Required By Technical Publications Departments")

<https://www.jetro.go.jp/ext_images/canada/pdf/ixiasoft.pdf>


# Vendors

## Aktuelle Zusammenstellung

[Best Component Content Management Systems in 2021 | G2](https://www.g2.com/categories/component-content-management-systems "Best Component Content Management Systems in 2021 | G2")

## Adobe XML Documentation Add-on

- [Adobe Component Content Management System - Features](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html# "Adobe Component Content Management System - Features")

---

<iframe width="560" height="315" src="https://www.youtube.com/embed/fPl62WRVqDg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

![](https://blogsimages.adobe.com/techcomm/files/2016/07/XML-Documentation-Add-On-for-Adobe-Experience-Manager_Overview-Graphic.jpg)


---

XML Documentation for Adobe Experience Manager 3.0

<https://helpx.adobe.com/content/dam/help/en/xml-documentation-solution/3-5/XML-Documentation-for-Adobe-Experience-Manager_6-5_6-4_6-3_User-Guide_EN.pdf>

---

Publishing

[Publishing DITA-Based Technical Content to Adobe Experience Manager Sites | Bounteous](https://www.bounteous.com/insights/2020/06/04/publishing-dita-based-content-aem-sites/ "Publishing DITA-Based Technical Content to Adobe Experience Manager Sites | Bounteous")


::: notes

This blog post shows quite well, how the XML Documentation is configured for publishing. It is possible and normally necessary to customize it for the specific DITA topics used by an organization. In a second step the output is connected to specific elements of the Adobe Experience Manager, and these element are linked to specific templates.


:::


## IxiaSOFT

- [#1 DITA CCMS - Enterprise-Class Content Management - IXIASOFT](https://www.ixiasoft.com/ "#1 DITA CCMS - Enterprise-Class Content Management - IXIASOFT")

---

More:

[IXIASOFT (@IXIASOFT) / Twitter](https://twitter.com/ixiasoft?lang=de "IXIASOFT (@IXIASOFT) / Twitter")

## Author-It

- [Author-It Software Co.](https://www.author-it.com/ "Author-It Software Co.") (Life Sciences)
- Nicht DITA-/XML-basiert

## Paligo

- [Features | Paligo - The Next Generation of Technical Documentation](https://paligo.net/product "Features | Paligo - The Next Generation of Technical Documentation")

---


[Case studies - Paligo](https://paligo.net/case-studies/ "Case studies - Paligo")

--


Docbook

---

Zendesk Integration

[Paligo + Zendesk: Publishing Technical Documentation to Your Help Desk Just Got Even Better](https://paligo.net/blog/news-and-updates/paligo-zendesk-publishing-technical-documentation-to-your-help-desk-just-got-even-better/ "Paligo + Zendesk: Publishing Technical Documentation to Your Help Desk Just Got Even Better")


## easyDITA

- [easyDITA](https://easydita.com/ "Publishing Documentation Just Got Faster | easyDITA")

## Astoria

-  [Astoria Software | XML Content Management](https://www.astoriasoftware.com/ "Astoria Software | XML Content Management")

## Dakota Systems

-  [Component Content Management | Dakota Systems](https://www.daksys.com/component-content-management/ "Component Content Management | Dakota Systems")

## Documoto

-  [Creat, Share, & Sell Equipment Parts Easily! | Documoto](https://documoto.com/ "Creat, Share, & Sell Equipment Parts Easily! | Documoto")
