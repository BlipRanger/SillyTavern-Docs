# Kobold Horde

## Disclaimer

- Kobold Horde is a crowdsourced, distributed GPU cluster run entirely by volunteers.
- By default, your inputs are anonymously sent and responses can not seen by the person running the Horde Worker.
- However, since it is an open-sourced program, Malicious Workers could modify the code to:
  - log your activity (IP, input prompts, AI responses)
  - produce bad or offensive responses

!!!warning
When using Horde **never send** any personal information such as names, email addresses, etc.
!!!

Switching on on the "Trusted Workers Only" checkbox will help avoid this problem entirely, but will result in less available Workers.

To help reduce this problem, SillyTavern has built in the following feature:

- When a chat response is generated by a Horde Worker, SillyTavern records the Worker's ID and what model they were using.
- This information can be seen by hovering your mouse cursor over the chat item (see image below)
- If you believe you recieved a malicious response, you can pass this information to the Horde admin on the [Kobold Discord](https://koboldai.org/discord) for review and possible disciplinary action against that Worker.

![Horde Worker Info Popup](https://files.catbox.moe/kw657j.png)

## Setup

- SillyTavern is able to connect with Horde out of the box with no additional setup required.
- Just select 'Kobold Horde' from the API dropdown selector in the ST API panel.
- By default, your SillyTavern instance will act like a 'guest account' on the Horde, and be given low priority.
- This means you will probably have to wait a long time to get a reply.
- To reduce wait times:
  - Make an account on the Horde website.
  - Add your Horde account ID into the SillyTavern Horde API Key box.
- Select one or more models from the Model Selector at the bottom of the panel.
- Begin chatting.

  ![ST Kobold Horde API Connection Panel](https://files.catbox.moe/mtajd1.png)

## Tips

- You can also [register as a Horde Worker](https://github.com/Haidra-Org/AI-Horde-Worker#readme) to provide your GPU for others.
  - Letting others use your GPU earns you 'kudos', a kind of Horde-only currency.
  - The more kudos your account has, the faster you will get chat responses from other Horde Workers.
  - Kudos can also be used to create AI images on [Stable Horde](https://stablehorde.net)
    - SillyTavern supports Stable Horde image generation out of the box.
