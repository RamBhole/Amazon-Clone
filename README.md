# 🛒 Amazon Clone

A front-end clone of Amazon's e-commerce interface, built with **React** and **Redux Toolkit**, styled with **Tailwind CSS**. Containerized with Docker and set up with a Jenkins + Terraform pipeline for CI/CD.

## 📖 About

This project recreates the look and core shopping experience of Amazon's storefront — product browsing, cart, and a responsive, modern UI — as a way to practice building a real-world, production-shaped React application (state management, routing, styling, and deployment tooling included).

> ⚠️ This is a personal/educational project and is not affiliated with, endorsed by, or connected to Amazon.com, Inc. in any way.

## ✨ Features

- Responsive UI built with Tailwind CSS
- Global state management via Redux Toolkit
- Client-side routing with React Router
- Image carousels/sliders via Swiper.js
- API requests handled with Axios
- Dockerized for consistent local & production builds
- CI/CD scaffolding with Jenkins + Terraform (`JENKINS-TF/`)

*(Update this list with the specific features your app implements — e.g. cart, checkout, search, product details, wishlist, etc.)*

## 🖥️ Demo

*(Add a live demo link here if you deploy it, e.g. to Vercel or Netlify)*

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Frontend | React 18 |
| State Management | Redux Toolkit, React-Redux |
| Routing | React Router v6 |
| Styling | Tailwind CSS |
| HTTP Client | Axios |
| UI Components | Swiper.js, Heroicons |
| Containerization | Docker |
| CI/CD | Jenkins, Terraform |

## 📂 Project Structure

```
Amazon-Clone/
├── JENKINS-TF/       # Jenkins pipeline & Terraform infra-as-code
├── img/               # Image assets
├── public/            # Static public assets
├── src/                # Application source code
├── Dockerfile          # Container build definition
├── package.json
└── tailwind.config.js
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later recommended)
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/RamBhole/Amazon-Clone.git
cd Amazon-Clone

# Install dependencies
npm install

# Start the development server
npm start
```

The app will be available at `http://localhost:3000`.

### Build for Production

```bash
npm run build
```

## 🐳 Running with Docker

```bash
# Build the image
docker build -t amazon-clone .

# Run the container
docker run -p 3000:3000 amazon-clone
```

## ⚙️ CI/CD

This project includes a `JENKINS-TF/` directory with Jenkins pipeline and Terraform configuration for automated builds and infrastructure provisioning.

*(Add a short note here on what the pipeline actually does — e.g. build & test on push, provision hosting infra, deploy to a server/cloud target — so reviewers know what to expect.)*

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

*(Add a license, e.g. MIT — or note if none is chosen yet)*

## 👤 Author

**Ram Bhole**
GitHub: [@RamBhole](https://github.com/RamBhole)

Find This repo for steps
```
https://github.com/RamBhole/Amazon-Clone
```
