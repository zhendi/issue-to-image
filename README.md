# issue-to-image
Create an issue to generate an image using AI

### Requirements

- [Cloudflare](https://dash.cloudflare.com/) account (for AI Image Generator)
- [sm.ms](https://sm.ms/) account (for Image Upload)

### Usage

- fork this project
- set Github Actions secrets:
  - CF_ACCOUNT
    - your Cloudflare account
  - CF_TOKEN
    - your Cloudflare Workers AI API token
  - SM_MS_TOKEN
    - your sm.ms API token
- create an issue to verify
