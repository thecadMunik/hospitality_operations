
# 📊 Hospitality Operations Intelligence Initiative

### Highlighting Analytics for Operational Optimization

This project analyzes customer support operations to identify inefficiencies in response time, inquiry volume, and operational cost, while establishing a data-driven baseline for future AI adoption.

🛠️ Tools Used: Google Sheets, Looker Studio
📁 Dataset: Operational Support Data (Agent logs, Cost metrics, Inquiry patterns, Knowledge base logs)

## 🧠 Project Goal

In this project, I aimed to evaluate how efficiently support operations are functioning by analyzing performance across time, scale, and cost dimensions. The goal was to identify bottlenecks, quantify their impact, and build a baseline to support evaluation of the Intelligent Travel Concierge initiative.

## 🔍 Business Understanding

I began by understanding the core operational challenges within customer support. The system is experiencing increasing demand, which leads to slower response times, high escalation and transfer rates, growing inquiry volumes, and rising operational costs. These challenges highlight the need for a structured, data-driven assessment.

## 📊 Data Understanding

To get a complete view of operations, I worked with multiple datasets including agent performance logs, cost efficiency metrics, inquiry volume patterns, and knowledge base and escalation logs. Each dataset provided insight into a different part of the support process, from performance tracking to cost impact and operational complexity.

## 🧹 Data Preparation

I used Google Sheets to clean and transform the data. I created key calculated fields such as first response time, total resolution time, total handle time, and SLA breach indicators. I also derived additional metrics including escalation rate, extra time added due to escalation, repetitive inquiry rate, and an automation impact score of 49.92%.

## 📌 Analysis & Insights

### ⏱️ Time Bottlenecks

From the analysis, I observed clear delays in response performance. First response time averages around 10 minutes, while SLA breach rate is high at about 71.8%. Response times also increase during peak hours, showing that the system struggles to maintain service levels as demand rises.

### 📈 Scale Bottlenecks

The demand analysis shows significant pressure on operations. Total inquiries reached 120,000, with over 60% classified as repetitive. Inquiry volume peaks during morning and evening hours, indicating predictable demand spikes. A large portion of workload is therefore repetitive and structured.

### 🔄 Process Inefficiencies

I identified inefficiencies in how tickets are handled. Around 32% of tickets require escalation, and escalation adds approximately 12 minutes to resolution time. Multiple transfers further increase handling complexity, reducing efficiency and slowing down service delivery.

### ⚙️ Operational Effort

From a workload perspective, agent utilization rate is 79%, and average handle time is 15.7 minutes. This indicates that agents are operating at a high capacity, with limited flexibility to handle increases in demand.

### 📚 Knowledge Base Dependency and Automation

There is a strong reliance on the knowledge base during ticket handling. Over 70% of tickets require knowledge base support, with usage rates across categories ranging between 89% and 95%. Agents also spend an average of 3.65 minutes searching for information, contributing to longer handling times.
Automation Impact Score is 49.92%, meaning nearly half of support handling effort is tied to repeatable tasks.

### 💰 Financial & Cost Impact

The financial analysis shows the scale of operational inefficiencies. Total operational cost is approximately $9.3 million, with an average cost per inquiry of $662. Missed revenue opportunities amount to about $501,000, while an additional $9,000 in upsell revenue was not captured during customer interactions. Repetitive inquiries account for a significant share of total operational cost, meaning a large portion of spending is tied to predictable and repetitive tasks.

## ✅ Key Findings

Based on the analysis, I identified several key insights. Response delays are strongly linked to peak demand periods. A large portion of workload is driven by repetitive inquiries. Escalations and transfers significantly extend resolution time, while knowledge dependency increases handling effort. High operational costs are largely driven by repetitive and inefficient processes, and missed revenue opportunities highlight gaps in service efficiency.


## 📊 Dashboard Development

To present these insights, I built an interactive dashboard using Looker Studio. The dashboard tracks response time and SLA performance, inquiry volume trends, escalation patterns, cost and revenue metrics, and knowledge base usage. This provides a clear and continuous view of operational performance.

## Dashboard Preview 
![Dashboard Overview](https://github.com/thecadMunik/hospitality_operations/blob/main/images/dashboard1.png)

![Cost and Operational Efficiency](https://github.com/thecadMunik/hospitality_operations/blob/main/images/dashboard2.png)


## 🤖 AI Automation Opportunities

| Problem Identified                      | AI Automation Opportunity      |
| --------------------------------------- | ------------------------------ |
| High repetitive inquiries (cost driver) | AI chatbot for common requests |
| High KB dependency                      | AI knowledge assistant         |
| High handle time                        | AI response suggestions        |
| High escalation rate                    | AI sorting and routing         |
| Peak-hour delays                        | AI self-service support        |

## 🧠 Final Conclusion

Through this project, I was able to identify key inefficiencies across time, scale, and operational processes, as well as their direct financial impact. A significant portion of operational cost is driven by repetitive inquiries, escalations, and manual knowledge retrieval. By quantifying these challenges and linking them to cost and revenue outcomes, this project establishes a strong baseline for evaluating AI adoption and improving both operational efficiency and financial performance.

