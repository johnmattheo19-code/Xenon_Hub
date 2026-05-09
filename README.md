# Xenon Raw Link Host

A sleek, futuristic web application for generating shareable raw links from code snippets. Perfect for sharing code without needing a GitHub gist or external service.

## Features

✨ **Fast & Simple** - Paste code, generate a link instantly  
🔐 **Client-side Encoding** - All encoding happens in your browser (no server tracking)  
💎 **Beautiful UI** - Glassmorphism design with cyan cyberpunk aesthetic  
📋 **Easy Sharing** - Copy or download your code effortlessly  
🌐 **No Dependencies** - Pure HTML, CSS, and JavaScript  

## How to Use

1. Visit the site and paste your code into the textarea
2. Click "Generate Raw Link"
3. Share the generated link with others
4. Recipients can view, copy, or download the code

## Files

- `index.html` - Main code hosting page
- `view.html` - Code viewer/decoder page
- `README.md` - This file

## Deployment

This site is deployed on GitHub Pages and can be accessed at:
- **Live URL**: https://johnmattheo19-code.github.io/Xenon_Hub/

## How It Works

1. **Encoding**: Your code is encoded using Base64 and passed as a URL parameter
2. **Sharing**: The generated link contains your entire code in the URL
3. **Decoding**: When someone opens the link, the code is decoded client-side
4. **Display**: Code is displayed with syntax highlighting and download options

## Privacy

- ✅ No server storage
- ✅ No tracking
- ✅ No cookies
- ✅ All processing happens in your browser
- ✅ Links are stateless and self-contained

## Tech Stack

- HTML5
- CSS3 (with Glassmorphism)
- Vanilla JavaScript (No frameworks)

## License

MIT - Feel free to use and modify

---

**Made with ❤️ by Xenon**