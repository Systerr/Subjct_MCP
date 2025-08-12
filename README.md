# 🏆 MachineTalents Hackathon — Winning Project (July 2025)

This repository contains our **winning project** from the [MachineTalents Hackathon](https://lu.ma/ibaiz50k), held in July 2025.  

We achieved **1st place in the MCP category** — [see the announcement on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7356811648583503872/).  

---

## 👥 Team

- [Andrei Lahonou](https://www.linkedin.com/in/andrey-logunov/)  
- [Raj P](https://www.linkedin.com/in/rajanpatel/)  
- [Tom Nash](https://www.linkedin.com/in/tomnash01/)  

---

Claude example with mcp server:
![Working with mcp from claude](assets/claude.png)

Cline example with mcp server
![Demo](assets/clineDemo.gif)



## Objective
Develop a Model Context Protocol (MCP) server using SUBJCT's provided API endpoints to demonstrate capabilities and solve real-world content optimisation challenges via an agentic delivery method.

See: https://modelcontextprotocol.io/introduction

## Scope
- Use Subjct's API endpoints to build a functioning MCP server within the 4-hour timeframe.
- Focus on transforming content from a CMS (e.g., Shopify or WordPress) for optimisation:
  - Add relevant links, tags, and schema.
  - Integrate knowledge graph data.
  - Ensure compatibility with existing SUBJCT functionalities.

## Requirements
- Utilise provided Swagger documentation and test account access.
- Deliver a proof of concept showcasing seamless API integration.
- Highlight how the solution can optimise articles for increased LLM mentions.
- Show the MCP server plugged in to Claude, ChatGPT or Google ADK to demonstrate functionality

## Resources Provided
- Test account credentials. Sign up using this link.
- SUBJCT API documentation (Swagger): https://api.subjct.ai/docs/swagger/
- After signing up, access the keys in the config area.
- [MCP Server Quickstart](https://modelcontextprotocol.io/quickstart)
- [Using LLMs to generate MCP server](https://modelcontextprotocol.io/llms-txt)
- [MCP + Google ADK](https://modelcontextprotocol.io/clients/google-adk)

## Deliverables
- A working MCP server prototype.
- Documentation and a brief presentation demonstrating functionality.
- Suggestions for scaling the solution or next steps.

## Evaluation Criteria
- Functionality and completeness of the MCP server.
- Effective utilisation of SUBJCT API.
- Potential for real-world application and scalability.
- Creativity and problem-solving approach.
- Going the extra mile to illustrate the power of MCP servers when bundled together (e.g. a demo illustrating your SUBJCT MCP server combined with Shopify/Wordpress CMS MCP server within Claude/ChatGPT)

## Development Notes

### Example Article for Testing
Use the following article for testing: https://emmajaneknight.com/blogs/news

### API Documentation
SUBJCT Swagger Documentation: https://api.subjct.ai/docs/swagger/ 

### Use Case Journey 


* https://emmajaneknight.com/blogs/news/juicing-the-2025-creative-comfort-zone

1. Send the article 

### Pitch Deck 


Certainly! Here is a concise 3-slide pitch deck summary for the hackathon idea integrating SUBJCT with MCP for content optimization:

### **Slide 1: Problem & Opportunity**

**Problem:**  
- E-commerce and content-heavy Shopify/WordPress sites struggle to consistently optimize internal linking, metadata, and schema at scale.  
- Manual SEO enhancements are time-consuming, error-prone, and hard to maintain.  
- AI-driven platforms (ChatGPT, Claude, Google ADK) need enriched, well-structured content context for better responses.

**Opportunity:**  
- Automated content optimization + AI-context integration can boost search rankings, user engagement, and AI interactions.  
- Using SUBJCT’s API combined with the emerging Model Context Protocol (MCP), we can build a scalable, automated server to transform CMS content seamlessly.

### **Slide 2: Solution Overview**

**What We Built:**  
- A **Model Context Protocol (MCP) Server** leveraging SUBJCT’s API to analyze and enrich Shopify/WordPress articles in real-time.  
- Automatically injects relevant internal links, tags, schema markup, and knowledge graph data—enhancing SEO and content discoverability.  
- Fully compatible with SUBJCT’s existing features and extendable to any CMS platform.

**How It Works:**  
1. Content pulled from CMS → sent to MCP server.  
2. MCP server calls SUBJCT API for content analysis & enrichment.  
3. Enriched content with optimized links & metadata delivered back for publishing/AI processing.  
4. MCP server plugs into LLM platforms (Claude, ChatGPT, Google ADK) for smarter AI responses.

### **Slide 3: Impact & Next Steps**

**Impact:**  
- Saves hours of manual SEO and content optimization work.  
- Increases organic traffic and customer engagement through better site architecture.  
- Enhances AI-driven tools’ effectiveness using richer, structured content context.  
- Demonstrates future-proof integration between CMS, SEO automation, and AI ecosystems.

**Next Steps:**  
- Scale MCP server to support multiple CMS integrations and features (e.g., multilingual support).  
- Develop UI tools for non-technical users to customize linking rules and schema presets.  
- Expand AI integration by building demo apps with ChatGPT and Google ADK using MCP.  
- Explore commercializing as a Shopify App or WordPress Plugin to streamline adoption.

## Install

* https://emmajaneknight.com/blogs/news/juicing-the-2025-creative-comfort-zone

```json
    "subjct": {
      "command": "{FULL_PATH}/node",
      "args": ["{FULL_PATH}/index.ts"],
      "env": {
      }
    }



