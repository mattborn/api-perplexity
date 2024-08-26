## Dev locally

```
npm i
npm run dev
```

## Deploy

```
gcloud functions deploy perplexity \
--allow-unauthenticated \
--no-gen2
--runtime=nodejs18 \
--update-env-vars PERPLEXITY_API_KEY=PASTE_KEY_HERE \
--trigger-http
```
