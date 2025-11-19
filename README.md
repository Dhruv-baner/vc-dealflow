# Venture Dealflow

An automated intelligence platform for UK venture capital deal sourcing and market analysis. Combines authoritative data sources with AI-powered curation to surface high-potential early-stage companies before they become obvious opportunities.

### The Challenge

Venture capital firms face three core problems in deal sourcing:

- **Information Overload**: Thousands of UK companies incorporate annually, making manual tracking impossible at scale

- **Late Discovery**: By the time companies appear in traditional databases, they're already widely known and competition intensifies

- **Signal vs Noise**: Distinguishing genuine momentum from vanity metrics requires deep context that doesn't exist in structured data alone

### Our Approach

We address these challenges through three layers of intelligent filtering:

- **Comprehensive Data Collection**: Aggregate signals from Companies House, funding announcements, hiring patterns, and product launches to build a complete view of the UK tech ecosystem
- **AI-Powered Curation**: Deploy specialized agents to match entities across sources, interpret signal quality, and generate investment narratives from raw data
- **Verified Intelligence**: Every featured company undergoes manual validation to ensure accuracy, with transparent confidence scoring on all metrics

### Technical Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| Data Sources | Companies House API, Tech.eu, Sifted, LinkedIn | UK company and funding data |
| Processing | Python, pandas, SQLite | Data cleaning and aggregation |
| AI Agents | Claude API | Entity matching, signal interpretation, narrative generation |
| Visualization | Streamlit | Interactive dashboard and reports |
| Automation | GitHub Actions | Scheduled data refreshes |
| Hosting | Streamlit Cloud | Free public deployment |

### Project Structure

The platform is built across eight focused modules:

**Data Collection**: Ingests data from Companies House API, funding news sources, YC databases, job boards, and Product Hunt

**Entity Resolution**: Matches companies across disparate sources and builds a master database with confidence-scored records

**Signal Processing**: Calculates hiring velocity, funding trajectories, and product momentum indicators

**Market Intelligence**: Generates sector trends, geographic analysis, and comparative benchmarking

**Company Curation**: Scores and selects featured companies with AI-generated investment narratives

**Visualization**: Builds interactive dashboard with sector heatmaps, company profiles, and filtering

**Automation**: Schedules weekly updates and generates email digests

**Validation**: Tests accuracy against ground truth and measures error rates



### AI Agent Architecture

Three specialized agents handle tasks where context and nuance matter:

**Entity Matching Agent**: Resolves company identity across data sources by understanding name variations, trading names, and corporate structures that rule-based matching misses

**Signal Quality Agent**: Evaluates whether observable changes (hiring, product launches, funding rumors) represent genuine momentum or misleading signals

**Narrative Generation Agent**: Synthesizes structured data into concise investment briefs that explain why a company merits attention right now

**NOTE: This dealflow project is in the production stage. Any results are a beta version** 