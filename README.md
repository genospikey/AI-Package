## Welcome to the AI server installation manual! 

Tired of wasting time on tedious tasks? Tired of staring at spreadsheets like they're the plague? Well, my friend, you're in luck! This manual will guide you through the effortless installation of your very own AI server, capable of superhuman feats like automatically generating dank memes and predicting the weather with 100% accuracy. 

**Step 1: Buy a PC**

Get ready to unleash your inner AI wizard! To run your AI server, you'll need a powerful PC with at least 2000 bucks. It's like buying a magic wand that can do wonders.

**Step 2: Install Windows**

Windows is the operating system that will power your AI server. It's like installing the software on your magic wand.

**Step 3: Install Docker Desktop**

Docker is like a magical portal that allows you to run complex AI models without needing to learn how to code. Simply download it from the internet and follow the instructions. It's like installing a genie, but without the annoying lamp.

**Step 4: Run the AI server**

Once the docker-compose.yaml file is set up, run the following command in the base folder:

```
docker-compose up
```

This will set up the following magical creatures:

- **Caddy:** A HTTPS server reverse proxy that will handle incoming requests.
- **Valkey:** An open-source in-memory storage system.
- **Ollama:** An AI language model.
- **Searxing:** A meta search engine that will power your AI server's search functionality.
- **Open Webui:** An interface for creating and chatting with AI models.

**Step 5: Install Automatic1111**

Automatic1111 is a stable diffusion server that will generate stunning images. To install it, run the following command in the same folder:

```
docker compose --profile download up --build
```

**Step 6: Connect Open Webui to Searxing and Automatic1111**

Open Webui needs to be connected to Searxing and Automatic1111 to function properly. You can do this by following these steps:

- In Open Webui, navigate to the Admin Panel.
- Select the Settings tab.
- Under Web Search, set the Web Search Engine to Searching and the Searxing Query URL to `http://127.0.0.1:8080`.
- Under Images, set the Image Generation Engine to Automatic1111 and the Automatic111 Base URL to `http://host.docker.internal:7860`.

**With these steps completed, you have the server, image generation, and search capabilities ready to go!**

**Hit me up on Facebook at jeremy.reyes.75, Instagram and TikTok at jeremyelguapo, or send a smoke signal for further assistance.**