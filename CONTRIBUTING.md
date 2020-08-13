# Contributing to Muninn

Welcome. If you've found this page, you are probably interested in contributing to this project. Thank you.

Before you jump into your first pull request, you need a quick primer on how this works and how best to contribute.

## The Purpose

The purpose of this project is to build a collection and network of memories and notes about the world as we see it right now, particularly in the United States and other countries whose democracy is being threatened by fascism and authoritarianism. Like the diaries from Nazi Germany, these should be records of our thoughts, feelings, etc., less for our contemporaries to read and more for historians after this is all said and done.

## The Stack

While this looks like just a collection of Markdown files, it's actually a [Foam](https://foambubble.github.io/foam/) project, which provides a few supports above and beyond basic Markdown. For best results, download the repository and open the workspace in VSCode, where you will then have access to network graphs, wiki-link, and backlink capabilities from the workspace settings.

### The Features

The Foam project is quickly evolving and their documentation will be more thorough, but I want to call out a couple of features in particular, as well as what I've added.

1. **Wiki-links** - in the rendered pages, you'll notice some links are surrounded by a set of square brackets (`[ ]`). In the source files, these appear to be plain text surrounded by a double set of square brackets (`[[ ]]`). These are wiki-links and will link entries together. The text inside the bracket in the source map to the file names (ideally without the file extension).
2. **Link Graph** - this generates a visual chart of the links, showing how they relate to one another.
3. **Paste Image** - this is an extension I've added to the recommended extensions. It allows you to paste an image from the clipboard into the Markdown editor. It will save the file and generate an image Markdown tag for it, so you don't have to.

## The Rules

In order to preserve the spirit of the project, I must lay a few ground rules, which will be strictly enforced.

1. **No editing, deleting, or otherwise altering others' entries, even for grammar.** Only the entry's owner will be allowed to edit an existing entry. The entries are the writer's truth, perspective, and voice. Editing or deleting them defeats the purpose of this project. Add your own entry and make a link to the entry you wish to comment about.
2. **Refrain from editing your own content.** You can edit the entries you own, but try not to substantially change the content once it's written. Adding to an existing entry of your own is okay, though be sure to consider adding a new entry and linking back to the existing one.
3. **Only English-language entries.** This is both for my benefit (so that I can review and vet the content of submissions) and to create a common language for historians. I'm sorry to those whose English is not as good or who would rather contribute in their own language. Perhaps this will be loosened if/when I build a team of trusted translators, but my fluency of other languages is limited and allowing others at this time would undermine my ability to do some amount of content vetting. If you wish to do a similar project, you are welcome to fork this one or use it as a template for yours and refer back to this. Forking it would allow for merging your content if the project gets adequate translation/vetting capability, and would allow for connections in the meantime. Likewise, you are still welcome to contribute to this one in English to whatever ability you have in the language.
4. **I reserve the right to reject entries.** Given the nature of this project, I don't want to outright ban the perspectives of those who find this and are in favor of the current situation and the direction it's going. However, there's a very real risk that this could be overwhelmed or usurped by the malicious actors we are attempting to preserve information against. If this project grows large enough, this will likely turn into a team of moderators so that I'm not the sole bottleneck or point of failure.
5. **Content here is Creative Commons.** While there are rules against touching other people's entries while contributing, and your entries are tagged with you as the owner, the project is intended to be freely available, both for freedom and for security. The more widely this gets distributed, the more copies there are and the hard it is to destroy. The project is licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0), which is a Free Cultural Works license as defined by [Freedom Defined](https://freedomdefined.org/) and the Creative Commons organization. Your contributions are still your voice, but contributing to this project means you agree to your contributions also falling under this license.

## The Process

The act of contributing, itself, is pretty straightforward -- add an entry Markdown file and submit a pull request. I recommend doing this in VSCode with the recommended extensions installed and enabled, so that links, backlinks, compatibility links, etc are included from the get-go. Additionally, if your entries relate to any other entries in the project that you know of, be sure to link to them. These links will help with discoverability and navigation as the project grows. I encourage you to make full use of the Foam project/framework/tools whenever/wherever you can.

I also recommend that you limit your Pull Requests to no more than 5 entries added or changed. PRs larger than that may be rejected as too large and asked to be split up. (This isn't a hard-and-fast rule, which is why it isn't part of the ground rules. It will depend greatly on the context of the PR.)
