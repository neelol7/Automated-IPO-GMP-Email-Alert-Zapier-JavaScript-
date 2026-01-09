# Automated-IPO-GMP-Email-Alert-Zapier-JavaScript-This project automates the collection of Indian IPO data and sends a daily email update with key details.

The automation is built using Zapier and a lightweight JavaScript parser to extract IPO information from a public IPO listing website and format it into a readable email.

Workflow Overview
A scheduled trigger runs daily via Zapier
IPO data is fetched using a Webhook (HTTP GET request)
Raw HTML is parsed using JavaScript to extract IPO table data
The parsed data is formatted into a clean text summary
An email with the IPO details is sent automatically via Gmail

Key Features
Fully automated end-to-end workflow
No manual tracking of IPO websites
Clean, readable email output
Easy to customize (filter by GMP, change schedule, add formatting)

Use Case
Designed for investors, traders, or enthusiasts who want quick daily IPO insights delivered directly to their inbox without manual effort.

