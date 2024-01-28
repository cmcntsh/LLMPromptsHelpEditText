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

#### Generate a writing report and suggested revision 

Prompt: (I get inconsistent results with the report, but the revision text is not bad.)

```
Please generate a report about the following text, which is enclosed by double quotes, based on the following criteria:
Identify grammar, syntax, usage, spelling, and punctuation errors and suggest specific improvements;
in addition, Identify plagiarism and suggest specific improvements;
in addition, Report document statistics;
in addition, Report vocabulary statistics:
in addition, Report the readability score;
in addition, Report the tone type (available options are Formal, Informal, Optimistic, Worried, Friendly, Curious, Assertive, Encouraging, Surprised, or Cooperative);
in addition, Report the intent type (available options are  Inform, Describe, Convince, or Tell A Story);
in addition, Report the audience type (available options are General, Knowledgeable, or Expert);
in addition, Report the style type (available options are formal or informal);
in addition, Report the emotion type (available options are mild or strong);
in addition, Report the domain type (available options are General, Academic, Business, Technical, Creative, or Casual);
in addition, Report the Flesch-Kincaid Grade Level.
Please provide revised text that adheres to the following instructions:
If the Flesh-Kincaid Grade level of the text is higher than 15, can you rewrite the text so that the grade level should be around 15, assuming that the audience type is Knowledgeable or Expert;
In addition, if the domain type of the text is Casual, then the text that you rewrite should have a domain type that is either academic or technical;
In addition, if the intent type of the text is Convince, then the text that you rewrite should have an intent type that is either Describe or Inform;
In addition, if the style type of the text is Informal, then the text that you rewrite should have a style type that is Formal;
In addition, if the emotion type of the text is Strong, then the text that you rewrite should have a style type that is Mild.
Here is the text: "[paste text here]"
```

## 3. Proofreading

* https://www.grammarly.com/blog/proofreading-habits-2017/
* https://www.grammarly.com/blog/how-to-proofread-emails/
* https://www.grammarly.com/blog/proofreading/

