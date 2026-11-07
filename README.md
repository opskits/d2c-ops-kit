# D2C Ops Kit

Free tools for **D2C brand owners**: the day-to-day operations of selling online, such as shipping labels, customer messages, reviews and stock.

Part of **[opskits](https://github.com/opskits)**: free, open-source (MIT) tools built from real day-to-day operations. Every tool lives in its **own repository**, so you can use just the one you need.

## Tools

| Tool | What it does | Status |
|---|---|---|
| [d2c-label-relay](https://github.com/opskits/d2c-label-relay) | Shipping-label workflows: retry-safe label creation, cheapest-quote pick, merged label PDFs, private links, email/WhatsApp delivery adapters | Early (28 offline tests; carrier integration pending) |

More tools will be listed here once they have working code and tests.

Status words are honest: *early* means tested on synthetic data only; nothing is called live or production-ready without proof.

## Using one tool
1. Open the tool's repository from the table.
2. Follow its README (each has its own setup, tests and version).
3. Keep your own settings and keys in your own private repository or secret store. Never commit them.

## Rules for every d2c tool
- Free under the MIT licence. No paid plans.
- Only reusable code and synthetic examples. No real customer data, labels, credentials or account configuration.
- Tests must work offline and never buy shipping, send messages or touch live accounts.
- New tools are added only when there is working code, tests and documentation.

## Contributing
Bug reports and pull requests are welcome in each tool's repository. Changes go through a pull request and review before they are merged.

## Licence
MIT, see [LICENSE](LICENSE).
