| Develop with Redis |
| --- |
| Quick starts |
| Data structure store |
| Document database |
| Vector database |
| RAG with Redis |
| Redis in AI |
| FAQ |
| Understand data types |
| Interact with data |
| Use Redis |
| Reference |
| Libraries and tools |
| Commands |

Docs → Develop with Redis → Quick starts → Redis as a document database quick start guide

## Redis as a document database quick start guide

Understand how to use Redis as a document database

This quick start guide shows you how to:

* . Create secondary index

* . Add JSON odcuments

* . Search and query your data

The examples in this article refer to a simple bicycle inventory that contains JSON documents with the following structure:

{

"brand": "brand name", "condition": "new | used | refurbished", "description": "description", "model": "model", "price": 0 }

Setup

The easiest way to get started with Redis Stack is to use Redis Cloud:

. Create

free account.