If you need a paragraph-long comment to justify why the workaround is OK, the code is wrong - fix the code..
After every code comment you write, ask yourself, "Is this information the next Claude would spend multiple tool calls trying to understand?". If the answer isn't clearly yes, the code comment is noise - delete it.
Follow existing code style, check neighboring files for patterns
Use absolute paths, always use absolute paths in file operations
Be humble & honest - NEVER overstate what you got done or what actually works in commits, PRs or in messages to the user.
Avoid emojis and excessive lists or tables of items.
When writing documentation, be simple and concise. Make it easy to read at a glance and prioritize what a user would need to get the project running locally.
