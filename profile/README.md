<p align="center">
  <img src="https://github.com/PlatinPay/.github/blob/main/horizontal-logo-text.png?raw=true" alt="PlatinPay's Logo"/>
</p>

## Showcase
[Showcase video (we worked hard on it!)](../platinpay-showcase.mp4)

[![Watch the video](https://github.com/user-attachments/assets/89858d85-fedd-4942-8d83-6085cea981c9)](https://github.com/user-attachments/assets/89858d85-fedd-4942-8d83-6085cea981c9)

## Try it yourself!
- [Frontend, with an example shop](https://platinpay.cc/store/main)

- Minecraft server, connected to this example shop: platinpay.cc

- [Link to the Discord server containing the testing bot (may be necessary so the bot can DM you)](https://discord.gg/javgnZTmGs)

## Preface

Both @iUnstable0 and I (@DatCodeMania) have ran Minecraft servers before. Monetization is what keeps a server alive, but
it always seems to be so painful... When I ran my Minecraft server, I resorted to using Tebex. That was... not great.
Lots of their services were unmaintained, and the 'taxing' model was completely unfair. Moreover, custom HTML cost a
ton! Minecraft servers are already hard enough to keep afloat, I don't need a greedy company stealing my money!

Now, it's been a while since either of us ran a Minecraft server. But, the Minecraft payment service situation has stuck
with us to this day. So, we decided to make PlatinPay.

PlatinPay is an OSS alternative to Tebex and other such payment services. It is currently a WIP, but we aspire to use
Stripe for payment processing, as Stripe has some of the lowest fees in this field. If you selfhost the only additional
fees you will pay will be to Stripe (and, if applicable, your bank)

### NOTE: Not all features are implemented yet, and not every feature listed is finalized. This is a WIP project.

## PlatinPay's features:

- Create different types of products, such as one-time purchases, subscriptions, consumable items, and more!
- Integration with Discord for role rewards and communication  (for example, instead of setting up a mail server to send emails to your players, you can just send them a DM on Discord!)
- Easily create automations with our powerful, easy-to-learn, and extensible framework (e.g., when a purchase is made,
  do X and Y).

- High customizability to fulfill your pleasurable needs
- Secure backend-service communications, using asymmetric Ed25519 signing, and other security options such as IP whitelisting.
- A beautiful, Nord-themed UI (this is the default, but feel free to add alternatives and submit PRs)

## This project is far from done. Our Roadmap consists of:

- Porting backend to Go (or Rust)
- Affordable hosting solutions
- Better system infastructure

## Directory
[platinpay-frontend](https://github.com/PlatinPay/platinpay-frontend) - [@iUnstable0](https://github.com/iUnstable0)

[platinpay-backend](https://github.com/PlatinPay/platinpay-backend)- [@iUnstable0](https://github.com/iUnstable0)

[platinpay-minecraft](https://github.com/PlatinPay/platinpay-minecraft) - [@DatCodeMania](https://github.com/DatCodeMania)

[platinpay-discord](https://github.com/PlatinPay/platinpay-discord) - [@DatCodeMania](https://github.com/DatCodeMania)

This project is licensed under the [GNU AGPL-3.0](../LICENSE) License. See the `LICENSE` file for details.

**DISCLAIMER: This project is currently not ready for production usage. It is a work-in-progress.**
