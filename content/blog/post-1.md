---
title: Setting up a Static Website.
date: 2026-06-19T12:00:00-04:00
---
My experience of hosting a static website Hugo on Github Pages with the Hextra theme.
All the documentation was stellar and I will also link below if you need further instructions.
<!--more-->

&nbsp;

# How do you even begin?

It wasn't too bad in my opinion! I was able to use [Github Pages](https://docs.github.com/en/pages) for mine.\


{{% steps %}}

### Set up Github Repository

#### Step subheading {class="no-step-marker"}

This is the first step.

### Install Hugo & Dependencies

This is the second step.

### Organize Directories

{{< filetree/container >}}
  {{< filetree/folder name="content" >}}
    {{< filetree/file name="_index.md" >}}
    {{< filetree/folder name="docs" state="closed" >}}
      {{< filetree/file name="_index.md" >}}
      {{< filetree/file name="introduction.md" >}}
      {{< filetree/file name="introduction.fr.md" >}}
    {{< /filetree/folder >}}
  {{< /filetree/folder >}}
  {{< filetree/file name="hugo.toml" >}}
{{< /filetree/container >}}

#### Sample Subheading

This will not be counted as a step.

{{% /steps %}}