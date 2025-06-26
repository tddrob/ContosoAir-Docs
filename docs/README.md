# 🌍 ContosoAir Wiki

Welcome to the ContosoAir Wiki — the centralized documentation hub for all things related to the ContosoAir travel platform. This wiki is designed to serve engineers, designers, product managers, operations teams, and business stakeholders with the knowledge they need to build, maintain, and evolve our product.

---

## ✈️ What Is ContosoAir?

**ContosoAir** is a next-generation, cloud-native travel booking platform that allows customers to search, compare, and book flights, hotels, car rentals, and destination experiences across the globe. Think of us as the intelligent, scalable version of Expedia or Kayak, built on modern cloud infrastructure and infused with AI.

Our mission: _“Make travel smarter, more personalized, and effortlessly connected.”_

### Key Product Capabilities

- Unified booking engine for flights, hotels, cars, and experiences
- Real-time inventory sync with partner providers
- Dynamic pricing and availability based on supply and demand
- Personalized recommendations powered by machine learning
- Intuitive UI/UX designed for mobile and web users
- Travel wallet, loyalty tracking, and trip management

---

## 🧭 Documentation Index

This wiki is organized into several major sections to help you find what you need quickly.

### 1. **Product Overview**
- Business goals, user personas, and high-level product capabilities
- Key KPIs and success metrics
- Supported languages, regions, and currencies

### 2. **System Architecture**
- High-level system diagram
- Microservices overview
- Data flow and service communication patterns
- Key design principles (e.g., fault tolerance, scalability, modularity)

### 3. **Platform Components**
- **Booking Service**: Handles reservation logic
- **Inventory Aggregator**: Syncs with GDS, OTA, and partner APIs
- **Pricing Engine**: Calculates real-time pricing with promotions
- **User Profile Service**: Manages user preferences, loyalty, and personalization
- **Notifications Service**: Email, SMS, and in-app notifications

### 4. **Dev Guide**
- Setting up the local development environment
- Environment configurations: `dev`, `test`, `stage`, `prod`
- Azure DevOps pipelines, test environments, and deployment patterns
- Coding standards and PR requirements
- Secrets management and config best practices

### 5. **APIs & Integrations**
- Public API catalog: Flights, Hotels, Bookings, Payments
- Partner API authentication (OAuth2, API keys, rate limits)
- Swagger and Postman collections
- Webhooks and event-driven architecture
- Third-party integrations (e.g., Stripe, Twilio, Amadeus, Sabre)

### 6. **AI & Personalization**
- How ContosoAir uses ML to power:
  - Search ranking
  - Dynamic pricing
  - Travel suggestions
  - Churn prediction
- Models currently deployed and pipelines used (MLflow + Azure ML)
- Data labeling and feedback loops

### 7. **Operations & Monitoring**
- Logging: OpenTelemetry, Application Insights
- Monitoring dashboards (Grafana, Azure Monitor)
- Alerting policies and on-call rotation
- Disaster recovery procedures and failover strategy

### 8. **Security & Compliance**
- Authentication and authorization (OAuth2, JWT)
- Role-based access control (RBAC)
- GDPR, CCPA, and PCI compliance checklists
- Secure handling of PII and payment data
- Vulnerability management and threat modeling

### 9. **Support & Smart Knowledge**
- Support chatbot (CopilotAir) powered by RAG pipelines
- Workflow for handling incoming support issues
- Approval pipeline for adding new knowledge chunks
- Teams support integration (auto-responder setup)

---

## 🛠️ Quick Start for Developers

```bash
# Clone the platform repository
git clone https://github.com/contosoair/platform.git

# Move into the core project directory
cd platform

# Install dependencies
npm install

# Start local services with Docker
docker-compose up

# Run tests
npm test
