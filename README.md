# 📈 Real-Time Intelligence with Microsoft Fabric

This repository documents the completion of a hands-on lab exploring the **Real-Time Intelligence** capabilities in Microsoft Fabric using live **stock market stream data**.

## 🎯 Purpose of the Lab

The objective of this lab was to demonstrate how Microsoft Fabric can be used to build real-time analytics solutions by integrating:
- Eventstream ingestion
- KQL-based querying and analysis
- Real-time dashboards
- Alerting and automation via Activator

The scenario used live streaming stock data to simulate how real-time business events can be captured, stored, visualized, and acted upon.

## 🧠 What I Learned

Throughout this lab, I developed an end-to-end understanding of Fabric’s real-time analytics stack, specifically:

- **Creating a Workspace and Real-Time Environment**  
  Set up a Fabric workspace and launched the Real-Time Hub to connect to a live stock data feed.

- **Ingesting Streaming Data Using Eventstream**  
  Connected to a public stock market sample stream and created an eventstream pipeline to ingest the real-time data.

- **Storing Streamed Data in an Eventhouse**  
  Routed the incoming eventstream data into a **KQL database table** for further analysis and querying.

- **Querying Real-Time Data with KQL**  
  Used **Kusto Query Language** (KQL) to perform exploratory queries on the live data, including time filtering and aggregations such as average stock price per symbol.

- **Visualizing Data with Real-Time Dashboards**  
  Created a real-time dashboard that visualizes average stock prices using a dynamic, auto-refreshing chart.

- **Creating Alerts with Activator**  
  Configured **alerts and triggers** using Fabric’s Activator to automatically detect significant changes in stock prices and notify users via email.

## ✅ Outcome

At the end of this lab, I had a fully functioning real-time analytics solution that included:

- A connected live data stream
- Storage in an eventhouse table
- A visual dashboard updated in near real-time
- Alerting mechanisms for threshold-based changes

This exercise reinforced how Microsoft Fabric enables seamless **stream processing, monitoring, and action** — making it ideal for operational analytics, fraud detection, system monitoring, and IoT scenarios.

## 🤝 Let’s Connect

If you’re working on real-time data pipelines or building streaming analytics solutions with Microsoft Fabric, I’d love to connect and exchange ideas.  
Reach out via [LinkedIn](https://www.linkedin.com/in/eyilan/) — let’s talk streaming, KQL, and Fabric!
