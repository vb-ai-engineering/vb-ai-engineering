<p align="center">
  <img src="./assets/tenor.gif" alt="future-pixel gif">
</p>
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=40&pause=1000&color=F7F7F7&background=000000F8&random=false&width=750&height=70&lines=Welcome+%F0%9F%91%8B+My+name+is+Vincent" alt="Typing SVG" />
  </a>
</p>
A new chapter begins ! Welcome to my new GitHub profile, where I showcase my most impactful projects and continue building AI-powered products and intelligent systems.
 
This space brings together selected work from my AI engineering journey, focusing on LLMs, autonomous agents, robotics, and modern software architectures.
 
I'm an AI Engineer and Full-Stack Developer passionate about building intelligent systems that solve real-world problems.
 
My work focuses on large language models (LLMs), autonomous multi-agent systems, Retrieval-Augmented Generation (RAG), cloud-native AI architectures, and modern full-stack development.
 
I'm currently working on integrating AI into humanoid robots, combining LLMs, computer vision, ROS2, autonomous navigation, and voice interaction to create intelligent robotic systems capable of interacting with people.
 
I'm fascinated by the idea of giving intelligence a physical body. Every new breakthrough in AI makes me wonder the same thing: what happens when we let these models leave the screen and interact with the real world?
 
One of the proudest moments of my journey was watching our robot walk through Paris Charles de Gaulle Airport during a live demonstration for airport executives. Seeing something that had existed only as lines of code suddenly navigating a busy international airport and interacting with real people was surreal. Moments like this are exactly why I love engineering.
 
<p align="center">
  <a href="https://youtube.com/shorts/nSDWjJWwXQ0?feature=share">
    <img src="assets/demo_cdg_image.jpg" alt="Humanoid Robot Demonstration at Paris Charles de Gaulle Airport" width="250">
  </a>
</p>
<p align="center">
  <em>▶ Click the image to watch the full demonstration.</em>
</p>
 
## 🌱 What I'm Working On
 
Currently exploring the frontiers of Agentic AI and Humanoid Robotics.
 
Explore some projects below to get a feel for my skills.
 
 
## 🤖 AI & Agentic Systems
 
### [Digital Twin V2 - AWS Cloud Architecture](https://d2s1zfamsgsifg.cloudfront.net/) ☁️
Link of the repository : https://github.com/vb-ai-engineering/digital-twin-V2
 
The production-grade evolution of my Career Digital Twin, now fully deployed on AWS with a professional cloud architecture. Features a serverless backend (AWS Lambda + FastAPI), a REST API (API Gateway), global HTTPS delivery (CloudFront), conversation memory persistence (S3), and AI responses powered by AWS Bedrock. Infrastructure managed entirely with Terraform across 3 isolated environments (dev, test, prod), with a fully automated CI/CD pipeline via GitHub Actions using keyless OIDC authentication — no AWS credentials stored anywhere.
 
### [Price Prediction - LLM + Deep Neural Network](https://github.com/vb-ai-engineering/Amazon-Price-Predictor-Fine-Tuning-LLM-Deep-Neural-Network-Pipeline) 🏆
 
An end-to-end ML pipeline predicting Amazon product prices from raw text descriptions, combining LLM-based preprocessing with a custom deep neural network. Uses Groq to summarize 820,000+ product listings into structured 5-field summaries via async batch jobs, then trains a 10-layer ResNet-style DNN (4,096 neurons, 100M+ parameters) with PyTorch. Remarkably, the fine-tuned LLaMA 3.2 model achieves higher accuracy than frontier LLMs on this specific benchmark — highlighting how domain-specific fine-tuning can outperform the world's most advanced general-purpose models. Features multi-process data loading, log-scale price normalization, and CUDA/MPS/CPU auto-detection.
 
### [Price Watch Multi-Agent Platform](https://github.com/vb-ai-engineering/price-watch-multi-agent-platform) 🔍
 
A LLM-orchestrated multi-agent platform combining RAG over 800K scraped Amazon products, a fine-tuned LLaMA 3.2 deployed on a cloud GPU, and a deep residual neural network to estimate true product value on the fly. Seven specialized agents collaborate fully autonomously, from RSS feed scraping to crafting and delivering push notifications with zero human intervention. Built with Python, OpenAI, ChromaDB, PyTorch, Modal, and Gradio.
 
### [Alex - the Agentic Learning Equities eXplainer](https://github.com/vb-ai-engineering/Alex---the-Agentic-Learning-Equities-Explainer) 📈
 
