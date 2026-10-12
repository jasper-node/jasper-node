# Vulnerability Disclosure Policy

Keeping your control logic, the JasperX platform and your controller's local web interface secure is important to us. For any security-related questions, feel free to contact us at [info@controlx.au](mailto:info@controlx.au).

## Our Infrastructure
We depend on the following sub-processors. Note that developed logic and AI chat prompts are sent up to our servers for JasperX management functionality and to power all of JasperNode's AI features.

* **Google Cloud Platform (GCP)** _Sees and stores data_: Our infrastructure is primarily hosted on GCP. Most of our servers are in Australia (Sydney), with some load balancing servers allocated by GCP automatically in other regions.

* **Anthropic** _Sees prompts and script code when we use it_: We may use Anthropic's Claude models to give AI responses. Anthropic's commercial API does not use your data to train models by default.

* **xAI** _Sees prompts and script code_: We use xAI's Grok models to give AI responses. xAI does not use your data to train models. It deletes it when the response is delivered or one hour after the request is processed, whichever comes first, and keeps no copy. xAI processes requests outside Australia, including in the United States.

* **Google Workspace** _May store data for debugging_: We use Google Workspace to collaborate. We may send snippets of prompts in our internal emails for debugging.

* **Stripe** _Sees no code data_: We use Stripe to handle billing. Stripe will store your personal data (name, credit card, address).



## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via email at [info@controlx.au](mailto:info@controlx.au).

We commit to acknowledging vulnerability reports immediately, and will work to fix active vulnerabilities as soon as we can. We will publish resolved vulnerabilities in the form of security advisories on our GitHub security page. Critical incidents will be communicated both on the GitHub security page and via email to all affected users.

We appreciate your help in making JasperNode more secure for everyone. Thank you for your support and responsible disclosure.
