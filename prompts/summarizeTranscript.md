---
PromptInfo:
 promptId: transcriptSummary
 name: ✉️ Take a transcript and summarize it
 description: Select the transcript and a bullet point summary will be generated.
 author: ~germ
 tags: transcript, summary
 version: 0.0.1
---
prompt: Write summary about the {transcript}. Any  information is in a bullet form, and any action item should be separate. At the end of each bullet, in parenthesis, put the people implicated with the topic (including the speakers or any specific name) in addition to the organisations and companies. 
transcript = {{context}}
summary bullet list: 