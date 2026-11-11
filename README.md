# Formal Analysis of OpenID4VCI 1.1 Issuance Flows

Multi-principal symbolic security model and per-lemma verification archive for the Authorization Code and Pre-Authorized Code issuance flows of OpenID for Verifiable Credential Issuance (OpenID4VCI) 1.1 in the Tamarin prover.

## Specification Baseline

- **Source repository:** `https://github.com/openid/OpenID4VCI`
- **Analysed snapshot:** Editor's draft `openid-4-verifiable-credential-issuance-1_1-01`, frozen on 28 September 2026 at commit `9115217` (`9115217c7af9cc6441e7cc2147016fc333c670d1`).

## Repository Contents

The archive (`Formal-Analysis-Of-OpenID4VCI_1.1.zip`) unpacks into a single folder containing:

- `oid4vci_multi.spthy` — unified 1,361-line Tamarin theory (`OID4VCI_MultiPrincipal`, SHA-256 `981174cb50225f953416af0ade1a347e0143902164ccec8c9d0d8b6afbc8a55b`) parameterised by preprocessor flags across 21 configurations.
- `<CONFIG>__<LEMMA>/` (321 directories) — per-lemma execution records (`analysis.log`, and where produced, `result.spthy` and witness trace exports `trace.json` / `trace.dot`), generated with Tamarin 1.12.0 and Maude 3.4.
