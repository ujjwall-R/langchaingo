# Document

Language models only know information about what they were trained on. In order to get them to answer questions or summarize other information you have to pass it to the language model. Therefore, it is very important to have a concept of a document.

A document at its core is fairly simple. It consists of a piece of text and optional metadata. The piece of text is what we interact with the language model, while the optional metadata is useful for keeping track of metadata about the document (such as the source).

## Creating a Document

You can create a document object rather easily in LangChain with:

Also check out [Document Loaders](../indexes/document_loaders/) for a way to load documents from a variety of sources.
