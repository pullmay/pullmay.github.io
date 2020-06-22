---
title: "Init"
date: 2020-06-19T18:49:46+09:00
lastmod: 2020-06-21T10:51:17+09:00
draft: false
tags: 
  - untagged
---

## Install

* `brew install hugo`

## meta

* https://github.com/Track3/hermit


## code

* 行番号（反映されない）

```python　{linenos=table}
def is_prime(p):
    return True
```

* theme適用

```python:is_prime.py
def is_prime(p):
    return True
```

* ハイライト

```python {hl_lines=[1, 3, "5-8"]}
import json

def lambda_handler(event, context):
    # TODO implement
    return {
        'statusCode': 200,
        'body': json.dumps('Hello from Lambda!')
    }
```

## ブロック環境？

{: .box-note}
**Note:** This is a notification box.

{: .box-warning}
**Warning:** This is a warning box.

{: .box-error}
**Error:** This is an error box.

## Twitter埋め込み

```markdown
{{(<) tweet 1275030562730737665 (>)}}
```

※`()`は不要

{{< twitter 1275030562730737665 >}}