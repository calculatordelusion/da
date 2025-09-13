# DeepSeek Deutsch Chatbot

A modern AI chatbot interface supporting DeepSeek V3 and DeepSeek R1 models with file upload capabilities.

## 🌟 Features

- **Dual Model Support**: Switch between DeepSeek V3 and DeepSeek R1
- **File Upload**: Support for PDF and Word document processing
- **Modern UI**: Clean, responsive interface with dark/light themes
- **WordPress Integration**: Easy embedding via WordPress plugin
- **German Language**: Native German language support

## 🚀 Live Demo

Visit the live chatbot: [Your deployment URL will be here]

## 🛠️ Technologies Used

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, shadcn/ui components
- **File Processing**: PDF.js, Mammoth.js
- **API**: OpenRouter API integration
- **Deployment**: Netlify/Vercel

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/calculatordelusion/da.git
cd da
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## 🔧 Configuration

The chatbot uses OpenRouter API to access DeepSeek models. 

### For Local Development:
1. Get API keys from [OpenRouter.ai](https://openrouter.ai)
2. Create a `.env` file in the project root:
```env
VITE_DEEPSEEK_V3_API_KEY=your-openrouter-api-key
VITE_DEEPSEEK_R1_API_KEY=your-openrouter-api-key
```
3. Start the development server

### For Vercel Deployment:
1. Add environment variables in Vercel dashboard:
   - `VITE_DEEPSEEK_V3_API_KEY`
   - `VITE_DEEPSEEK_R1_API_KEY`

## 📱 WordPress Integration

This project includes a WordPress plugin for easy integration:

1. Install the DeepSeek WordPress plugin
2. Configure the chatbot URL in WordPress settings
3. Use shortcode `[deepseek_chatbot]` in posts/pages

## 🌐 Deployment on Vercel

### Quick Deploy
1. Fork this repository: `https://github.com/calculatordelusion/da`
2. Connect to Vercel and import the project
3. Add environment variables (see Configuration section)
4. Deploy!

### Manual Deployment
1. Run `npm run build`
2. Upload `dist` folder contents to your hosting

### Vercel Configuration
The project includes `vercel.json` with optimal settings for Vite deployment.

## 🔒 Security

- Client-side API key management
- Secure iframe embedding
- HTTPS-only deployment
- No API keys stored in code

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support and questions, please open an issue in this repository.

---

**Built with ❤️ for the AI community**
