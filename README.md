# AI PDF Analyser

![](https://github.com/Nariman-Mamutov-ew/AI-pdf-analyser/raw/main/preview.gif)

## Project Overview

**AI PDF Analyser** is a project designed to analyze PDF documents using various AI tools and services. The project leverages APIs from OpenAI, Unstructured, and Supabase for text extraction, processing, and storage.

## Features

- Extract and analyze text from PDF documents.
- Use OpenAI for generating insights and responses.
- Store and manage data using Supabase.

## Prerequisites

Make sure you have the following installed:

- Node.js (v14 or later)
- TypeScript

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd AI-PDF-Analyser
   ```

2. Install dependencies:

   ```bash
   yarn install
   ```

3. Create a `.env.development.local` file based on the provided `.env.example` and fill in your API keys and configuration details:

   ```bash
   cp .env.example .env.development.local
   ```

## Environment Variables

The following environment variables need to be set in your `.env.development.local` file:

```
UNSTRUCTURED_API_KEY=
OPENAI_API_KEY=
SUPABASE_PRIVATE_KEY=
SUPABASE_URL=
PORT=
UNSTRUCTURED_API_URL=
```

## Running the Project

To start the development server:

```bash
yarn run dev
```

The server will start on the port specified in your `.env.development.local` file.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://www.openai.com/)
- [Unstructured](https://unstructured.io/)
- [Supabase](https://supabase.io/)
