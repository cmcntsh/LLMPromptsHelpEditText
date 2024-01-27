# LLM Prompts to Help Edit Text

## 1. Substantive Editing

* https://www.grammarly.com/blog/editing/

Prompt: Split the text into separate lines and number the lines

```
Please list each sentence of this text in a new line, and please number the lines Here is the text: "[paste your text here]"
```

Prompt: Get the main topic for each numbered line.

```
Please list the main topic of each sentence next to it's corresponding number.
```

Prompt: Reorder the numbered list.

```
please relist the sentences in the following order [list the new order with values separated by commas here]
```

**Prompt: Create an outline of text ordered by paragraphs** (This created an outline based on the paragraphs with the main topic of each first sentence used as level 1 headings. I like this prompt quite a bit. It made it easier to see when the writing may be fragmented and important points may be buried in the text.)

```
Please list the following sentences in outline format. Have the first sentence of each paragraph as level 1 and the remaining sentences in each paragraph as level 2. Here are the sentences: "[paste text here]"
```

Prompt: Create an outline of sentences (This created an outline based on the paragraphs with multiple levels.)

```
Please list the following sentences in outline format. Identify the main topic of each paragraph as level 1 and the remaining sentences in each paragraph as level 2. Here are the sentences: "[paste text here]"
```

Prompt: Have LLM suggest how to organize sentences (This is only partially successful. I didn't fully agree with some of the organization choices.)

```
I have a collection of sentences. Please organize the sentences into groups by topics and suggest an order of presentation that would make sense to a reader. Please rewrite the collection of sentences as coherent paragraphs based on the order you suggest. Here are the sentences: "[paste text here]"
```

## 2. Copy Editing

* https://www.grammarly.com/blog/whats-the-difference-between-copy-editing-and-proofreading/

## 3. Proofreading

* https://www.grammarly.com/blog/proofreading-habits-2017/
* https://www.grammarly.com/blog/how-to-proofread-emails/
* https://www.grammarly.com/blog/proofreading/

