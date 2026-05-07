# Common Claude Code Prompts

  

## 摄入新论文（摘要级）

I added a new paper to raw/papers/.

Read it and follow CLAUDE.md to create a paper page,

update related concept/species/mechanism pages,

add wikilinks, and update index.md.

  

## 精读论文（PDF）

Read raw/papers/论文名.pdf in full detail.

Update (not recreate) wiki/papers/对应页面.md with

deeper analysis including methods, findings, and limitations.

Create any new concept or mechanism pages if needed.

  

## 摄入博客/综述

I added a blog/review to raw/blogs/.

Extract key concepts and mechanisms,

integrate into existing wiki pages.

Do not create a separate page for the blog.

  

## 定期维护（每10篇后运行）

Run a wiki maintenance pass:

1. Find orphan pages with no wikilinks → connect or flag

2. Find concepts mentioned in multiple papers

   but without a concept page → create them

3. Update wiki/synthesis/ with disease association summary

4. Report changes in log.md

  

## 专题查询

Based on the wiki, summarize all evidence linking

[菌种/机制] to [疾病/免疫表型].

Write a summary table to output/topic-名称.md

  

## 生成综述

Based on all papers in wiki/papers/,

write a structured review of how microbial diversity

affects [具体免疫机制].

Save to output/review-名称.md


## Step 7：第一次编译

  

```bash

cd ~/microbiome-kb

claude

```

  

```

Read CLAUDE.md to understand the schema.

Then read all files in raw/ and compile the wiki:

- Create concept pages in wiki/concepts/

- Create paper pages in wiki/papers/

- Create species pages in wiki/species/

- Create mechanism pages in wiki/mechanisms/

- Add wikilinks between all related pages

- Update index.md with summaries