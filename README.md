# Pantheon Edge Integrations Drupal SDK

[![Unsupported](https://img.shields.io/badge/pantheon-unsupported-yellow?logo=pantheon&color=FFDC28)](https://github.com/topics/unsupported?q=org%3Apantheon-systems "Unsupported, e.g. a tool we are actively using internally and are making available, but do not promise to support") ![Packagist Version](https://img.shields.io/packagist/v/pantheon-systems/edge-integrations-drupal-sdk) ![MIT License](https://img.shields.io/github/license/pantheon-systems/edge-integrations-drupal-sdk)

Welcome to the Pantheon Edge Integrations Drupal SDK!

This repository serves as a one-stop shop for integrating your Drupal site on Pantheon with our Edge Integrations toolset.

## Setup

Adding Edge Integrations support to your project is simple.

<!-- Dev note: This isn't actually possible yet until we publish this repository on Packagist. -->

To get started, all you need to do is to add this repository as a dependency:

```bash
composer require pantheon-systems/edge-integrations-drupal-sdk
```

That command will add this repository to your `/vendor` directory, as well as all of the dependencies, which include a [global, CMS-agnostic PHP library](https://github.com/pantheon-systems/pantheon-edge-integrations) and a [Drupal module](https://github.com/pantheon-systems/smart_content_cdn) as well as all of the documentation for the SDK.

