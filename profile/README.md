[![Invoicerr](https://invoicerr.app/og.jpg)](https://invoicerr.app)

Open-source invoicing you can host yourself or use in our cloud: quotes, invoices, payments and the
paperwork that follows, including the e-invoicing rules of the country you bill from.

[Website](https://invoicerr.app) · [Cloud app](https://my.invoicerr.app) · [Documentation](https://docs.invoicerr.app) · [Source code](https://github.com/invoicerr-app/invoicerr)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://invoicerr.app/screens/dashboard-dark.webp">
  <img alt="The Invoicerr dashboard" src="https://invoicerr.app/screens/dashboard.webp">
</picture>

## What you get

- Quotes, invoices, credit notes, purchase orders, goods receipts, expenses and received invoices, all
  on one document engine.
- Payments, deposits, instalments, bank statement import with automatic matching, and online payment
  methods.
- Clients with their own portal, account statements and aged balance.
- An article catalogue with stock, project time tracking that turns into invoice lines, and recurring
  documents.
- PDF generation, e-invoice XML (Factur-X, UBL, CII, XRechnung, Peppol BIS, FatturaPA, FA(3)) and
  national transmission channels: PDP and Chorus Pro in France, KSeF in Poland, SdI in Italy.
- A legal archive per issued document, kept for as long as the country's own rule asks.
- E-mail/password, OIDC/SSO or API key sign-in, multi-company, role-based access, webhooks, a REST API,
  an MCP server and a plugin system.
- 18 interface languages, multi-currency, light and dark themes, installable as a PWA.

A country is data, not code. Germany, France, Italy, Poland and Portugal ship with their catalogues
filled in, and every fact carries the legal text it comes from. See the
[country support matrix](https://docs.invoicerr.app/docs/developer-guide/country-support).

## Two ways to run it

| | Cloud | Self-hosted |
| --- | --- | --- |
| Where | [my.invoicerr.app](https://my.invoicerr.app) | Your own server, with Docker or the Helm chart |
| Price | From $15 a month, 14-day free trial | Free, every feature, no seat limit |
| Start | [Start a free trial](https://my.invoicerr.app) | [Read the install guide](https://docs.invoicerr.app/docs/user-guide/docker-installation) |

```bash
docker pull ghcr.io/invoicerr-app/invoicerr:latest
```

## Repositories

| Repository | What it is |
| --- | --- |
| [invoicerr](https://github.com/invoicerr-app/invoicerr) | The application: NestJS backend, React frontend, documentation and Helm chart |
| [landing](https://github.com/invoicerr-app/landing) | The website at [invoicerr.app](https://invoicerr.app) |
| [ocr-image](https://github.com/invoicerr-app/ocr-image) | Self-hosted OCR service for received invoices, ocrmypdf and Tesseract, fully local |
| [plugin-example](https://github.com/invoicerr-app/plugin-example) | A minimal plugin to start from |

## Contributing

Issues and pull requests are welcome on the
[main repository](https://github.com/invoicerr-app/invoicerr/issues). The
[local development guide](https://docs.invoicerr.app/docs/developer-guide/local-development) covers the
setup and the test suites. Translations are managed on
[Weblate](https://hosted.weblate.org/engage/invoicerr/).

## License

Invoicerr is dual-licensed:
[AGPL-3.0](https://github.com/invoicerr-app/invoicerr/blob/dev/LICENSE) for open-source use, and a
[commercial license](https://github.com/invoicerr-app/invoicerr/blob/dev/LICENSE.COMMERCIAL.md) for
offering it as a paid service.
