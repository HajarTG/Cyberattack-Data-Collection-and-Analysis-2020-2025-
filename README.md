#  Cyberattack Data Collection and Analysis (2020-2025)

##  Project Overview

**Objective:** Collect and analyze monthly data on cyberattacks from 2020 to 2025, focusing on:

- **Affected devices or systems** (IoT, Industrial, SCADA, PLC)
- **Number of incidents** per month/year
- **Estimated financial impact** in USD
- **Types of attacks** (Ransomware, DDoS, Data Breaches, etc.)
- **Data breaches** and their severity

**Target Sector:** Industrial & Energy (IoT / Embedded Systems)


---

##  Project Goals

1. **Data Collection**: Gather cyberattack data from multiple sources
2. **Analysis**: Identify trends and patterns over time
3. **Visualization**: Create interactive dashboards and charts
4. **Insights**: Understand evolution of cyber threats across sectors

##  Data Sources

- **AlienVault OTX** - Threat intelligence pulses
- **Shodan** - Exposed IoT devices
- **AbuseIPDB** - Malicious IP reports
- **VirusTotal** - Malware indicators
- **Censys** - Network infrastructure data
- **Historical Data** - 2020-2024 incidents (simulated)

##  Project Structure

```
security/
├── README.md
├── requirements.txt
├── .env (for API keys)
├── cyberattack_analysis_2020_2025.ipynb
├── cyberattacks_2020_2025_complete.csv
├── cyberattacks_report_2020_2025.txt
├── executive_summary_2020_2025.txt
├── yearly_statistics_2020_2025.csv
├── top_threats_2020_2025.csv
└── top_devices_2020_2025.csv
```

##  Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd security
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure API keys** (optional)
   - Create a `.env` file with your API keys
   - The notebook works with simulated data if no API keys are provided

##  Usage

1. **Open the Jupyter notebook**
   ```bash
   jupyter notebook cyberattack_analysis_2020_2025.ipynb
   ```

2. **Run all cells** to generate the complete analysis

3. **View generated files**:
   - `cyberattacks_2020_2025_complete.csv` - Complete dataset
   - `cyberattacks_report_2020_2025.txt` - Detailed report
   - `executive_summary_2020_2025.txt` - Executive summary

##  Features

- **Historical Data Generation**: Realistic cyberattack data for 2020-2025
- **Temporal Analysis**: Monthly and yearly trends
- **Financial Impact**: Cost analysis in millions USD
- **Interactive Visualizations**: Plotly charts and dashboards
- **Statistical Analysis**: Correlations and predictions
- **Comprehensive Reporting**: Executive summaries and detailed reports

##  Key Insights

- **Growth Trend**: Average annual growth of ~25% in cyberattacks
- **Most Common Attacks**: Ransomware, DDoS, Data Breaches
- **Most Targeted Devices**: SCADA Systems, PLC Controllers, IoT Sensors
- **Financial Impact**: Billions in estimated damages
- **Geographic Distribution**: Global impact with regional variations

##  Visualizations

- Evolution of cyberattacks over time
- Financial impact analysis
- Attack type distribution
- Device vulnerability heatmaps
- Geographic impact maps
- Interactive dashboard

##  Predictions 2025

- **Expected Incidents**: ~500 incidents
- **Financial Impact**: $2.5B+ in damages
- **Critical Incidents**: 50+ high-severity attacks
- **New Threats**: AI-generated attacks, quantum threats

##  Recommendations

1. **Industrial System Security**
   - Network segmentation
   - Encrypted communications
   - Multi-factor authentication

2. **Monitoring & Detection**
   - 24/7 SOC for industrial sector
   - Continuous IoT monitoring
   - Real-time alert systems

3. **Training & Awareness**
   - Industrial threat training
   - Regular attack simulations
   - Cybersecurity best practices

4. **Incident Management**
   - Specific incident response plans
   - Business continuity procedures
   - Crisis communication

5. **Testing & Audits**
   - Regular penetration testing
   - Annual security audits
   - Vulnerability assessments

##  Generated Files

- `cyberattacks_2020_2025_complete.csv` - Complete dataset (2000+ incidents)
- `cyberattacks_report_2020_2025.txt` - Comprehensive analysis report
- `executive_summary_2020_2025.txt` - Executive summary
- `yearly_statistics_2020_2025.csv` - Annual statistics
- `top_threats_2020_2025.csv` - Top 20 threat types
- `top_devices_2020_2025.csv` - Most targeted devices


