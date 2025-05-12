---
layout: post
title: Thesis Research Seminars
subtitle: Scheduled to be updated once a month
thumbnail-img: /assets/img/cover_seminar.jpg
share-img: /assets/img/cover_seminar.jpg
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Research Seminar, Industrial Safety Management, Computer Vision, Data Augmentation, LLM]
comments: true
mathjax: true
author: Geunho Lee
---

{: .box-note}
**Note:** This repository is a space for the archive of paper seminars held regularly once a month. Each seminar is approximately 30 minutes long and introduces the main research content and provides related Q&A.

**Here is some bold text**

# Thesis Research Seminars List

| Date |Title & Topic | Link |
| :------ |:------|:------|
| 2023-12-15 | Jinwoo Park, Jihun Bae, Jongeon Im, Byeongchan Kim, Jongpil Jeong, "LED-Display Defect Detection Based on YOLOv5 and Transformer",  IEEE Access,  18 October 2023 | [Link](https://ieeexplore.ieee.org/document/10287328/) |
| 2025-02-21 | Bowen Wen, Wei Yang, Jan Kautz, Stan Birchfield, "FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects",  arXiv only,  26 March 2024 | [Link](https://arxiv.org/abs/2312.08344) |
| 2025-03-19 | Peng Lu, Tao Jiang, Yining Li, Xiangtai Li, Kai Chen, Wenming Yang, "RTMO: Towards High-Performance One-Stage Real-Time Multi-Person Pose Estimation", IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 1491–1501, | [Link](https://ieeexplore.ieee.org/document/10654887) |
| 2025-04-09 | Peng Lu, Tao Jiang, Yining Li, Xiangtai Li, Kai Chen, Wenming Yang, "RTMO: Towards High-Performance One-Stage Real-Time Multi-Person Pose Estimation", IEEE Transactions on Image Processing, vol. 33, pp. 1234–1245, 2024 | [Link](https://ieeexplore.ieee.org/document/10299609) |
| 2025-05-21 | Manqing Dong, Hao Huang, Longbing Cao, "Can LLMs Serve As Time Series Anomaly Detectors?", arXiv preprint arXiv:2408.03475, 6 August 2024. | [Link](https://arxiv.org/abs/2408.03475) |

You can use [MathJax](https://www.mathjax.org/) to write LaTeX expressions. For example:
When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
