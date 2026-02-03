# Plant Store Documentation Demo

This repository contains a demo documentation site built with **Fern** for a Demo Company called **Plant Store**.  
The goal of this project is to showcase a clean, easy-to-use API documentation experience that could be shared with real customers.

The site includes:
- A styled landing page
- Interactive API reference generated from OpenAPI
- Code samples and examples
- A sandbox environment for testing requests
- Webhook payload documentation

📂 GitHub Repository:
https://github.com/ChadMathlin24/fern-plantstore-demo

🌐 Published Docs Site:
https://chad-mathlin-demo.docs.buildwithfern.com

This README explains what was built and how to run it locally.

---

## 🚀 Getting Started

### 1. Install the Fern CLI

To work with this project locally, you’ll need the Fern CLI installed:


"npm install -g fern-api"

This will allow you to use Fern in the terminal to check and publish your demo site.

Optional: Make Sure Fern Is Up to Date

If you already have Fern installed, it’s a good idea to make sure you’re on the latest version:

npm update -g fern-api



### 2. Clone the Repository
git clone https://github.com/ChadMathlin24/fern-plantstore-demo.git
cd fern-plantstore-demo

## 3. Run the Documentation Locally

Navigate into the fern directory and start the local development server:

fern docs dev

## 4. Validate the Configuration

To confirm everything is configured correctly, run:

fern check


Assignment Requirements Completed

-Webhook payloads display correctly

-Python code sample added for POST /plant

-Sandbox environment configured

-Custom examples added with x-fern-examples

-Multiple server environments supported

-Styling updated to match the sample design



## 5. Publishing

To preview or publish the documentation site, use:

fern generate --docs


🎇Thanks for checking out the demo!
