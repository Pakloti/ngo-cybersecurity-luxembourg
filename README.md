# NGO Cybersecurity Luxembourg

A practical cybersecurity framework for small NGOs in Luxembourg. Two tiers, GDPR-aware, importable into CISO Assistant.

---

## Why this exists

Small NGOs in Luxembourg (patient associations, peer-support groups, prevention organisations, small care providers) handle sensitive personal data with limited budgets and often no IT staff. Most cybersecurity guides are written for enterprises and ask for things these organisations cannot realistically sustain.

This framework is different. It is **sized to what a small NGO can actually do**, organised into two honest tiers based on a single question: does your NGO have someone who can operate cybersecurity controls?

## Who this is for

- Small NGOs in Luxembourg, typically up to 20 people
- Volunteer-led or small-staff organisations
- Directors, board members, operations managers, or IT volunteers responsible for protecting NGO data
- Funders wanting realistic expectations from the NGOs they support

## Who this is *not* for

- Large NGOs with dedicated security teams
- Hospitals and other healthcare providers (sector-specific rules apply)
- Anyone looking for a formal certification scheme this is a working framework, not a badge

## What's in this repository

| File | What it contains |
|---|---|
| `guide/framework-guide-ngo.pdf` | The full 19-page practical guide |
| `guide/annex-gdpr-mapping.pdf` | The Annex covering GDPR obligations |
| `framework/ngo-cyber-lu.yaml` | The framework, formatted for [CISO Assistant](https://github.com/intuitem/ciso-assistant-community) |
| `framework/README.md` | The steps to import the framework in your Ciso assistant setup |
| `templates/Risk-Register.xlsx` | A one-page risk register template |

## The framework in one minute

**The five basics for every NGO**
1. Two-step login (MFA) everywhere
2. Backups (use a cloud workspace; test restores once a year)
3. Automatic device updates
4. A yearly one-hour awareness session
5. An offline emergency contact card

**Tier I** (1-5 people, no IT person): rely on the security built into your tools.
**Tier II** (up to ~20 people, at least one IT-capable person): configure and verify those tools properly.
**Sensitive personal data add-ons**: extra steps for NGOs handling health, vulnerability, or children's data.

## Using the framework in CISO Assistant

[CISO Assistant](https://github.com/intuitem/ciso-assistant-community) is a free, open-source GRC platform that lets you track your cybersecurity controls and produce evidence for funders or auditors.

1. Install CISO Assistant locally (see their [installation guide](https://intuitem.gitbook.io/ciso-assistant/deployment/local))
2. In the web interface, go to **Libraries ->  Add library**
3. Upload `framework/ngo-cyber-lu.yaml`
4. Create a new **Compliance Assessment** and select the framework
5. Work through the requirements, mark each one *compliant*, *partially compliant*, *non-compliant*, or *not applicable*

You can also use the PDF guide on its own, without CISO Assistant.

## Reading the PDF guide alone

If you just want the guide, open [`guide/framework-guide-ngo.pdf`](guide/framework-guide-ngo.pdf). Start with the **five basics**, identify your tier using the one-question test on page 12, then follow the section for your tier.

## Useful contacts in Luxembourg

- **NC3** : National Cybersecurity Competence Center (free training, Fit4Cybersecurity self-assessment)
- **CIRCL** : Computer Incident Response Center Luxembourg (call them first when something serious happens)
- **CNPD** : Commission nationale pour la protection des donn√©es (data breach notifications within 72 hours)

Full contact details are in the guide.

## Contributing

This framework is meant to grow with feedback from NGOs that actually use it. If you found something unclear, missing, or wrong, please [open an issue](../../issues). Pull requests are welcome. Especially:

- Translations (French, German, Luxembourgish)
- Real-world feedback after using the framework
- Updates as Luxembourg regulations or threat patterns evolve

## Disclaimer

This guide is a working framework, not legal advice. For binding interpretation of GDPR, the ASBL law, the ASFT law, NIS2, or sector-specific requirements, consult a lawyer or the relevant Luxembourg authority. Cybersecurity practices evolve review your tier and risk list annually.



