# E-Invoice.be 🧾 - hey there 👋

**Switch to e-invoicing, keep your workflow**

Welcome to the e-invoice.be GitHub organization! We're building the simplest way for businesses worldwide to use e-invoicing.

## 🚀 About Us

At e-invoice.be we believe that compliance shouldn't mean complexity. Our platform allows businesses to:

- **Use simple and straightforward solutions** - We offer a simple app and powerful Peppol API
- **Keep working as they always have** - Continue using Excel, Word, PDF, or any familiar tools
- **Receive e-invoices in their email** - No new inbox to check, everything comes to your existing email
- **Start for just €1** - Pay only for what you use with transparent per-invoice pricing
- **Stay compliant** - Automatically handle all Peppol requirements and technical complexity

## 🎯 Mission

Our mission is to make the switch to e-invoicing as painless as possible for businesses of all sizes. We handle the technical complexity so entrepreneurs can focus on what they do best - euh everything else!

## 🛠️ What We Build

### Core Platform
- **Peppol Access Point** - Certified Peppol service provider
- **Document Processing Engine** - Automatic conversion from common formats (PDF, Excel, Word) to compliant UBL
- **Fraud Detection System** - Built-in security to protect against invoice fraud
- **Company Search** - Enhanced business directory to check Peppol readiness

### Developer Tools
- **E-Invoicing API** - Simple REST API for developers and ERP integrations
- **SDKs** - Native libraries for JavaScript/Node.js, Python, Ruby, Java, and PHP
- **No-code Integrations** - Zapier app and n8n nodes for workflow automation
- **OpenAPI Specification** - Complete API documentation with code generation support

## 🔧 Technical Stack

Our platform is built with modern, scalable technologies:

- **Infrastructure**: European data centers with 99.5% uptime
- **Security**: Bank-grade verification and fraud protection
- **Compliance**: Full Peppol certification and UBL 2.1 support
- **Data Protection**: GDPR compliant, data stays in Europe 🇪🇺

## 📚 APIs & SDKs

- `e-invoice-ts` - JavaScript/Node.js SDK: https://www.npmjs.com/package/e-invoice-api
- `e-invoice-py` - Python SDK: https://pypi.org/project/e-invoice-api/
- `e-invoice-rb` - Ruby SDK: https://rubygems.org/gems/e-invoice-api
- `e-invoice-api-php` - PHP SDK: https://packagist.org/packages/e-invoice/e-invoice-api
- `e-invoice-api-java` - Java SDK (Coming Q4 2025)

## 🚀 Quick Start

### For Businesses
1. Sign up at [e-invoice.be](https://app.e-invoice.be/register?ref=github-biz) for €1
2. Complete company onboarding
3. Start receiving e-invoices in your email immediately

### For Developers
1. Get your API key from the [developer portal](https://app.e-invoice.be/register?ref=github-dev)
2. Install our SDK:
   ```bash
   npm install e-invoice-api
   # or
   pip install e-invoice-api
   ```
3. Send your first e-invoice:
   ```javascript
   import EInvoice from 'e-invoice-api'
   
   const client = new EInvoice({
     apiKey: process.env.E_INVOICE_API_KEY,
     environment: 'development'
   })
   
   const invoice = await client.documents.create({
     // Your invoice data as simple JSON
   })
   ```

## 📖 Documentation

- **API Documentation**: [api.e-invoice.be/docs](https://api.e-invoice.be/docs)
- **User Guide**: [api.e-invoice.be/docs/guide](https://api.e-invoice.be/docs/guide)
- **Developer Portal**: [api.e-invoice.be](https://api.e-invoice.be)

## 🌍 E-Invoicing Compliance

E-invoicing mandates are rolling out globally, with many countries requiring businesses to adopt digital invoicing standards. We're here to make this transition seamless:

- **No workflow changes** - Keep using your current tools and processes
- **Automatic compliance** - We handle all technical requirements
- **Gradual adoption** - Start with receiving, upgrade to sending when needed
- **Cost-effective** - Pay only for what you use, starting at €1

## 🤝 Contributing

We welcome contributions from the community! Please see individual repository contribution guidelines for specific projects.

### General Guidelines
- Follow our coding standards and best practices
- Include comprehensive tests for new features
- Update documentation for any API changes
- Ensure all changes maintain backward compatibility

## 📄 License

Our open-source projects are licensed under the Apache License 2.0 unless otherwise specified. See individual repository LICENSE files for details.

## 📞 Support

- **Technical Support**: Create an issue in the relevant repository
- **Business Support**: [support@e-invoice.be](mailto:support@e-invoice.be)
- **Documentation**: [api.e-invoice.be/docs](https://api.e-invoice.be/docs)

## 🎉 Community

Join our community of developers and businesses making e-invoicing simple:

- **Website**: [e-invoice.be](https://e-invoice.be)
- **API Portal**: [api.e-invoice.be](https://api.e-invoice.be)

---

**Looking for a Peppol API?** Start today at [e-invoice.be](https://app.e-invoice.be/register?ref=github) for just €1.

*e-invoice.be - Because e-invoicing should be simple, not complicated.*


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
