# 🎵 AI Music Festival Planner

> **Intelligent festival planning powered by CrewAI multi-agent orchestration**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-00C7B7?style=for-the-badge&logo=vercel)](https://crewai-ai-music-festival-planner.vercel.app/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react)](https://react.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

---

## 🌟 Overview

**AI Music Festival Planner** is a full-stack web application that demonstrates modern software engineering practices through an intelligent festival planning system. The application orchestrates multiple AI agents to generate comprehensive festival plans, including lineup scheduling, logistics coordination, budget allocation, and marketing strategy.

Built with **Next.js 16**, **React 19.2**, and **FastAPI**, the application showcases production-ready architecture, real-time AI interactions, and a polished user experience that adapts seamlessly across devices.

**[🚀 Try it live](https://crewai-ai-music-festival-planner.vercel.app/)**

---

## ✨ Key Features

### 🎯 Multi-Agent Planning System
- **CrewAI Orchestration**: Four specialized AI agents collaborate to create comprehensive festival plans
  - **Booking Agent**: Curates artist lineups and schedules
  - **Logistics Manager**: Handles operational planning and risk assessment
  - **Budget Analyst**: Optimizes financial allocations
  - **Marketing Crew**: Develops campaign strategies and sponsorship tiers

### 💬 Interactive AI Assistant
- **Context-Aware Chat**: Real-time streaming responses powered by OpenAI
- **Plan-Specific Guidance**: AI assistant references your festival configuration for personalized advice
- **Streaming Responses**: Word-by-word generation for smooth user experience

### 📊 Intelligent Plan Optimization
- **AI-Powered Suggestions**: Automated analysis of festival plans with actionable recommendations
- **Cost Optimization**: Identifies budget savings opportunities
- **Impact Prioritization**: Highlights high-impact improvements

### 🔄 Plan Comparison & History
- **Side-by-Side Comparison**: Compare multiple festival plans to evaluate different approaches
- **Version History**: Track iterations and improvements over time
- **Interactive Timeline**: Visualize plan evolution

### 📅 Interactive Schedule Management
- **Drag-and-Drop Scheduling**: Intuitive lineup adjustments with touch support
- **Conflict Detection**: Automatic identification of scheduling issues
- **Multi-Stage Coordination**: Manage complex multi-stage festival layouts

### 📤 Export & Share
- **Multiple Formats**: Export plans as JSON or PDF
- **Shareable Links**: Generate shareable plan references
- **Professional Documentation**: Production-ready plan documents

### 🎨 Modern UI/UX
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile
- **Dark/Light Mode**: System-aware theme switching
- **Smooth Animations**: Polished transitions and state-driven UI
- **Accessibility**: WCAG-compliant interface with proper ARIA labels

---

## 🏗️ Architecture

### Frontend Stack
- **Framework**: Next.js 16 (App Router)
- **UI Library**: React 19.2 with Material-UI (MUI)
- **Language**: TypeScript 5.0+
- **State Management**: React Hooks with Context API
- **Styling**: CSS Variables with theme-aware design system
- **Deployment**: Vercel (Edge Network)

### Backend Stack
- **Framework**: FastAPI (Python 3.11+)
- **AI Integration**: CrewAI + OpenAI (gpt-4o-mini)
- **Database**: Supabase (PostgreSQL with custom schema)
- **Cache/Queue**: Upstash Redis
- **Deployment**: Railway (Container-based)

### Key Architectural Decisions
- **Monorepo Structure**: Unified codebase with clear separation of concerns
- **API-First Design**: RESTful endpoints with streaming support
- **Type Safety**: End-to-end TypeScript with Pydantic models
- **Real-Time Updates**: Server-Sent Events for streaming responses
- **Optimistic UI**: Immediate feedback with background synchronization

---

## 🎨 Design Philosophy

The application follows a **command center** design philosophy, presenting complex planning data in an organized, actionable format. The UI emphasizes:

- **Clarity**: Information hierarchy guides users naturally
- **Efficiency**: Common actions are accessible within 1-2 clicks
- **Feedback**: Real-time status updates and progress indicators
- **Flexibility**: Multiple views and interaction modes for different workflows

The design system uses semantic color tokens, ensuring consistent theming across light and dark modes while maintaining excellent contrast and readability.

---

## 🚢 Deployment

### Frontend (Vercel)
- **Platform**: Vercel Edge Network
- **Build Command**: `npm run build`
- **Framework**: Next.js 16
- **Environment**: Production-ready with optimized bundles

### Backend (Railway)
- **Platform**: Railway (Container-based)
- **Runtime**: Python 3.11+
- **Builder**: Railpack
- **Auto-Deploy**: Git push triggers deployment

### Database & Cache
- **Database**: Supabase (PostgreSQL)
- **Cache**: Upstash Redis
- **Schema**: Custom `festivalplanner` schema with RPC functions

---

## 🛠️ Technologies Showcased

### Frontend Excellence
- **Next.js 16 App Router**: Server components, streaming, and optimized routing
- **React 19.2**: Latest features including improved hooks and concurrent rendering
- **TypeScript**: Full type safety from API to UI
- **Material-UI**: Professional component library with custom theming
- **Responsive Design**: Mobile-first approach with breakpoint optimization

### Backend Excellence
- **FastAPI**: Modern Python web framework with automatic OpenAPI docs
- **Async/Await**: Non-blocking I/O for optimal performance
- **Pydantic**: Runtime type validation and serialization
- **CrewAI**: Multi-agent orchestration framework
- **OpenAI Integration**: Streaming responses and structured outputs

### DevOps & Infrastructure
- **Monorepo Management**: Unified codebase with clear boundaries
- **Environment Configuration**: Secure secret management
- **CI/CD Ready**: Automated testing and deployment pipelines
- **Database Migrations**: Version-controlled schema changes
- **Health Monitoring**: Comprehensive status endpoints

---

## 🎯 Use Cases

### Festival Organizers
- **Initial Planning**: Generate comprehensive festival plans from basic requirements
- **Budget Optimization**: Get AI-powered suggestions for cost savings
- **Schedule Management**: Interactive lineup adjustments with conflict detection
- **Marketing Strategy**: Develop campaign timelines and sponsorship tiers

### Event Planners
- **Rapid Prototyping**: Quickly explore different festival configurations
- **Comparison Analysis**: Evaluate multiple planning approaches side-by-side
- **Documentation**: Export professional plan documents for stakeholders

### Developers & Engineers
- **Architecture Reference**: Study modern full-stack patterns
- **AI Integration**: Learn CrewAI and OpenAI best practices
- **TypeScript Patterns**: Explore type-safe API-to-UI data flow

---

## 🔐 Security & Privacy

- **Schema Isolation**: Custom database schema prevents public exposure
- **RPC Functions**: Secure data access without exposing internal structure
- **Environment Variables**: Sensitive credentials never committed
- **Input Validation**: Pydantic models ensure data integrity
- **Rate Limiting**: Redis-based rate limiting for API protection

---

## 📈 Performance

- **Frontend**: Optimized Next.js bundles with code splitting
- **Backend**: Async operations with connection pooling
- **Database**: Indexed queries with efficient schema design
- **Caching**: Redis for job state and rate limiting
- **CDN**: Vercel Edge Network for global content delivery

---

## 🤝 Contributing

This is a portfolio project demonstrating modern full-stack development practices. The codebase is structured to be:

- **Readable**: Clear naming conventions and documentation
- **Maintainable**: Modular architecture with separation of concerns
- **Extensible**: Easy to add new features or modify existing ones
- **Testable**: Comprehensive test coverage and testing utilities

---

## 📄 License

This project is part of a portfolio showcasing software engineering capabilities. All code is available for review and learning purposes.

---

## 👤 Creator

**Derril Filemon**  
*AI Engineer & Fullstack Developer*

- 🌍 **Location**: Gothenburg, Sweden
- 💼 **LinkedIn**: [linkedin.com/in/derril-filemon-a31715319](https://www.linkedin.com/in/derril-filemon-a31715319)
- 💻 **GitHub**: [@derril-tech](https://github.com/derril-tech)
- 📧 **Contact**: Available via LinkedIn

---

## 🌐 Live Application

**[🎵 Try AI Music Festival Planner →](https://crewai-ai-music-festival-planner.vercel.app/)**

Experience the full application with:
- Real-time AI agent orchestration
- Interactive plan generation
- Context-aware AI assistance
- Comprehensive festival planning tools

---

<div align="center">

**Built with attention to detail, optimized for performance, designed for users.**

[🚀 Live Demo](https://crewai-ai-music-festival-planner.vercel.app/) • [📚 Documentation](./docs/) • [💻 GitHub](https://github.com/derril-tech/crewai-ai-music-festival-planner-)

</div>
