# cpython-sprint

## Purpose

Analyze a snapshot of bpo issues

## Installation

With Python 3.8+:

```
pip install -r requirements.txt
```

## Data collection

Snapshot CSV as the following query for all open issues:

```
https://bugs.python.org/issue?@columns=title,id,stage,creation,activity,components,assignee,status,message_count&@filter=status&@pagesize=500&@startwith=0&status=1&@dispname=all%20open
```

