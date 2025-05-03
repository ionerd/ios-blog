---
title: MarkdownUI Showcase
description: A comprehensive test of all MarkdownUI features
date: "2025-05-03T08:09:50Z"
---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

## Emphasis & Inline Elements

- *Italic* or _Italic_
- **Bold** or __Bold__
- ~~Strikethrough~~
- `Inline code` inside a sentence
- Mixed _**`emphasis`**_ styles

---

## Lists

### Unordered

- First item
- Second item
  - Nested item
  - Another nested item

### Ordered

1. First
2. Second
3. Third

---

## Blockquote

> This is a blockquote.  
> It can span multiple lines.

---

## Links & Images

- [Visit Apple](https://apple.com)

![Swift Logo](https://swift.org/assets/images/swift.svg)

    You can also insert images in a line of text, such as
    ![](https://picsum.photos/id/237/50/25) or
    ![](https://picsum.photos/id/433/50/25).

    ```
    You can also insert images in a line of text, such as
    ![](https://picsum.photos/id/237/50/25) or
    ![](https://picsum.photos/id/433/50/25).
    ```

---

## Table

| Name     | Language | Year |
|----------|----------|------|
| Swift    | Swift    | 2014 |
| Kotlin   | Kotlin   | 2011 |
| Python   | Python   | 1991 |

---

## Code Block

```swift
import SwiftUI

struct HelloView: View {
    var body: some View {
        Text("Hello, MarkdownUI!")
    }
}
