Quickstart with GPT3
================

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Install

``` sh
pip install gpt3_examples
```

## How to use

Import the functions and use them to play with GPT-3 models. Make sure
you create your own API keys by signing up in OpenAI

# Example

> Lets ask GPT3 to create some text for us!

    -First we write a prompt to send to the model
    -Then the model creates text for us based on the prompt

``` python
prompt = 'Whats a good tagline for champaign'

text_response = ask_gpt3(prompt)
print(text_response)
```

     bubbles for everyone!
