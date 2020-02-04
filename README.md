# Color Picker Custom Element for Kentico Kontent

This is a [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) for [Kentico Kontent](https://kontent.ai) that allows users to choose a color using a dynamic pallete. It saves the value as a HEX string (e.g. `#ff0000` for a bright red or `#00ff00` for a bright green).

![Screenshot of custom element](ColorPicker.gif)

## Setup

1. Deploy the code to a secure public host
    * See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Kentico/kontent-custom-element-sample-color-picker)

## What is Saved?

The value is saved as a HEX color code (e.g. `#ff0000` for a bright red or `#00ff00` for a bright green).

## Contributors

Originally contributed by [@dzmitryk-kentico](https://github.com/dzmitryk-kentico)