---
title: "rotatef"
---

# rotatef

import RotatefMacro from './_rotatef_macro.md';

<RotatefMacro />

## Expanded Reference: rotatef

:::tip
TODO: Please contribute to this page by adding explanations and examples
:::

```lisp
(let ((list1 (list 1 2 3 4))
      (list2 (list :A :B :C :D))
      (list3 (list "a" "b" "c" "d")))
  (rotatef (cdr list1) (cdr list2) (cdr list3))
  (values list1 list2 list3))

;;; 
;;; CL-USER> (1 :B :C :D)
;;;          (:A "b" "c" "d")
;;;          ("a" 2 3 4)
```
