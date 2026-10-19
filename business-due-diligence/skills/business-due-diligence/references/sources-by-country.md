# Sources by Country

Use this file in Phases 1 to 7. Each source has an access note:
- OPEN: free, and search engines index the pages. `site:` searches work.
- FORM: free, but the site uses a search form. Open the form with the browse tool if you can. If the tool cannot submit the form, mark NOT ACCESSIBLE.
- PAID / LOGIN / CAPTCHA: you cannot use it. Mark NOT ACCESSIBLE and put it in "Recommended next steps" for a human to check.
- AGGREGATOR: a private site that copies official data. Findings from it are INDICATED, not CONFIRMED. Use it to find leads, then confirm on the official source.

Sites change. If a pattern fails 2 times, search for the source name plus "search" to find the current URL.

---

## A. Global sources (use for every subject)

| Source | Use | Access | Search pattern |
|---|---|---|---|
| OpenSanctions (opensanctions.org) | Sanctions, PEPs, debarment from 100+ lists, including OFAC, UN, EU, UK | OPEN | `site:opensanctions.org "[name]"` and open opensanctions.org/search/?q=[name] |
| OFAC Sanctions List Search (sanctionssearch.ofac.treas.gov) | US sanctions | FORM | Use OpenSanctions if the form fails |
| UN Security Council Consolidated List (scsanctions.un.org) | UN sanctions | FORM | Use OpenSanctions if the form fails |
| EU Sanctions Map (sanctionsmap.eu) | EU sanctions | FORM | Use OpenSanctions if the form fails |
| World Bank Debarred Firms and Individuals | Procurement fraud debarment | OPEN | `"World Bank" debarred "[company]"` and open the list page |
| Asian Development Bank sanctions list | Procurement debarment, Asia | OPEN | `ADB sanctions list "[company]"` |
| Interpol Red Notices (public) | Wanted persons, public notices only | FORM | Most notices are not public. NOT FOUND here does not clear a person |
| ICIJ Offshore Leaks (offshoreleaks.icij.org) | Offshore entities, Panama and Pandora Papers | OPEN | `site:offshoreleaks.icij.org "[name]"` |
| OpenCorporates (opencorporates.com) | Company records from 140+ registries | AGGREGATOR | `site:opencorporates.com "[company]"` |
| GLEIF LEI search (search.gleif.org) | Legal Entity Identifier, legal name, address, parent company | OPEN | Search the company name |
| Wayback Machine (web.archive.org) | Old versions of the company website | OPEN | web.archive.org/web/*/[domain] |
| Reuters, Bloomberg, Financial Times, AP | International adverse media | OPEN (some paywalls) | `"[name]" site:reuters.com` |

---

## B. India

| Source | Use | Access | Search pattern |
|---|---|---|---|
| MCA21 Company Master Data (mca.gov.in) | Official company status, CIN, directors (DIN) | FORM / CAPTCHA | Mark NOT ACCESSIBLE if blocked |
| Zauba Corp, Tofler, The Company Check | Copies of MCA data: CIN, status, directors, charges | AGGREGATOR | `site:zaubacorp.com "[company]"`, `site:tofler.in "[company]"` |
| GST taxpayer search (services.gst.gov.in) | GSTIN validity and legal name | FORM / CAPTCHA | Ask the user for the GSTIN |
| Indian Kanoon (indiankanoon.org) | Judgments from Supreme Court, High Courts, tribunals | OPEN | `site:indiankanoon.org "[name]"` |
| eCourts (ecourts.gov.in) | District court case status | CAPTCHA | NOT ACCESSIBLE. Recommend a manual check |
| NCLT (nclt.gov.in) and IBBI (ibbi.gov.in) | Insolvency (CIRP), liquidation, public announcements | OPEN | `site:ibbi.gov.in "[company]"`, `"[company]" NCLT insolvency` |
| SEBI orders (sebi.gov.in) | Securities enforcement orders and debarment | OPEN | `site:sebi.gov.in "[name]" order` |
| RBI (rbi.org.in) | Alert list of unauthorised forex platforms, cancelled NBFC licences | OPEN | `site:rbi.org.in "[company]"` |
| Enforcement Directorate (enforcementdirectorate.gov.in) | Money laundering (PMLA) press releases | OPEN | `site:enforcementdirectorate.gov.in "[name]"` |

Local keywords: fraud, cheating, "Section 420", FIR, chargesheet, "wilful defaulter", insolvency, NCLT, ED raid, धोखाधड़ी (fraud), गिरफ्तार (arrested).

Credible news: The Hindu, Indian Express, Hindustan Times, Times of India, Economic Times, Business Standard, Mint, Moneycontrol, PTI.

---

## C. Indonesia

| Source | Use | Access | Search pattern |
|---|---|---|---|
| Ditjen AHU (ahu.go.id) | Company deeds (akta pendirian, akta perubahan), directors and commissioners (pengurus) | PAID for full profile | Mark NOT ACCESSIBLE for full profile. Recommend a notary (notaris) check |
| Direktori Putusan Mahkamah Agung (putusan3.mahkamahagung.go.id) | Court decisions, all court levels | OPEN | `site:putusan3.mahkamahagung.go.id "[nama]"` |
| SIPP per district court (sipp.pn-[city].go.id) | Case tracking in a district court (Pengadilan Negeri) | FORM | Use the court of the subject's city |
| OJK (ojk.go.id) and Satgas PASTI | Financial licences, illegal investment and illegal lending lists | OPEN | `site:ojk.go.id "[nama]"`, `Satgas PASTI "[nama]"` |
| IDX (idx.co.id) | Listed company disclosures | OPEN | `site:idx.co.id "[company]"` |
| KPPU (kppu.go.id) | Competition law decisions | OPEN | `site:kppu.go.id "[company]"` |
| SLIK OJK | Credit history | NOT PUBLIC | Requires consent of the subject. Recommend a formal request |

Local keywords: penipuan (fraud), penggelapan (embezzlement), wanprestasi (breach of contract), gugatan (lawsuit), tergugat (defendant, civil), terdakwa (accused, criminal), divonis (sentenced), pailit (bankrupt), PKPU (debt suspension), korupsi (corruption), pencucian uang (money laundering), ditangkap (arrested).

Credible news: Kompas, Tempo, Detik, Bisnis Indonesia, Kontan, CNBC Indonesia, Antara, Jakarta Post.

---

## D. Singapore

| Source | Use | Access | Search pattern |
|---|---|---|---|
| ACRA Bizfile (bizfile.gov.sg) | Official company profile | PAID for full profile | Basic UEN search is free. Full profile NOT ACCESSIBLE |
| Company directories (for example sgpbusiness.com) | UEN, status, address | AGGREGATOR | `"[company]" UEN` |
| eLitigation judgments (elitigation.sg) | Published court judgments | OPEN | `site:elitigation.sg "[name]"` |
| MAS (mas.gov.sg) | Investor Alert List, enforcement actions | OPEN | `site:mas.gov.sg "[name]"` |
| Government Gazette (egazette.gov.sg) | Winding-up and bankruptcy notices | OPEN | `site:egazette.gov.sg "[name]"` |

Credible news: The Straits Times, The Business Times, CNA.

---

## E. Malaysia

| Source | Use | Access | Search pattern |
|---|---|---|---|
| SSM e-Info (ssm.com.my) | Official company profile | PAID | NOT ACCESSIBLE. Recommend purchase of a company profile |
| Malaysian judiciary e-Judgment (kehakiman.gov.my) | Published judgments | FORM | `site:kehakiman.gov.my "[name]"` |
| Securities Commission (sc.com.my) | Investor Alert List, enforcement | OPEN | `site:sc.com.my "[name]"` |
| Bank Negara (bnm.gov.my) | Financial Consumer Alert List | OPEN | `site:bnm.gov.my "[name]"` |
| Malaysian Department of Insolvency (mdi.gov.my) | Bankruptcy status | FORM | NOT ACCESSIBLE if blocked |

Local keywords: penipuan (fraud), didakwa (charged), mahkamah (court), saman (lawsuit), bankrap (bankrupt), SPRM or MACC (anti-corruption).

Credible news: The Star, New Straits Times, The Edge Malaysia, Malaysiakini, Free Malaysia Today.

---

## F. United Kingdom

| Source | Use | Access | Search pattern |
|---|---|---|---|
| Companies House (find-and-update.company-information.service.gov.uk) | Company status, officers, filings, disqualified directors | OPEN | Search company and officer names |
| Find Case Law (caselaw.nationalarchives.gov.uk) | Judgments | OPEN | `site:caselaw.nationalarchives.gov.uk "[name]"` |
| The Gazette (thegazette.co.uk) | Insolvency and winding-up notices | OPEN | `site:thegazette.co.uk "[name]" insolvency` |
| FCA Register and Warning List (register.fca.org.uk) | Financial authorisation, clone firms | OPEN | `site:fca.org.uk "[name]"` |

---

## G. United States

| Source | Use | Access | Search pattern |
|---|---|---|---|
| State business registries (Secretary of State) | Company status, registered agent | FORM | Use OpenCorporates for leads |
| SEC EDGAR (sec.gov/edgar) | Filings of listed companies | OPEN | `site:sec.gov "[company]"` |
| SEC litigation releases | Securities enforcement | OPEN | `site:sec.gov/litigation "[name]"` |
| FINRA BrokerCheck (brokercheck.finra.org) | Broker records | FORM | Search the name |
| CourtListener (courtlistener.com) | Federal and state opinions, some dockets | OPEN | `site:courtlistener.com "[name]"` |
| PACER | Federal dockets | PAID | NOT ACCESSIBLE |
| SAM.gov exclusions | Federal procurement exclusions | FORM | Search the name |
| DOJ press releases (justice.gov) | Indictments, pleas, convictions | OPEN | `site:justice.gov "[name]"` |

---

## H. Other countries (generic method)

If the country is not listed:
1. Search `[country] company registry search` and find the official registrar.
2. Search `[country] court judgments database` and `[country] supreme court decisions search`.
3. Search `[country] financial regulator investor alert list`.
4. Find the local words for: fraud, lawsuit, defendant, convicted, bankrupt. Search with them.
5. Use 2 or 3 national news outlets with a known editorial standard (national newspapers, public broadcaster, national news agency).
6. Record each source and its access status in the Coverage Log.
