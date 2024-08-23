# Serve Ollama model publicly

Once you docker compose is up, access the model like
`curl -X POST https://$NGROK_DOMAIN/api/generate -d '{ "model": "llama3", "prompt":"Hello" }'`
