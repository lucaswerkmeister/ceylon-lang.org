---
layout: reference
title_md: '`?` (default) operator'
tab: documentation
unique_id: docspage
author: Tom Bentley
doc_root: ../../..
---

# #{page.title_md}

The right-associative, binary `?` operator is used to specify a *default* value.

## Usage 

<!-- try: -->
    void m(Integer? num) {
        Integer numOrDefault = num ? 0;
    }

## Description

### Definition

The meaning of `?` is defined as follows:

<!-- check:none -->
<!-- try: -->
    if (exists lhs) lhs else rhs

See the [language specification](#{site.urls.spec_current}#nullvalues) for more details.

### Polymorphism

The `?` operator is not [polymorphic](#{page.doc_root}/reference/operator/operator-polymorphism). 


## See also

* [`?`](#{site.urls.spec_current}#nullvalues) in the language specification.
* [operator precedence](#{site.urls.spec_current}#operatorprecedence) in the 
  language specification
