# PHP Loose Comparison Bug

This repository demonstrates a common yet subtle bug in PHP related to loose comparisons (using `==`) between strings and integers.  The core issue is that the expression `'0' == 0` evaluates to `true`, which may lead to unexpected behavior and potential security vulnerabilities in your applications. 

The `bug.php` file shows the problematic code. The `bugSolution.php` file demonstrates how to use strict comparison (`===`) to prevent this type of issue.  Always prefer strict comparisons to avoid ambiguity and unexpected behavior.