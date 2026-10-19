# Risk Rubric

Use this rubric in Phase 9. Do not change a level with personal judgment.

## Rules

1. Use only findings with identity match STRONG or PARTIAL.
2. A PARTIAL match can set AMBER at most. Only a STRONG match can set RED.
3. One RED trigger sets the overall rating to RED.
4. If there is no RED trigger, one AMBER trigger sets the overall rating to AMBER.
5. GREEN needs all of these conditions:
   - No RED or AMBER trigger.
   - Identity Confidence is HIGH or MEDIUM.
   - Phases 1, 3, and 4 have at least one source with status FOUND or NOT FOUND (not only NOT ACCESSIBLE).
6. If rule 5 fails only because sources were NOT ACCESSIBLE, set the rating to INCOMPLETE. Do not set GREEN.

## RED triggers

| Trigger | Evidence needed |
|---|---|
| Listed on a sanctions list (OFAC, UN, EU, UK, or national) | CONFIRMED |
| Debarred by the World Bank, ADB, or a government procurement body (current) | CONFIRMED |
| Criminal conviction for fraud, corruption, money laundering, tax evasion, or violence | CONFIRMED or REPORTED |
| Court judgment against the subject as defendant in a fraud or financial case | CONFIRMED |
| Regulator ban, licence revocation, or listing on an illegal investment or warning list | CONFIRMED |
| Company is dissolved, struck off, or in liquidation, but the subject says it is active | CONFIRMED |
| Major claim mismatch: a claim is false on a material point (company did not exist at the claimed date, person is not a director, licence does not exist) | CONFIRMED |
| Disqualified director (where a register exists) | CONFIRMED |

## AMBER triggers

| Trigger | Evidence needed |
|---|---|
| Open civil lawsuit as defendant, or a lawsuit filed in the last 3 years | CONFIRMED or REPORTED |
| Criminal charge or investigation with no verdict | REPORTED |
| Insolvency or debt restructuring process, now or in the last 5 years | CONFIRMED or REPORTED |
| Politically exposed person (PEP) | CONFIRMED |
| Minor claim mismatch (dates differ by 1 to 2 years, title differs) | Any |
| Professional profile or website states a different company or role than the subject told the user | INDICATED or better |
| Frequent changes of company name, address, or directors (3 or more in 3 years) | Any |
| Company website is less than 12 months old for a company that claims a long history | Any |
| Little or no business web presence for a company that claims a large operation | Any |
| Offshore structure in ICIJ Offshore Leaks | CONFIRMED |
| Identity Confidence is LOW | Not applicable |

## Identity Confidence

| Level | Condition |
|---|---|
| HIGH | Official registry entry matches the name, company, and registration number or address |
| MEDIUM | Company website or professional profile matches name and company, but no official registry entry was accessible |
| LOW | Name only, or sources conflict |

## Overall rating labels

| Label | Meaning for the user |
|---|---|
| GREEN | No adverse findings in the accessible sources |
| AMBER | Adverse findings that need a follow-up before the decision |
| RED | Findings that block the decision until legal or compliance review |
| INCOMPLETE | Key sources were not accessible. A human must complete the check |
