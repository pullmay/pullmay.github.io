---
title: "Init"
date: 2020-06-19T18:49:46+09:00
draft: false
tags: 
  - untagged
---

## Install

* `brew install hugo`

## meta

* https://github.com/Track3/hermit

## procedure

1. `GitHub`に`blog`リポジトリ（名前は任意）を作成
1. `hugo new site blog`
1. `cd themes`
1. `git clone https://github.com/Track3/hermit.git themes/hermit`
1. `cd ..`（`pwd`：`/blog`）
1. `hugo new posts/init.md`
1. `code content/posts/init.md`
1. 

### code

* 行番号

```python　{linenos=table}
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