A production-grade AI financial advisor built entirely on AWS serverless infrastructure. Six specialized agents collaborate to deliver portfolio analysis, retirement projections, and dynamic chart generation: a Financial Planner orchestrates the pipeline via SQS, while a Researcher agent browses financial websites autonomously every 2 hours via a Playwright MCP server, embedding findings into S3 Vectors for semantic retrieval. Built with the OpenAI Agents SDK, AWS Bedrock (Nova Pro), SageMaker serverless embeddings, Aurora Serverless v2, and a Next.js frontend with Clerk authentication. Full observability via Langfuse, infrastructure managed end-to-end with Terraform.
 
▶️ [Watch demo](https://drive.google.com/file/d/1Qe9NpkxsY-7UPKQbOUvDrSZR9QQI8FQt/view?usp=sharing)
 
### [Autonomous AI Trading Simulation](https://github.com/vb-ai-engineering/Autonomous-Trading-Simulation) 💹
 
An experimental simulation where multiple AI agents inspired by iconic investors like Buffett, Soros, Dalio, and Wood develop and evolve their own trading strategies. Each agent leverages MCP servers, real-time Polygon market data, Brave Search, and persistent memory to adapt over time. Built with Python 3.12+, Gradio, OpenAI Agents, Plotly, and multi-model orchestration (GPT, DeepSeek, Gemini, Grok).
 
▶️ [Watch demo](https://drive.google.com/file/d/17wud_t8fTiFNZBx5Hn02OoVFxCJR-yGR/view)
 
### [Finance Ally — AI Trading Workstation](https://github.com/vb-ai-engineering/AI-Trading-Workstation) 📈
 
A production-grade AI-powered trading terminal inspired by Bloomberg terminals. Streams live prices for 33 tickers across 6 sectors via Server-Sent Events, lets users trade a simulated $10K portfolio with instant market-order fills, and integrates an LLM chat assistant that can analyze positions, suggest trades, and execute them autonomously. Features a compact grid watchlist with sector filtering, live P&L area chart, portfolio heatmap, candlestick charts with MA/RSI overlays, and real-time market breadth. Built entirely by orchestrated AI agents as a capstone for an agentic AI coding course. The backend runs on FastAPI with Python/uv for high-performance async endpoints, persisting data in SQLite, while the frontend is a Next.js 19 static export written in TypeScript and styled with Tailwind CSS v4 — all charts powered by Lightweight Charts v5 for smooth, low-latency rendering. AI inference is routed through LiteLLM to OpenRouter backed by Cerebras hardware for near-instant responses. The entire stack ships as a single Docker container on one port.
 
▶️ [Watch demo](https://drive.google.com/file/d/1gxxYV38R6E_3Rfu3YcnH3zO5eW3wTNzU/view?usp=sharing)
 
### [Advanced RAG System with Evaluation Framework](https://github.com/vb-ai-engineering/Advanced-RAG-System-with-Evaluation-Framework-and-Pro-Implementations) 📚
 
An advanced Retrieval-Augmented Generation system built in Python and Gradio, featuring an evaluation framework to measure performance using MRR, nDCG, and keyword coverage. Demonstrates how to combine large language models with document retrieval, custom prompts, and systematic self-evaluation for high-quality answer generation.
 
### [4 Agents AI Engineering Team](https://github.com/vb-ai-engineering/4-Agents-Engineering-Team) 👨‍💻
 
A collaborative AI-driven software engineering team powered by CrewAI, where four specialized agents (tech lead, backend dev, frontend dev, and QA engineer) work together to design, build, test, and demo a complete Python project. Fully modular and configurable, each agent uses a tailored language model to optimize its task. Includes a Gradio demo interface and automated unit testing.
 
▶️ [Watch demo](https://drive.google.com/file/d/17ePDdkq0TVcTeYgG-axHndiNdVlBoeM5/view)
 
### [AI Sidekick Assistant](https://github.com/vb-ai-engineering/Langraph-AI-Sidekick-Assistant) 🔗
 
An experimental AI assistant capable of organizing knowledge and actions as interconnected graphs. Combines web search, automated browsing, code execution, file handling, email writing and reading, and knowledge retrieval from Wikipedia, all while self-evaluating and self-correcting its answers over time.
 
▶️ [Watch demo](https://drive.google.com/file/d/1q4y5yFmMHtf4N3U7WncXWXR6v8bpbm9k/view)
 
### [Agents AI Factory](https://github.com/vb-ai-engineering/agents-army-factory-autogencore) 🏭
 
An experimental platform for creating autonomous AI agents that can brainstorm, generate Python code, and collaborate in real-time. Features a Creator agent capable of dynamically generating new agents, inter-agent messaging, and customizable objectives.
 
⚠️ Experimental. ▶️ [Watch demo](https://drive.google.com/file/d/1QUplfJMUBH3g-4LIjkz3D-XM2dhRPoo9/view)
 
### [Prelegal - AI-assisted SaaS platform for drafting professional French legal documents](https://github.com/vb-ai-engineering/prelegal) ⚖️
 
An end-to-end legaltech SaaS application designed to dynamically generate and customize 12 types of French legal templates (such as NDAs, cloud contracts, and GDPR agreements) through an interactive, real-time AI interface. Combines a FastAPI (Python) backend with an adaptive multi-stage Docker setup and a static Next.js 16/Tailwind CSS v4 frontend, executing inference via LiteLLM, OpenRouter, and OpenAI's GPT-o3. Features a live side-by-side legal document preview that populates dynamically as users chat step-by-step with the AI assistant, along with complete state persistence via standard JWT authentication and SQLite. Leverages custom multi-platform shell scripts and native browser-based PDF rendering to guarantee high-quality formatting and pixel-perfect document export across macOS, Linux, and Windows ecosystems.
 
### [AI Cybersecurity Analyzer](https://github.com/vb-ai-engineering/AI-Cybersecurity-Analyzer-Agent) 🔐
 
An AI-powered web application that analyzes Python code for security vulnerabilities. Combines OpenAI for intelligent analysis, a Semgrep MCP server for static scanning, a React/Next.js frontend, and a FastAPI backend, fully containerized with Docker and deployed on both Azure Container Apps and Google Cloud Run using Terraform.
 
### [AI Deep Research](https://github.com/vb-ai-engineering/AI-DeepResearch-App) 🔬
 
A multi-agent research application powered by OpenAI's API and Gradio. Performs parallel searches, synthesizes the results into a well-structured markdown report, and sends it via email using Resend. Not deployed online to avoid OpenAI API costs.
 
▶️ [Watch demo](https://drive.google.com/file/d/1v7ZVjc3eCQ7Z6bjfRF2HYZhjHBgFwspS/view)
 
### [StockPicker AI Investment Research Assistant](https://github.com/vb-ai-engineering/CrewAI-StockPicker-MultiAgents-System-For-Investements) 📊
 
Coordinates multiple specialized agents working hierarchically to identify trending companies, analyze their financials, and produce smart stock recommendations delivered via mobile push notifications. Features contextual memory layers using SQLite and Google Generative AI embeddings for semantic understanding and relevance.
 
### [Crew-AI Debate System](https://github.com/vb-ai-engineering/Crew-AI-Debate-System) 🎙️
 
A multi-agent debate simulation powered by CrewAI. Features two AI debaters and a judge over a motion. Supports any combination of models (Claude, ChatGPT, DeepSeek) with a judge that picks a winner based on logic and clarity.
 
---
 
## 🌐 Full-Stack Engineering
 
### [FullStack E-Shop project in React](https://cerulean-melba-c14f75.netlify.app/)
 
A complete e-commerce application built with React, TypeScript, Firebase, Redux, and Stripe. Includes full authentication via OAuth, product browsing, cart management, and secure payment processing, all tested with Jest.
 
### [Example of Front-end UX Designs](https://space-showcase-lime.vercel.app/)
 
Creative landing page built with Next.js, TypeScript, Tailwind CSS, featuring an interactive spaceship pilot to explore animated previews of web app categories like hotel booking, travel planning, and dashboards, showcasing UX/UI skills.
 
### [Netflix Clone project in Next.js](https://netflix-portfolio-nine.vercel.app/)
 
Featuring Next.js 15, TypeScript, Tailwind CSS, TMDB API, responsive design, server components, optimized images, and dynamic content fetching.
 
---
 
### 👯 Always open to collaborating on interesting projects.
 
### 📫 Let's Connect!
 
- [LinkedIn](https://www.linkedin.com/in/vincent-b-289a2a184/)
- Email: vincentbmmrtpro@gmail.com
Feel free to reach out if you have any questions, suggestions, or just want to say hi! 😊
 
<br/><br/>
 
<!--
<div align="center">
    <img src="https://github-trophies.vercel.app/?username=VinceBmmrt&theme=radical&no-frame=true&margin-w=4&rank=SECRET,SSS,SS,S,AAA,AA,A,B&row=2&column=7" alt="vb-ai-engineering's GitHub Trophies" />
</div>
-->
<br/><br/>
 
<!-- <div align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VinceBmmrt&layout=compact&theme=radical&langs_count=20" alt="Top Langs" />
</div> -->
 
<br/><br/>
 
<div align="center">
<p align="center">
  <img src="https://24.media.tumblr.com/65032a3e0a3aaffd4f336bfa8ce0b65f/tumblr_mh0j8p3MeO1qagmleo1_250.gif" alt="image">
</p>
</div>
<div align="center">
Always learning, always experimenting, always building.
</div>
<br/><br/>
 
<p align="center">
  <img src="https://steamuserimages-a.akamaihd.net/ugc/831329771678673548/49C66203D4484F804076D9E21376CE55F8BC2DFE/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false" alt="test">
</p>
