![](https://www.banana.dev/lib_zOkYpJoyYVcAamDf/x2p804nk9qvjb1vg.svg?w=340 "Banana.dev")

# Banana.dev illusion-diffusion-hq starter template

This is a illusion-diffusion-hq starter template from [Banana.dev](https://www.banana.dev) that allows on-demand serverless GPU inference.

You can fork this repository and deploy it on Banana as is, or customize it based on your own needs.

# Running this app

## Deploying on Banana.dev

1. [Fork this](https://github.com/bananaml/demo-illusion-diffusion-hq/fork) repository to your own Github account.
2. Connect your Github account on Banana.
3. [Create a new model](https://app.banana.dev/deploy) on Banana from the forked Github repository.

## Running after deploying

1. Wait for the model to build after creating it.
2. Make an API request using one of the provided snippets in your Banana dashboard. However, instead of sending a prompt as provided in the snippet, you have to send the request structured as following:

```python
inputs = {
    "prompt" : "your_promot",
    "negative_prompt": "your_negative_prompt",
    "image": "your_base64_image",
    "seed": "your_seed"
}
```

For more info, check out the [Banana.dev docs](https://docs.banana.dev/banana-docs/).

