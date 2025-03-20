# Style guide

Follow these guidelines to maintain a professional yet approachable tone, use inclusive language, and structure information effectively. The guide also covers Markdown usage for formatting, lists, headings, and tables to keep the documentation organized and visually clear.

## Voice, tone, and language

Write in a natural, conversational, and respectful way. Keep sentences clear and direct, avoiding slang, excessive informality, or unnecessary complexity. Stay approachable without being overly familiar while ensuring clarity.

Use a friendly and confident tone to make the content more engaging. Also, use active language and avoid sounding robotic or overly authoritative.

Since our members come from diverse backgrounds, use simple and inclusive language. When referring to a person, use **they/their** unless you know their specific pronouns.

Avoid cultural references that may not translate well, and focus on making the content easy to understand for everyone.

## Spelling

Use American English spelling. For example:

- color, not colour
- optimize, not optimise
- canceled, not cancelled

## Headings

Use sentence case for headings by capitalizing only the first word. If a heading includes an official term, retain its original capitalization. Ensure your headings are concise and descriptive.

Also, use heading levels in sequential order without skipping. For example, progress from H1 to H2 to H3. Avoid using headings beyond H3. Instead, structure content with numbered or bullet lists.

## Words to avoid

Avoid informal or unclear words. Use the following table for guidance:

| Word    | Meaning             | Use instead         |
|---------|---------------------|---------------------|
| ain’t   | Is not              | isn’t               |
| gonna   | going to            | going to            |
| gotta   | got to              | have to             |
| how’d   | how did / how would | how did / how would |
| how’ll  | how will            | how will            |
| I’d     | I would             | I would             |
| may’ve  | may have            | may have            |
| mayn’t  | may not             | may not             |
| might’ve| might have          | might have          |
| mightn’t| might not           | might not           |
| ’twas   | it was              | it was              |

## Commonly misused words and preferred alternatives

The following table shows the commonly misused words and their preferred alternatives:

| Avoid                            | Use instead                                                               |
|----------------------------------|---------------------------------------------------------------------------|
| cons                             | disadvantages                                                             |
| desire, desired                  | want or need                                                              |
| does not yet                     | doesn’t                                                                   |
| e.g.                             | for example or such as                                                    |
| enable                           | use **turn on** for features or **lets you** for capabilities |
| pros                             | advantages                                                                |
| leverage                         | use **build on**, **use**, or **take advantage of** if needed             |

## Lists

You can use lists to organize information in the documentation. There are two types of lists:

### Numbered lists

Use numbered lists for step-by-step instructions when order matters. For example:

1. Install the necessary software.
2. Configure the settings.
3. Run the application.

### Unnumbered lists

Use bullet lists for items that don't follow a specific order. For example:

- Features included in the latest update
- Supported file formats
- Common error messages

Avoid overly complex nesting in lists. If a list becomes too deep, consider breaking it into smaller sections. Ensure all items in a list follow the same grammatical structure to maintain clarity.

## Markdown usage

This documentation uses Markdown. The following are the common syntax elements with examples:

### External links

Create an external link with this syntax:

```markdown
[Link text](https://example.com)
```

### Headings

The syntax for headings one through three is as follows:

1. Heading one (H1):
    ```markdown
    # Heading one - page title
    ```

2. Heading two (H2):
    ```markdown
    ## Heading two - section title
    ```

3. Heading three (H3):
    ```markdown
    ### Heading three - subsection
    ```

### Paragraphs

Separate paragraphs with a blank line without indentation.

### Lists

A list can be either numbered or unnumbered. You can also nest lists to create different hierarchy levels:

1. Numbered lists

    Start each item with a number followed by a period and a space. Add a blank line before and after the list:
    
    ```markdown
    1. Item 1
    2. Item 2
    3. Item 3
    ```

2. Unnumbered lists

    Start each item with a hyphen (`-`) followed by a space. Add a blank line before and after the list:
    
    ```markdown
    - Item 1
    - Item 2
    - Item 3
    ```

3. Nested lists

    Indent each sub-item level using four spaces:
    
    ```markdown
    - Item 1
        - Sub-item 1
        - Sub-item 2
    - Item 2
        - Sub-item 1
        - Sub-item 2
    ```

### Bold

Wrap text with double asterisks (`**`) to make it bold:

```markdown
**This text is bold.**
```

### Italic

Wrap text with single underscores (`_`) to make it italic:

```markdown
_This text is italic._
```

### Bold and italic combined

Combine single underscores and double asterisks to make text both bold and italic:

```markdown
_**This text is bold and italic._**
```

## Tables

Use Markdown tables for structured data. Here’s an example:

```markdown
| Header 1        | Header 2        |
|-----------------|-----------------|
| Row 1, Column 1 | Row 1, Column 2 |
| Row 2, Column 1 | Row 2, Column 2 |
```
