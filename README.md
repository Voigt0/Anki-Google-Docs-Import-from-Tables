# 📄 Voigt – Google Docs to Anki (Tables Version)

A modified version of [Google Doc Decks (Remote Decks)](https://ankiweb.net/shared/info/924929499) that allows you to create Anki flashcards from **Google Docs** using **tables** and is integrated into the creator's addon ecosystem.

> 🧪 This add-on is currently in beta. It focuses on simplicity and ease of use. More features are planned.

## ✨ What's New

The main enhancement is the ability to generate Anki flashcards from **tables** (`<table>`) in Google Docs.

This was designed to better suit workflows where Google Docs are structured with tables, providing a more flexible and readable input method for many users.

---

## ✅ Features

- 🟢 Create **Basic** Anki cards from Google Docs
- 🟣 Use **tables** integrated into the creator's addon ecosystem
- 🖼️ Support for **embedded images** in answers
- 🎨 Preserves **text formatting** (bold, italic, underline, color)
- 🚫 Lines starting with `#` are ignored (good for comments/headings)
- 🔁 Supports syncing updated documents
- 🛠️ Lightweight and minimal codebase

---

## 📝 How to Format Your Google Doc

Write your content in this structure:

```markdown
<table>
  <tr>
    <td>What is the capital of France?</td>
    <td>Paris</td>
  </tr>
  <tr>
    <td>What is 2 + 2?</td>
    <td>4</td>
  </tr>
  <tr>
    <td>What is shown in the image?</td>
    <td><img src="https://example.com/image.png"></td>
  </tr>
</table>
```

- `* Question` → creates a card front
- `  * Answer` → creates a card back
- Anything starting with `#` is ignored (like Markdown headers)

---

## 🌐 How to Publish Your Google Doc

1. Open your document in Google Docs
2. Go to `File → Share → Publish to web`
3. Click **Publish**
4. Copy the **link** provided

> This link is required to sync the document with Anki

---

## 📥 Importing the Deck into Anki

1. Open Anki
2. Click `Voigt → Table Decks → Add New Remote Deck`
3. Paste your **published URL**
4. Click **OK**

Anki will create the deck with the cards parsed from your document.

---

## 🔁 Syncing Updates

Want to update the deck after editing the doc?

1. Edit your Google Doc
2. Wait a few minutes (Google takes time to publish changes)
3. In Anki, click `Voigt → Table Decks → Sync Remote Decks`

Your changes will be imported into Anki without duplicating cards.

---

## 🧹 Removing a Remote Deck

If you no longer want a document to sync:

1. Click `Voigt → Table Decks → Remove Remote Deck`

> ⚠️ This does **not delete** the cards. It only removes the remote sync link.

---

## ✨ Formatting Support

You can use the following in your Google Doc:

- **Bold**
- _Italic_
- <u>Underline</u>
- <span style="color:red;">Text color</span>
- 🖼️ Embedded images (`<img>` tags)

---

## 🙏 Credits

Based on the original [Google Doc Decks (Remote Decks)](https://ankiweb.net/shared/info/924929499)  
Created by the [AnKing team](https://www.ankingmed.com)  
Modified by [V01gt](https://github.com/V01gt) for table support

All original rights reserved to their respective authors.

---

> Built to simplify your workflow. If you’re a student using Google Docs to learn, this add-on is made for you.
```

---
