# Mathematical Writing

**by Donald E. Knuth, Tracy Larrabee, and Paul M. Roberts**

This report is based on a course of the same name given at Stanford University during autumn quarter, 1987. Here’s the catalog description:

> CS 209. Mathematical Writing - Issues of technical writing and the effective presentation of mathematics and computer science. Preparation of theses, papers, books, and “literate” computer programs. A term paper on a topic of your choice; this paper may be used for credit in another course.

The first three lectures were a “minicourse” that summarized the basics. About two hundred people attended those three sessions, which were devoted primarily to a discussion of the points in §1 of this report. An exercise (§2) and a suggested solution (§3) were also part of the minicourse.

前三次講座是一個總結基礎知識的“minicourse”。大約兩百人參加了這三屆會議，主要致力於討論本報告§1中的要點。練習（§2）和建議的解決方案（§3）也是minicourse的一部分。

The remaining 28 lectures covered these and other issues in depth. We saw many examples of “before” and “after” from manuscripts in progress. We learned how to avoid excessive subscripts and superscripts. We discussed the documentation of algorithms, computer programs, and user manuals. We considered the process of refereeing and editing. We studied how to make effective diagrams and tables, and how to find appropriate quotations to spice up a text. Some of the material duplicated some of what would be discussed in writing classes offered by the English department, but the vast majority of the lectures were devoted to issues that are specific to mathematics and/or computer science.

剩下的28次講座深入涵蓋了這些和其他問題。我們 在進步的手稿中看到了許多“之前”和“之後”的例子。我們學會瞭如何避免過度下標和上標。我們討論了算法，計算機程序和用戶的文檔手冊。我們考慮了裁判和編輯的過程。我們學習了如何進行有效的圖表和表格，以及如何找到適當的引箱來調味文本。一些材料重複了一些將在英語提供的課程中討論的內容部門，但絕大多數講座都致力於問題這是數學和/或計算機科學的特定。

Guest lectures by Herb Wilf (University of Pennsylvania), Jeff Ullman (Stanford), Leslie Lamport (Digital Equipment Corporation), Nils Nilsson (Stanford), Mary-Claire van Leunen (Digital Equipment Corporation), Rosalie Stemer (San Francisco Chronicle), and Paul Halmos (University of Santa Clara), were a special highlight as each of these outstanding authors presented their own perspectives on the problems of mathematical communication.

本報告包含本季度分佈的各種講義的講座和副本的成績單。我們認為課程能夠澄清一個令人驚訝的大量問題，這些問題在各個專業人士的生活中發揮著重要作用數學領域。因此，我們希望無法參加課程的人可能仍然可以從中受益，通過閱讀本綜述什麼是托運的。

This report contains transcripts of the lectures and copies of various handouts that were distributed during the quarter. We think the course was able to clarify a surprisingly large number of issues that play an important part in the life of every professional who works in mathematical fields. Therefore we hope that people who were unable to attend the course might still benefit from it, by reading this summary of what transpired.

本報告包含本季度分佈的各種講義的講座和副本的成績單。我們認為課程能夠澄清一個令人驚訝的大量問題，這些問題在各個專業人士的生活中發揮著重要作用數學領域。因此，我們希望無法參加課程的人可能仍然可以從中受益，通過閱讀本綜述什麼是托運的。

The authors wish to thank Phyllis Winkler for the first-rate technical typing that made these notes possible.

Caveat: These are transcripts of lectures, not a polished set of essays on the subject. Some of the later
lectures refer to mistakes in the notes of earlier lectures; we have decided to correct some (but not all) of those mistakes before printing this report. References to such no-longer-existent blunders might be hard to understand. Understand?

警告：這些是講座的成績單，而不是對受試者的拋光散文集。一些後來 講座是指早期講座的票據中的錯誤;在打印本報告之前，我們決定糾正一些（但不是全部）這些錯誤。對此沒有更長的空白的引用可能很難理解。理解？

Videotapes of the class sessions are kept in the Mathematical & Computer Sciences Library at Stanford.

The preparation of this report was supported in part by NSF grant CCR-8610181.

## Table of Contents

1. [Minicourse on technical writing](knuth-mathwriting-ch1.md)
2. An exercise on technical writing
3. An answer to the exercise
4. Comments on student answers (1)
5. Comments on student answers (2)
6. Preparing books for publication (1)
7. Preparing books for publication (2)
8. Preparing books for publication (3)
9. Handy reference books
10. Presenting algorithms
11. Literate Programming (1)
12. Literate Programming (2)
13. User manuals
14. Galley proofs
15. Refereeing (1)
16. Refereeing (2)
17. Hints for Referees
18. Illustrations (1)
19. Illustrations (2)
20. Homework: Subscripts and superscripts
21. Homework: Solutions
22. Quotations
23. Scientific American Saga (1)
24. Scientific American Saga (2)
25. Examples of good style
26. Mary-Claire van Leunen on ‘hopefully’
27. Herb Wilf on Mathematical Writing
28. Wilf’s first extreme
29. Wilf ’s other extreme
30. Jeff Ullman on Getting Rich
31. Leslie Lamporton Writing Papers
32. Lamport’s handout on unnecessary prose
33. Lamport’s handout on styles of proof
34. Nils Nilsson on Art and Writing
35. Mary-Claire van Leunen on Calisthenics (1)
36. Mary-Claire’s handout on Composition Exercises
37. Comments on student work
38. Mary-Claire van Leunen on Which vs. That
39. Mary-Claire van Leunen on Calisthenics (2)
40. Computer aids to writing
41. Rosalie Stemer on Copy Editing
42. Paul Halmoson Mathematical Writing
43. Final truths
