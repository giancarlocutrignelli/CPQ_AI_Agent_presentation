# CPQ AI Agent
## Query-Centric RAG System for Enterprise Sales Automation

![CPQ AI Agent](./images/CPQ_AI_Agent_Workflow.jpg)

---

## 🎯 **Project Overview**

The **CPQ AI Agent** is an enterprise-grade conversational AI system that automates the complete Configure-Price-Quote (CPQ) sales process. Built on a query-centric RAG (Retrieval-Augmented Generation) architecture, it delivers intelligent, context-aware responses while eliminating manual overhead on Product Management teams.

### **Problem Solved**
- **Manual CPQ Process**: Time-intensive quote generation requiring extensive PM involvement
- **Resource Constraints**: Limited Product Management bandwidth for customer quotes
- **Inconsistent Quality**: Variable quote accuracy and completeness across sales teams
- **Slow Response Times**: Extended customer wait times impacting sales velocity
- **Scalability Issues**: Process bottlenecks that don't scale with business growth

### **Solution Delivered**
A conversational RAG-driven AI Agent managing the complete CPQ workflow with:
- ✅ **Automated Configuration**: AI-guided product selection and validation
- ✅ **Intelligent Pricing**: Dynamic pricing with market factors and volume projections
- ✅ **Query-Centric RAG**: Knowledge-driven responses with 35 verified operations
- ✅ **Enterprise Integration**: Full n8n v1.109 workflow automation
- ✅ **Zero PM Overhead**: Self-service quote generation without additional organizational burden

---

## 🏗️ **System Architecture**

### **Core Components**
- **Product Database**: Comprehensive catalog with configuration rules
- **Business Logic Engine**: 150+ PostgreSQL functions for CPQ operations
- **RAG AI Agent**: Query-centric knowledge system with conversation intelligence
- **n8n Integration**: Workflow orchestration and tool coordination

### **Technology Stack**
- **AI/ML**: OpenRouter chat models, Google Gemini embeddings
- **Database**: PostgreSQL with PGVector for semantic search
- **Workflow Engine**: n8n v1.109 with 8 specialized CPQ tools
- **Knowledge Base**: Query registry with 35 verified operations
- **Authentication**: Secure session management and validation

---

## 📁 **Repository Structure**

```
CPQ_AI_Agent/
├── README.md                                    # Project documentation
├── CPQ_AI_Agent_v2.html                        # Interactive presentation
└── images/                                     # Visual assets
    ├── RAG_Knowledge_Builder_Workflow.jpg      # RAG system architecture
    └── CPQ_AI_Agent_Workflow.jpg              # AI agent workflow
```

---

## 🚀 **Key Features**

### **Conversational Intelligence**
- **Natural Language Processing**: Intent recognition and query classification
- **Context-Aware Responses**: Maintains conversation state across CPQ phases
- **Error Recovery**: Automated handling of invalid inputs and edge cases
- **Multi-tool Orchestration**: Seamless integration of discovery, configuration, and pricing tools

### **RAG Knowledge System**
- **Query Registry**: 35 verified operations (Q000-Q034) with natural language mapping
- **Function Intelligence**: 150+ business functions with parameter validation
- **Conversation Patterns**: Intent classification and response templates
- **Vector Store**: PGVector-powered semantic search for contextual retrieval

### **CPQ Workflow Automation**
- **Phase Management**: Mandatory workflow progression through 9 CPQ phases
- **Product Discovery**: AI-guided family and configuration selection
- **Pricing Intelligence**: Volume-based pricing with 5-year projections
- **Quote Generation**: Complete ordering codes and business case analysis

---

## 🎬 **Interactive Demo**

The presentation includes a **live conversation demo** showcasing:
- Real-time customer interaction for industrial market CPQ
- Complete workflow from requirements gathering to quote generation
- Business case analysis with margin calculations
- Professional quote output with ordering codes

**View the presentation**: Open `CPQ_AI_Agent_v2.html` in your browser for the full interactive experience.

---

## 🔧 **Technical Implementation**

### **n8n Workflow Integration**
Enhanced for n8n version 1.109 with:
- Modern node architecture and procedures
- Automated RAG knowledge building
- Session management and validation
- Multi-tool coordination and error handling

### **Query-Centric Architecture**
```
User Input → Intent Classification → Query Registry → Function Execution → Response Generation
```

### **Supported Operations**
- **Session Management**: Customer profiling and requirement gathering
- **Product Discovery**: Family selection and compatibility checking
- **Configuration**: Hardware selection and validation
- **Software Selection**: Bundle discovery and compatibility
- **Service Configuration**: Professional services and support options
- **Pricing Calculation**: Volume-based pricing with compound factors
- **Quote Generation**: Complete ordering resolution and documentation

---

## 🛠️ **Getting Started**

### **Prerequisites**
- n8n v1.109 or higher
- PostgreSQL with PGVector extension
- OpenRouter API access
- Google Gemini API for embeddings

### **Quick Setup**
1. Clone this repository
2. Review the presentation for complete system overview
3. Follow n8n workflow deployment guides
4. Configure database connections and API keys
5. Initialize RAG knowledge base using the builder workflow

---

## 📧 **Contact & Support**

**Project Author**: Giancarlo Cutrignelli  
**Email**: giancarlo.cutrignelli@gmail.com

For questions about implementation, customization, or enterprise deployment, please reach out directly.

---

## 📄 **License**

This project is proprietary software designed for enterprise CPQ automation. Contact the author for licensing and usage terms.

---

*Built with ❤️ for enterprise sales teams who deserve better than manual CPQ processes.*