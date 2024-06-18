---
title: Author experience
description: How to author content with CMS
date: 2024-06-18T14:08:36
image: /images/screenshot-2024-06-18-at-14.10.57.png
authors:
  - Wyona
tags:
  - content
categories:
  - cms
---
When the website is up and running, authors can add and edit content using the CMS user interface.

CMS allows managing only content that has been configured in the collections for modifications. It depends on the template what things on the website are read from the CMS content and which are hard wired. For example, in this template it is not possible to modify the layout or css styles, but they could be configurable.

By default, the editor and preview of an item looks like in the image above. However, it is possible to configure the preview to match the website look as described in [StaticCMS documentation for custom preview](https://www.staticcms.org/docs/custom-previews). Different preview template can be configured for each type of items managed by CMS.

The modifications can be published immediately, or CMS can be configured to use Editorial Workflow, like in this website. With Editorial Workflow, the changes are saved as drafts, that are stored in git in a separate branch, and collaborators can review them before publishing.

After the changes have been published, it takes some time for the new content to deploy on the website. The deploy logs can be made public, so authors can view the deploy status to see when the changes are live. This websites deploy logs can be found at [https://app.netlify.com/sites/static-site-example3/deploys](https://app.netlify.com/sites/static-site-example3/deploys).
