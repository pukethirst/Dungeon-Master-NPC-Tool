Dungeon Master NPC Helper

This application is designed to assist Dungeon Masters (DMs) in managing non-player characters (NPCs) and engaging in role-playing conversations. It utilizes the OpenAI GPT-3.5 language model to provide interactive and dynamic NPC interactions.

Compiled Version:
------------------
https://www.dropbox.com/scl/fi/u94ifkhkcr72wxey1z8sw/Dungeon-Master-NPC-Tool.exe?rlkey=yrscvgpaiypip6cptxzxfi9qo&dl=0

Usage:
-------

1. Run the "Dungeon Master NPC Helper.exe" executable.

2. Select a preset NPC personality:
   - Type "/npc" to enter the NPC selection menu.
   - Choose a number corresponding to the desired NPC from the list.
   - The selected NPC will become the active personality until changed.

3. Communicate with the assistant:
   - You can start typing messages to the assistant directly.
   - If an NPC is selected, the assistant will respond as that NPC.
   - If no NPC is selected, the assistant will respond as a regular chatbot(currently doesn't switch back, needs fixed).

4. Game Mechanics Questions:
   - The assistant can answer game mechanics questions for supported games.
   - Simply ask your question in the chat window, and the assistant will do its best to provide an answer based on its knowledge.

API Key Setup:
--------------

To use the OpenAI GPT-3.5 model, you need an API key. Here's how you can generate one:

1. Create an OpenAI account:
   - Go to the OpenAI website: [OpenAI Website](https://openai.com/)
   - Click on "Get Started" or "Sign up" to create a new account.
   - Follow the instructions to create your account.

2. Navigate to the API page:
   - Once you have an account, go to the OpenAI API page: [OpenAI API](https://platform.openai.com/account/api-keys)
   - Sign in using your OpenAI account credentials.

3. Generate an API key:
   - On the API page, you'll find the option to generate an API key.
   - Click on "Generate New Key" or similar.

4. Copy and save the API key:
   - Once the API key is generated, copy it to your clipboard.
   - Save the API key in a secure location, as it will be needed to run the application.

Note: Make sure to keep your API key confidential and do not share it with anyone.

Configuring the API Key:
------------------------

To configure the API key in the application:

1. Open the "Program Files/Dungeon Master NPC Tool/api.key" file in a text editor.

2. Replace the existing content with your API key.

3. Save the file.

Adding Custom NPCs:
-------------------

To add custom NPCs:

1. Open the "npcs.xml" file.

2. Follow the format of the existing NPCs to add new ones.

   Format:
   <npc>
       <name>NPC Name</name>
       <source>NPC Source, you can enter any specific instructions you want to this part to customize the characters further. Refer to the npcs.xml for further examples.</source>
   </npc>

Conversations with dynamically generated NPCs may be less reliable than those with predefined NPC descriptions.

Enjoy your Dungeon Master NPC Helper experience and have fun exploring the rich world of role-playing adventures!
