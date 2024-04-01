# A Quickstart Template

A quick start is a guided tutorial with a scoped learning objective. They are useful for getting oriented with a feature, API, or project very quickly.


## Introduction

Description of what the post is about. 

_In this guide, we’ll walk you through creating a straightforward product page using ShopEasyAPI. We’ll cover just the images and descriptions. If you’re looking to dive into more advanced features like chatbots or recommendation engines, we have separate guides for those._

Or learning objectives, this example from the React Quick Start guide:
```
You will learn
* How to create and nest components
* How to add markup and styles
* How to display data
* How to render conditions and lists
* How to respond to events and update the screen
* How to share data between components
```
## Body
### Getting started
Loading this example quickly in the context of code. Being able to pull a full repository or deploy a version for themselves.

```
# Clone this repository
git clone https://github.com/xx/xxxxxx
# Go into the repository
cd xxxxxx
# Install dependencies
npm install
# Run the app
npm start
```


### Explanation of core components

_A basic React application with the following structure:_
* App.js
* index.js
* package.json
* README.md

#### Code Snippets
Include relevant code samples to help the reader understand how to build. For example, if this is a tutorial on how to use an API show the code for calling the API.

Sending an API request to Anthropic's Claude in Python.

```python
import anthropic

client = anthropic.Anthropic(
    # defaults to os.environ.get("ANTHROPIC_API_KEY")
    api_key="my_api_key",
)

message = client.messages.create(
    model="claude-3-opus-20240229",
    max_tokens=1000,
    temperature=0.0,
    system="Respond only in 7 words or less",
    messages=[
        {"role": "user", "content": "How are you today?"}
    ]
)

print(message.content)

```

## What's next
Generally a quick start guide will have a "What's next" section. This section is a list of resources that are useful for explorating what's possible. Ideally, the current tutorial will be the base in which the user can continue learning with other modules.

In the example of learning how to use a code repository with Git, the section might look like:

```
* Learn more about setting up a repository.
* Learn more about cloning a repository.
* Learn how to add a repository as a Git remote.
* Learn how to connect a repository hosted on GitHub or Bitbucket.
```

This section can also include resources for learning that are more in-depth. This could be links to documentation, API's, or additional examples.
