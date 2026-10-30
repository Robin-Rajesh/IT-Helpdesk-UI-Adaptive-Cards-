# 🧩 IT Helpdesk UI with Adaptive Cards

Adaptive Card templates for building rich, interactive chat interfaces in **Microsoft Copilot Studio** bots.

![Adaptive Cards](https://img.shields.io/badge/Adaptive_Cards-1.5-5059C9?logo=microsoftteams&logoColor=white)
![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-0078D4)

## 💡 Why Adaptive Cards?

Adaptive Cards use a JSON schema to render rich UI inside Copilot Studio chats, which is more engaging and less error-prone than plain text.

For a question like *"Which OS: Windows, Mac or Linux?"*, an Adaptive Card can show buttons or a choice set. Users pick from the options, so the bot captures clean input automatically and avoids the typos that come with free-text answers.

## 📂 Files

| File | Description |
|---|---|
| `foodOrder.json` | Adaptive Card (schema v1.5) with a heading, a question and a templated `ImageSet` that binds menu images from data using `${...}` expressions |
| `agenda.json` | Placeholder for an agenda card (currently empty) |

## 🚀 Trying the cards

1. Open the [Adaptive Cards Designer](https://adaptivecards.io/designer/).
2. Paste the contents of a JSON file into the **Card Payload Editor**.
3. Add sample data in the **Sample Data Editor** to preview the templated fields.
4. In Copilot Studio, use the JSON in an **Ask with Adaptive Card** node.
