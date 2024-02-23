+++
title = "Hello World"
summary = "国际惯例 历史悠久 起源"
date = 2024-01-31T22:19:24+08:00
+++

## Hello, World!  
> 按照国际惯例的 "Hello, World!"，作为历史最悠久的文章，~~却并没有什么实质内容。~~

<br />

### 1. Installing/Updating PaperMod  
**UPDATE**:  
1. Sync fork
2. Inside the folder of your Hugo site `MyFreshWebsite`, run:  
```bash
git submodule update --remote --merge
```  
### 2. UPDATE github.com/hugomods/pwa  
> https://gohugo.io/hugo-modules/use-modules/#update-one-module  
```bash
hugo mod get -u github.com/hugomods/pwa
```  
### 3. "You can use it by creating archetypes/post.md"
https://github.com/adityatelange/hugo-PaperMod/wiki/Installation#sample-pagemd
```bash
hugo new --kind post <name>
```