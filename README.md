# Bentley ProjectWise WSG Swagger UI 🛠️

This repo hosts an **interactive Swagger UI** powered by the OpenAPI spec for the Bentley ProjectWise Web Services Gateway (PW‑WSG). The interface enables you to explore every endpoint, see detailed schemas and error definitions, and understand how to integrate with ProjectWise—without running your own instance!

## 🔍 What’s Inside

- **Live endpoint browser** – view paths, HTTP methods, request/response schemas, headers, and error codes  
- **In-browser "try it out" mode** – test calls right in the UI (note: this is simulated— you'll need to copy the endpoint and use your own client like Postman, Apidog, or curl, and supply your own authentication)  
- **Complete PW‑WSG API reference** – covering repositories, schemas, domain classes, documents, workflows, and more

## 🚀 How to Use

1. Open the Swagger UI:  
https://cjandrew84.github.io/PW-WSG-API/
2. Browse the available endpoints and inspect request/response data directly in the UI.
3. Select an operation, click **"Try it out"**, and then copy the **curl** or endpoint.
4. Paste into your client (Postman, Apidog, or curl) and add your authentication headers (Basic Auth, OAuth, Mas-App-Guid, Mas-Uuid, etc.).
5. Send real requests to your own PW‑WSG deployment.

## 🧩 Why This Matters

The Swagger UI provides a reliable, self-service reference that makes it easy to explore PW‑WSG without needing to read static docs or guess payload formats. It’s especially useful for:

- Developers building integrations or automations
- Engineers troubleshooting request/response mismatches
- Anyone wanting a quick and interactive view of what the API supports

## ⚙️ Under the Hood

- Powered by the openly available OpenAPI spec (JSON/YAML)
- Hosted with Swagger UI on GitHub Pages
- No authentication handled here—use your own credentials and instances

## 💬 Feedback & Contributions

Let me know if you find endpoints missing, confusing, or want code examples/tests to speed up integration. **Submit GitHub issues** or open a **pull request** for improvements, or drop me a note via DM.

---

Built to help the Bentley community grow better tooling and usage around PW‑WSG. Enjoy! 💡
