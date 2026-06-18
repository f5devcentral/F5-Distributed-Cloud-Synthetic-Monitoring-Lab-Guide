# F5 Distributed Cloud Synthetic Monitoring Lab Guide


## 📋 Overview

This repository contains a comprehensive lab guide for **F5 Distributed Cloud Synthetic Monitoring**. The guide covers application observability and digital experience monitoring, helping teams ensure their applications are continuously available, performant, and measurable from the external user perspective.

## 🎯 Learning Objectives

- Create HTTP synthetic monitors for multiple endpoints
- Configure monitor validation using status codes and receive strings
- Run monitors from selected AWS and F5 Distributed Cloud locations
- Observe service-level health and identify intermittent behaviour
- Configure alert receivers and create alert policies
- Review TLS scores and detailed reports
- Create & observe DNS synthetic monitors

## 📚 Lab Contents

| Section | Description |
|---------|-------------|
| **Prerequisites** | Setting up MyF5 account and accessing the lab environment |
| **Section 1** | Configure HTTP Synthetic Monitors for Arcadia Finance |
| **Section 2** | Observe HTTP Synthetic Monitors and analyze health status |
| **Section 3** | Create Alert Policy for critical event notifications |
| **Section 4** | TLS Report analysis and security assessment |
| **Section 5** | DNS Monitor configuration and observation |

## 🏗️ Target Application

The lab uses **Arcadia Finance** as the target application with three services:

| Service | URL |
|---------|-----|
| Arcadia Main | https://arcadia.f5xc.cloud/ |
| Arcadia Trading | https://arcadia.f5xc.cloud/trading/login.php |
| Arcadia API | https://arcadia.f5xc.cloud/rest/api/v1 |

## 📁 Repository Structure

```
.
├── README.md                                          # This file
├── F5_Distributed_Cloud_Synthetic_Monitoring_Lab_Guide.md  # Full lab guide
├── images/                                            # Screenshots and diagrams
│   ├── image1.png
│   ├── image2.png
│   └── ... (59 images total)
└── NCC_Group_Bedrock_Letter_of_Engagement_Oct_10_2025_1 (1).docx  # Original document
```

## 🚀 Getting Started

1. **Prerequisites**: Ensure you have a MyF5 account
2. **Sign In**: Access https://account.f5.com/myf5
3. **Accept Invitation**: Check your email for lab invitation
4. **Follow the Guide**: Open `F5_Distributed_Cloud_Synthetic_Monitoring_Lab_Guide.md`

## 📖 How to Use This Guide

1. Open the main lab guide: [F5_Distributed_Cloud_Synthetic_Monitoring_Lab_Guide.md](F5_Distributed_Cloud_Synthetic_Monitoring_Lab_Guide.md)
2. Follow each section sequentially
3. Screenshots are provided for each step
4. Complete all exercises to gain hands-on experience

## 🔧 Key Features Covered

- **HTTP Synthetic Monitoring**: Monitor web application endpoints
- **Response Time Analysis**: DNS lookup, TCP connection, TLS handshake, server processing
- **Health Policies**: Configure thresholds and evaluation periods
- **Alert Management**: Email notifications for critical events
- **TLS Security Reports**: Analyze TLS scores and ratings
- **DNS Monitoring**: Monitor domain resolution health


## 📝 License

This lab guide is provided for educational purposes.

## 🤝 Contributing

Feel free to submit issues or pull requests to improve this lab guide.

---

**F5 Distributed Cloud** - Enabling digital experience monitoring and application observability.