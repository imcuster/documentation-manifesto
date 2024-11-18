# Ian's Documentation Manifesto

The primary goal of documentation should be to enable a human with an unknown amount of knowledge to be able to utilize and maintain resources you have created, **by themselves, without help.**  Documentation should be written **by humans, for a human audience.**

The primary source of documentation in a Git repository should be the `README.md` file at the root of the directory structure.

## README.md requirements

A `README.md` file should contain the following information:

- What is in this repository?
- What can I use this repository for?
- If I am going to use this repository:
    - What questions do I need to answer beforehand?
    - What considerations do I need to make about this repository's place within a larger ecosystem?
    - What information and additional resources do I need to supply which aren't inherent to the repository itself?
- What are some common issues that can be encountered while using this repository, and how do I mitigate them?
- Does this repository contain dependencies on other resources?
    - If so, how do I ensure that those dependencies are accounted for when I use this repository?
- If I have questions about this repository that aren't covered by the documentation, or if I want to modify the repository, how do I do that?
    - If I want to modify the repository, are there specific procedures that I need to follow that go above and beyond the standard Git workflow?

## Visual aids, sample code, and links

If your documentation requires visual aids, you should provide screenshots that are clear and focused, with as little extraneous visual information as possible.

- Screenshots of content on the internet should not include any interface elements from web browsers except when necessary.  If you're documenting a workflow in AWS, for instance, the web browser you are using should not be present in the visual aid. 

If your documentation requires sample code, provide it inline...

```
like this
```

...and provide clear context for your sample code.

If your documentation requires inline hyperlinks to resources on the internet, provide the link with descriptive text or the name of the resource instead of simply providing a URL, like this: [GitHub](https://github.com/), instead of https://github.com.

## Inline code comments

Comments in code you have written should be used sparingly, but should still exist in a limited capacity:

- Inline comments should provide human-readable names and (brief) descriptions of what an object "does" in cases where the name of the object does not clearly explain itself, or where an object does not include its own descriptive element.

It is important to note that comments in code do not constitute complete documentation.  You still need to create descriptive content outside of the code itself.

## Documentation tools

There are tools that will automatically produce documentation for a repository, but the following should be considered when using those tools:

- Automated documentation tools should not be relied on to produce the entirety of the documentation for a repository.
- These tools can only work with the information that is provided to them.  Remember: Garbage in, garbage out.
- These tools should be used as an addition to, not a replacement for, documentation written by humans for a human audience.


## AI

Do not use AI tooling to produce documentation.  You cannot trust AI to understand the intent of a resource you have created.  **AI is not, and cannot be, pragmatic.**  AI cannot be trusted to understand the context of a resource you have created within a larger ecosystem.

## Terminology

If the language used in a document can't be exactly correct, it should at least be consistent.  Changing terminology halfway through will result in an incoherent document that can do more harm than good.

## Editing

After you have produced a draft of your documentation, **read it out loud,** either to yourself or to a willing audience.  It is highly likely that you will encounter issues that you will want to fix, in the form of awkward wording, unclear or incorrect information, incorrect spelling, or any number of other things that you cannot be expected to account for when writing in a vacuum.

**No documentation is perfect,** neither is this, and neither is yours.  Good documentation requires consistent effort beyond the original composition.  Issues with documentation should be called out when possible, because bad documentation is worse than no documentation.
