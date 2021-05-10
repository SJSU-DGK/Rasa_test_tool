# AI Test Tool Chatbot

SJSU Undergraduated Senior Project of Software Engineering

## Features
- This is a chatbot to support [AI Test Tool](http://3dmodeler.us-east-2.elasticbeanstalk.com/)
- Understanding the AI Test Tool
- Getting started with AI Test Tool
- Answering some FAQs around AI Test Tool
- Directing technical questions to specific documentation
- Handling basic chitchat
## Overview of the files

    .
    ├── actions                  # Custom action for chatbot
    ├── data                     # Training data
    │   ├── nlu.yml              # NLU training data, Intents
    │   └── rules.yml            # Special rules
    │   └── stories.yml          # Chat stories
    ├── images                   # Images for custom chat
    ├── model                    # Automated tests
    ├── result                   # NLU pipeline and policy ensemble
    ├── tests                    # Tools and utilities
    └── domain.yml               # The domain file, including bot response templates
    └── config.yml               # Training configurations for the NLU pipeline and policy ensemble
    └── README.md

## Installation

Install
```
pip3 install -U pip
pip3 install rasa
```

To chat with the chatbot, use command
```
rasa shell
```

For detail installation, please refer to Rasa Installation at this [link](https://rasa.com/docs/rasa/installation/)
 * [Windows Guide](https://www.youtube.com/watch?v=GlR60CvTh8A)
 * [MacOS Guide](https://www.youtube.com/watch?v=fqzsE70Rvr0)
 * [Ubuntu Guide](https://www.youtube.com/watch?v=tXiYJM2vGJk)

## Contributors
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/SangT"><img src="https://avatars.githubusercontent.com/SangT?v=3?s=100" width="100px;" alt=""/><br /><sub><b>Grace To</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/duytranvinh"><img src="https://avatars.githubusercontent.com/duytranvinh?v=3?s=100" width="100px;" alt=""/><br /><sub><b>Duy Tran Vinh Thai</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/khamtran411"><img src="https://avatars.githubusercontent.com/khamtran411?v=3?s=100" width="100px;" alt=""/><br /><sub><b>Kham Tran</b></sub></a><br /></td>
  </tr>
</table>
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your own Branch
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request


## Credits
This bot is created based on the [Rasa Open Source](https://github.com/RasaHQ/rasa)
