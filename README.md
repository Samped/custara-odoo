# Custara AP (Odoo 18)

Free LGPL-3 module for [apps.odoo.com](https://apps.odoo.com).

Custara is the AP control plane. Odoo stays the ledger. Approved bills settle in Arc mainnet USDC on [custara.xyz](https://custara.xyz).

## Branch

This repository uses Odoo series branch names. Install from branch **`18.0`**.

Apps Store registration URL:

```text
ssh://git@github.com/Samped/custara-odoo#18.0
```

## Install

Copy `custara_ap` into your Odoo 18 addons path, update the apps list, install **Custara AP**.

Settings → Accounting → Custara AP:

- API URL: `https://custara.xyz` (production) or `https://testnet.custara.xyz` (demo)
- Partner API key from Custara → Developers

## Source of truth

Module development continues in [Samped/Custara](https://github.com/Samped/Custara) under `odoo_apps/custara_ap`. Sync that folder into this repo when publishing updates.
