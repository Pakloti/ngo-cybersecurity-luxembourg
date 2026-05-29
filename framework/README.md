# NGO Cybersecurity Luxembourg - Framework

The framework files in this folder let you import the NGO Cybersecurity Luxembourg framework into [CISO Assistant](https://github.com/intuitem/ciso-assistant-community), a free open-source GRC tool. Once imported, your NGO can answer each question, get a maturity score, and see which controls still need work.

## What's in this folder

| File                | Use                                                |
| ------------------- | -------------------------------------------------- |
| `ngo-cyber-lu.yaml` | The framework, ready to import into CISO Assistant |


## How to import the framework

1. Install CISO Assistant locally. The official guide is here: https://intuitem.gitbook.io/ciso-assistant/deployment/local
2. Log in to your instance (usually at `https://localhost:8443`)
3. Go to **Governance → Libraries**
4. Click the upload button (top right) and select `ngo-cyber-lu.yaml`
5. Once the library appears in the list, click the arrow icon on its row to activate it

## How to run your first self-assessment

1. Go to **Governance → Perimeters** and create a Perimeter for your NGO (name it whatever you like)
2. Go to **Compliance → Audits** and click **+ Add**
3. Fill in the form:
   - **Name**: anything, for example `Assessment 2026`
   - **Perimeter**: the one you just created
   - **Framework**: NGO Cybersecurity Luxembourg
   - **Implementation Groups**: pick the ones that match your NGO
     - **BASICS** only: bare minimum for any NGO
     - **BASICS + T1**: NGO of 1 to 5 people without an IT person
     - **BASICS + T1 + T2**: NGO of up to 20 people with at least one IT person
4. Click on each requirement and set its status (compliant, partially compliant, non-compliant, not applicable) and optionally a score from 1 to 5

The progress bar updates as you fill it in. Non-compliant items are your action list.

## What the scores mean

| Score | Name                  | What it means                                                |
| ----- | --------------------- | ------------------------------------------------------------ |
| 1     | Not started           | The control is not in place                                  |
| 2     | In progress           | The team is setting it up                                    |
| 3     | Implemented           | The control works and people use it                          |
| 4     | Reviewed regularly    | The control is checked at the cadence we set (yearly, quarterly) |
| 5     | Continuously improved | The control is reviewed and improved based on near-misses    |

## Need help?

- For questions about the framework content (what an exigence means, why a control is at one tier and not the other): open an issue in this repo
- For questions about CISO Assistant itself (installation, errors, features): see their [documentation](https://intuitem.gitbook.io/ciso-assistant/) or [Discord](https://discord.gg/ciso-assistant)