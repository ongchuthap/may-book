# Mây Book Privacy Policy

Last updated: 12 November 2026. [Tiếng Việt](privacy-policy.vi.md)

Mây Book is an EPUB reader with an optional AI reading assistant, made by an independent developer. This policy says what the app does with your data.

In short: the developer runs no server and receives nothing from the app. Your books, notes and conversations stay on your devices and in your own iCloud. Text goes to an AI provider or a web search service only when you have set one up with your own key and allowed it in the app.

## What the developer collects

Nothing. The app has no account, no analytics, no advertising, no tracking and no crash-reporting service, and it never contacts a server run by the developer. If you chose in your device's settings to share analytics with app developers, Apple may pass anonymous crash reports and usage statistics to the developer; that choice is between you and Apple.

## Where your data is kept

- **On your device**, in the app's own storage: your books (EPUB files), reading positions, highlights, notes, glossary terms, AI conversations, the AI's memory and briefs of your books, translations and settings.
- **In your iCloud**, when iCloud sync is on: book files in the app's folder in iCloud Drive, and the rest in files in the app's iCloud container, so your other devices get them. Apple keeps them under your Apple Account; the developer cannot see them.
- **API keys** are kept in iCloud Keychain (encrypted, synced only between your own devices). They are never written to iCloud Drive files and never sent to the developer.
- **Spotlight and widgets**: book titles are indexed in Spotlight on your device; highlights and notes only when you turn that on, on each device. Widgets show the current book and reading time from a copy kept on the device.
- **Fonts, read aloud and quick translation** work on the device: the fonts are part of the app, read aloud uses the system's voices, and short translations use Apple's on-device translation first.

## What goes to the AI provider you choose

The AI features work only after you add an API key (or the address of your own server) for an AI provider: OpenRouter, DeepSeek, OpenAI, or any OpenAI-compatible server you enter. Before anything is sent to a provider for the first time, the app shows a screen that names the provider and lists what is sent, and asks your permission. Only with that permission does the app send to that provider:

- your questions and the conversation in the thread;
- passages of the book: what you select, and what the AI reads or searches in the book to answer; the book's title and author, and where you are in it;
- your notes, highlights and glossary terms, when the AI looks them up;
- the AI's memory of the book and of you (notes and summaries of earlier conversations), with each question about that book;
- your instructions for the AI;
- text you ask to translate or explain, including words the device could not translate, and the chapters shown in bilingual mode;
- in the background: a brief of each book you import (its outline and about 6,000 words of passages), and summaries of your conversations for the AI's memory.

OpenRouter passes requests on to the company that makes the model you choose. A server you run on the same device (an address such as `localhost`) receives requests without a permission screen, because nothing leaves the device.

You choose the provider and hold the account with it, and the app sends it only what the feature you use needs. The provider handles what it receives under its own terms and privacy policy, which you accepted when you created your account and key; the developer has no agreement with the providers and receives none of this data. Read the provider's policy before you allow sharing.

## What goes to web search and web pages

When the AI's web tools are on and you set up a search service (Tavily, Brave Search, Exa, DeepSeek, or your own SearXNG server), the app sends that service, after you allowed it, the search queries the AI writes from your questions; for a book's brief, the queries contain the book's title and author. The AI may also open web pages from the results or from links you sent, again only after you allowed it: those websites see your device's network (IP) address and which page was asked for. With DeepSeek as the search service, DeepSeek opens those pages instead and sees their addresses.

## How to withdraw your permission

- **Settings › Privacy › AI Data Sharing** lists every provider and service you allowed. Stop sharing with one there: nothing more goes to it, and background work for it stops at once. The app asks again before it sends anything new.
- You can also turn off the AI's memory (Settings › Teaching Style), turn off web tools (Settings › Agent Tools) or remove a key (Settings › AI Providers).
- Data a provider or search service already received is kept under its own retention rules; delete it in your account with that company.

## Keeping and deleting your data

- Deleting a book in the app deletes its highlights, notes, conversations, memory and brief, on every device that syncs.
- In a book's memory view you can edit or clear what the AI remembers; conversations can be deleted one by one.
- To remove the iCloud copy, delete the app's folder in iCloud Drive and the app's data under your Apple Account's iCloud storage settings.
- Deleting the app deletes everything it stored on the device, except keys, which stay in iCloud Keychain: remove them in Settings › AI Providers before you delete the app.
- The developer keeps no data about you. If you email the developer (support, or "Report a problem with this answer"), the email is used only to look into your report and answer you, and is deleted once that is done.

## Reporting a problem

"Report a problem with this answer" opens your mail app with a message to the developer that contains the answer and the names of the model and provider. Nothing is sent unless you send that email yourself.

## Children

The app collects no personal data from anyone, children included.

## Changes

When this policy changes, the new version is published here with a new date, and the app shows the version that came with it.

## Contact

[mike.infra.dev@gmail.com](mailto:mike.infra.dev@gmail.com)
