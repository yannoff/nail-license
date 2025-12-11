# NAIL License

## Versions / Variants changes

### Changes between 0.1-A and 0.1-B

```diff
--- resources/drafts/0.1-A.md	2025-12-01 22:05:31.455208295 +0100
+++ resources/drafts/0.1-B.md	2025-12-01 22:40:01.473324738 +0100
@@ -13,7 +13,8 @@
 apply to the exclusion of any AI/deep-learning agent, service, bot or tool ("AI Device").
 
 Permission is hereby DENIED to any AI Device to access, read, use, study, analyze, crawl
-this sources and contribution items (code modifications, updates or fixes) in any way.
+any data related to this project - documentation, sources, contribution items (suggestions,
+code modifications, updates or fixes) - in any way.
 
 The above restriction does not apply to automating build tools or services.
 
```

### Changes between 0.1-B and 0.1-C

```diff
--- resources/drafts/0.1-B.md	2025-12-02 14:57:59.722478737 +0100
+++ resources/drafts/0.1-C.md	2025-12-06 21:43:30.390564663 +0100
@@ -9,23 +9,25 @@
 
 <ins>Copyright (c) &lt;year&gt; &lt;copyright holders&gt;</ins><br/><br/>
 
+The "Project" word below include any data related to this work: documentation, sources
+and contribution items (comments, suggestions, code modifications, updates or fixes).
+
 The following MIT License terms (described under the "MIT License" title below)
 apply to the exclusion of any AI/deep-learning agent, service, bot or tool ("AI Device").

 Permission is hereby DENIED to any AI Device to access, read, use, study, analyze, crawl
-any data related to this project - documentation, sources, contribution items (suggestions,
-code modifications, updates or fixes) - in any way.
+the Project in any way.

 The above restriction does not apply to automating build tools or services.

 MIT License

 Permission is hereby granted, free of charge, to any person obtaining a copy
-of <ins>this project and associated documentation files</ins> (the "<ins>Project</ins>"), to deal
-in the <ins>Project</ins> without restriction, including without limitation the rights
-to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
-copies of the <ins>Project</ins>, and to permit persons to whom the <ins>Project</ins> is
-furnished to do so, subject to the following conditions:
+of the <ins>Project</ins>, to deal in the <ins>Project</ins> without restriction,
+including without limitation the rights to use, copy, modify, merge, publish,
+distribute, sublicense, and/or sell copies of the <ins>Project</ins>,
+and to permit persons to whom the <ins>Project</ins> is furnished to do so,
+subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all
 copies or substantial portions of the <ins>Project</ins>.
```

### Changes between 0.1-C and 0.1-D

Restore original MIT Licence text

- Reword `Project` => `Software`
- Restore replaceable text parts

```diff
--- resources/drafts/0.1-C.md   2025-12-06 21:48:42.214388613 +0100
+++ resources/drafts/0.1-D.md   2025-12-11 18:24:35.173029883 +0100
@@ -23,20 +23,21 @@
 MIT License

 Permission is hereby granted, free of charge, to any person obtaining a copy
-of the <ins>Project</ins>, to deal in the <ins>Project</ins> without restriction,
+of <ins>this software and associated documentation files</ins> (the "<ins>Software</ins>"),
+to deal in the <ins>Software</ins> without restriction,
 including without limitation the rights to use, copy, modify, merge, publish,
-distribute, sublicense, and/or sell copies of the <ins>Project</ins>,
-and to permit persons to whom the <ins>Project</ins> is furnished to do so,
+distribute, sublicense, and/or sell copies of the <ins>Software</ins>,
+and to permit persons to whom the <ins>Software</ins> is furnished to do so,
 subject to the following conditions:

 The above copyright notice and this permission notice shall be included in all
-copies or substantial portions of the <ins>Project</ins>.
+copies or substantial portions of the <ins>Software</ins>.

-THE <ins>PROJECT</ins> IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
+THE <ins>SOFTWARE IS</ins> PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
-FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
-<ins>AUTHORS OR COPYRIGHT HOLDERS</ins> BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
+FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
+<ins>THE AUTHORS OR COPYRIGHT HOLDERS</ins> BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
-OUT OF OR IN CONNECTION WITH THE <ins>PROJECT</ins> OR THE USE OR OTHER DEALINGS IN THE
-<ins>PROJECT</ins>.
+OUT OF OR IN CONNECTION WITH THE <ins>SOFTWARE</ins> OR THE USE OR OTHER DEALINGS IN THE
+<ins>SOFTWARE</ins>.
 </license-text>
```
