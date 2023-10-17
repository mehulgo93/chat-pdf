
# Chat with any PDF 🌐

An intuitive platform where millions of students, researchers, and professionals can instantly answer questions and understand research with the power of AI.

![Chat with any PDF Screenshot](<img width="1728" alt="Chat With Any PDF" src="https://user-images.githubusercontent.com/111099204/275982612-4f7e6d2d-6e1b-4378-b83e-e41cad75a7f3.png">
)

## Features 🌟

- **Instant AI-powered Q&A with OpenAI:** Drop a PDF and get your questions answered using OpenAI's embeddings model `ada-002`.
- **Typescript & Next.js:** Built using the powerful combination of Typescript and Next.js for optimum performance and scalability.
- **Prisma Database:** Robust and type-safe database interactions using Prisma.
- **Pinecone Vector Embeddings:** Integrated with Pinecone for efficient vector search and embeddings.
- **Stripe Integration:** Seamless payment gateway integration using Stripe.
- **Vercel Deployment:** Deployed for high availability and performance on Vercel.

---

## Getting Started 🚀

### Prerequisites

- Node.js
- OPENAI API key
- Prisma CLI
- Pinecone API key
- Stripe API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/chat-pdf.git
```

2. Install the dependencies:
```bash
cd chat-pdf
npm install
```

3. Set up your environment variables:
```bash
cp .env.example .env.local
```
Then, fill in your Pinecone and Stripe API keys.

4. Run the development server:
```bash
npm run dev
```

Visit `http://localhost:3000` on your browser to view the app.

## Contribution 🤝

Feel free to contribute to this project. Open an issue first for major changes.

1. Fork the project
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request.

## License 📝

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


