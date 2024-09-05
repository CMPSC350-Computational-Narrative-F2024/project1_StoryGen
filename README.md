# Project 1: System for Generating Stories

## Timeline

Activity                   | Deadline
-------------------------- | ------------------------------
Regular Commits:  | September 6th-27th, 2024 (total: 20 commit requirement, at least 1 on September 6th, 13th, and 20th)
Planning (add a theme to the report) | September 6th, 2024 by 4:20pm
Peer Interview ([Google Form](https://forms.gle/JUygtcTEVhNvWcbM7)) | September 13th, 2024 during lab
Demo of work-in-progress | September 20th, 2024 during lab
Final submission and Critique | September 27th, 2024 by 11am, critique in class and during lab if needed

## Summary

Prompt engineering -- the practice of learning to con/destructively "pilot" a generative model -- is one of the surprising new skills to emerge out of the development of context-aware large language models (LLM). Simply put: prompt engineering is the practice of instructing a model to produce an output consistent with the prompter's intent or desire. While we've given a new name to what essentially amounts to "asking the right questions," prompt engineering is much more than that.

In this project, you are invited to create a system that generates stories. The generated stories should follow some structure of a narrative. The system should be based on some kind of formalism or abstraction about narrative — either something you learned about or something you have come up with yourself. The system should provide a set of instructions to follow or an interface to interact with, and at the end produce some kind of a story. The system should be expressive, i.e., following the instructions multiple times should produce noticeably different stories. Be _creative_ and _weird_! 

## Learning

* [Methods of Prompt Programming](https://www.promptingguide.ai/techniques)
* [OpenAI API](https://platform.openai.com/docs/overview)
* [OpenAI Notes on prompt design](https://platform.openai.com/docs/guides/prompt-engineering/six-strategies-for-getting-better-results)

## Learning Outcomes

* Learn to interact with LLM through the practice of prompt engineering
* Refine skills in prompt engineering to increase efficacy and quality of output
* Discover exploitable boundaries in LLM generation
* Develop a model of on constraint as an enabling practice

These assignment learning outcomes contribute to the following course learning outcomes described in the [course syllabus](https://github.com/CMPSC350-Computational-Narrative-F2024/course_information):

1. Correctly describe and apply best practices of prompt engineering across a range of large language model (LLM) platforms to design successful prompts.
4. Develop software to interact with language model application programmer interfaces (APIs).
5. Create and justify a body of text products that leverage text-to-text, text-to-image, and other language model technologies.

This assignment also contributes to the `Modes of Expression` distribution learning outcome.

## Baseline Requirements

* Use a `programming language` of your choice to develop a `story generating system`.
* Your system must apply a `GPT model` (your choice) via `API` to assist in generating text for the story.
* Prompts must only be `zero-`, `few-`, or `many-` shot prompts.
* Your system must provide `user interaction` (instructions to follow or prompts for the user).
* The generated story must vary each time the system runs, have a relevant `title`, range from ~800 to 1500 words, and follow the same common `theme`.

### Assessment

In addition to participation in work-in-progress work described in the [Timeline section](#timeline), your final submission should include two (2) completed files for this assignment to be considered "complete". 

### `writing/report.md`

This contains documentation of all the prompts you have tried to use along with reflection on their uses. It should also include one example of a generated story and learning takeaways from this project.

### `src/main.py`

The program behind your story generation, including communication with the GPT API. 

Final submissions that do not include working system or a (mostly) completed report will be considered `Incomplete`. Individuals who do not participate in (most of) the `process` portions of the assignments will have their assignment marked as `Incomplete`.

### GatorGrade

You can check the baseline writing and commit requirements of this project by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python installed. If not, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor or TLs during the laboratory sessions. Alternatively, you may ask questions in the Discord channel for this course. Finally, you can schedule a meeting during the course instructor's office hours.
