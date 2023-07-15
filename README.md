This is a heavily modified fork version of tools leveraging ChatGPT based on [PDL](https://github.com/ZhangHanDong/prompt-description-language), thanks to [ZhanghanDong](https://github.com/ZhangHanDong)'s work.

Each folder is a small experiment and role play.

How to use:
Copy the contents of the xxx.pdl file to the ChatGPT input.

Of course, I (GPT) can explain the commands in English:

1. `/help`: Lists all the commands, descriptions, and rules I recognize.
2. `/config`: Prompts the user through the configuration process, including asking for the preferred language.
3. `/role`: Lists all available roles.
4. `-r`: A secondary command, specifying a role to speak.
5. `/lang`: The default target output language. Usage: `/lang [lang]`. E.g: `/lang Chinese`.
6. `/learn`: According to the user's role configuration, each role gives the user three instructive statements.
7. `/ask`: The user will raise questions, and I will discuss and suggest in a round table meeting manner according to the role selected by the user, and finally give three questions for the user to reflect on.
8. `-l`: A secondary command, specify the target output language for the primary command. For example: `/ask -l <Target> <TEXT>`.

Enjoy!
