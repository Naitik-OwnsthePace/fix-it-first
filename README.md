# Fix It First 🌿 — Circular Engine Dashboard

An AI-powered circular economy dashboard designed to reduce e-waste and consumer discard rates. By analyzing item condition, usage history, and fault descriptions, **Fix It First** calculates real-time repairability scores, carbon emission savings, financial payback periods, and step-by-step restoration roadmaps using the Google Gemini API.

---

## Key Features

- **Dynamic Repairability Scoring**: Evaluates the feasibility of repair vs. replacement based on condition, age, and defect severity.
- **Carbon & Cost Intelligence**: Quantifies avoided carbon footprint ($CO_2e$) and estimated savings compared to buying new.
- **AI-Powered Diagnostics**: Integrates Gemini for domain-specific troubleshooting steps and part recommendations.
- **Session Vault**: Retains an active history of evaluated items for comparison and export.

---

## Tech Stack

- **Framework**: React 18 with TypeScript
- **Bundler**: Vite
- **Styling**: Tailwind CSS
- **AI Engine**: Google Gemini API (`@google/genai`)
- **Icons**: Lucide React

---

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- A Gemini API Key from [Google AI Studio](https://aistudio.google.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Naitik-OwnsthePace/fix-it-first.git
   cd fix-it-first