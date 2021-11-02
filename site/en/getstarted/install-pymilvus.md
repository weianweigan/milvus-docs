---
id: install-pymilvus.md
label: Install PyMilvus
related_key: SDK
order: 0
group: sdk
summary: Learn how to install the Python SDK of Milvus.
---

# Install Milvus SDK

This topic describes how to install Milvus SDK for Milvus.

Current version of Milvus supports SDKs in Python and Node.js.

{{tab}}

## Requirement

Python 3 (3.6 or later) is required.

## Install PyMilvus via pip

PyMilvus is available in [Python Package Index](https://pypi.org/project/pymilvus/).

```
$ python3 -m pip install pymilvus=={{var.milvus_python_sdk_version}}
```

## Verify installation

If PyMilvus is correctly installed, no exception will be raised when you run the following command.

```
$ python -c "from pymilvus import Collection"
```



## What's next

Having installed PyMilvus, you can:

- Learn the basic operations of Milvus:
  - [Connect to Milvus server](connect.md)
  - [Conduct a vector search](search.md)
  - [Conduct a hybrid search](hybridsearch.md)

- Explore [PyMilvus API reference](/api-reference/pymilvus/v{{var.milvus_python_sdk_version}}/tutorial.html)