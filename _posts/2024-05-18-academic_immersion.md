---
layout: post
title:  Immersion learning applies to academic subjects, not just languages
date: 2024-05-18
description: Applying the input hypothesis to efficiently learn technical subjects
tags: research language-learning learning
categories: academics
toc:
  sidebar: left
citation: true
giscus_comments: true
---
It is difficult to learn dense technical subjects. Where do you begin, when there's an ocean of resources and a variety of projects to tackle? Immersion based language learning offers a good model.

## The Input Hypothesis
The idea of learning via massive amounts of input has gained popularity in language learning circles. The general trend is to bootstrap an initial learning period with a targeted amount of study, and then learn through immersion in normal content geared towards native speakers. This process can be paired with a spaced repetition system (e.g. anki) to speed up acquisition. The result is that output in a language—speaking and writing—is a function of input—listening and reading.

For example, in Japanese a learner might:

1. Learn vocabulary using an anki deck with the most common 2000 words
2. Begin exposure through subtitled anime
3. Progress to reading full books
4. Continually learn through all types of media

Indeed, this is more or less what I did to pass the N1 on the Japanese Language Proficiency Test.

Number two above highlights the idea of "comprehensible input." That is, the chance of comprehending the media should be maximized with supplements. Subtitled anime is a good example, because the person watching is simultaneously exposed to the spoken language (audio), the written language (subtitles), and the visual content of what is being described (the anime). If the content is barely comprehended then the learner doesn't learn much! Which is why jumping straight into reading full books probably isn't the most efficient learning method. The input should roughly match the learners ability.

## Immersion Machine Learning
How can we apply this idea to an academic subject? With the same general idea—a period of targeted study at the outset, followed by learning through immersion.

Let's use machine learning as an example:

1. Work through an introductory text, such as ISL<sup>1</sup>
2. Follow along with some Jupyter notebook tutorials using real code
3. Build your first project from scratch, targeting a real problem
4. Keep building while continually immersing in new papers, referencing textbooks when you get stuck, etc.

Step one allows you to gain familiarity with the new vocabulary and concepts. Step two is a form of comprehensible input—looking at real code made more comprehensible by explanations and experimentation. The rest is akin to immersing yourself in a language, or simply living in an environment with constant opportunities for input and output.

This provides a powerful way to overcome endlessly building up base knowledge through textbooks and courses. At some point, you have to jump into the deep end and learn how to swim. By purposely placing a limit on the initial bootstrap step you can overcome paralysis by analysis. This echoes some of the advice in the academia stack exchange post [How to stop hopping the learning chain and actually begin somewhere?](https://academia.stackexchange.com/questions/89032/how-to-stop-hopping-the-learning-chain-and-actually-begin-somewhere)

The key challenge here is to identify what a good introductory resource is, and to set a hard limit on getting through it in a timely fashion.

## Bottom-up or Top-down?
The textbook Mathematics for Machine Learning<sup>2</sup> by Deisenroth, Faisal, and Ong contains a discussion at the outset on bottom-up vs. top-down learning. Similar to inductive vs. deductive learning, they give the following definitions:

- **Bottom-up:** Building up the concepts from foundational to more advanced.
- **Top-down:** Drilling down from practical needs to more basic requirements.

While doing everything bottom-up seems logical, it's hard to deny the power of learning by doing. Projects are essential to mastery—you won't learn to swim just by reading about swimming. But, it is deeply frustrating to try to make something with insufficient background knowledge. Tightly targeted learning at the outset saves the headache of endlessly starting and abandoning learning resources and projects. Start with an appropriate amount of bottom-up before progressing into top-down, and then reference bottom-level concepts as needed to make progress.

P.S. You just read the first post on my blog! Thanks for swinging by.

---
## References
1. James, G., Witten, D., Hastie, T., Tibshirani, R. & Taylor, J. E. _An introduction to statistical learning: with applications in Python_. (Springer, 2023).
2. Deisenroth, M. P., Faisal, A. A. & Ong, C. S. _Mathematics for Machine Learning_. (2020).
