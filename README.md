```markdown
# pollinations-ai-image-generator

A small React app that uses the free Pollinations image generation endpoint to produce images from text prompts.

Website: https://pollinations.ai/

How it works
- The app constructs an image URL using the prompt and loads it directly from Pollinations' image service:
  `https://image.pollinations.ai/prompt/<encoded-prompt>`
- No API key is required for the simple public endpoint used in this demo.

Run locally
1. npm install
2. npm start
3. Open http://localhost:3000

Notes
- The Pollinations image endpoint can return large images; add caching or size limits as needed for production.
- If Pollinations changes their public endpoint or usage policy, update the code accordingly.

Screenshot
<img width="699" height="407" alt="Screenshot 2025-10-25 114919s" src="https://github.com/user-attachments/assets/6e31618d-8ed2-4423-9120-e3c7f13a04de" />





```


https://github.com/pollinations/pollinations/issues/4768
