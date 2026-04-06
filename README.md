# CNVD-Jinher-OA-XXE
本仓库用于漏洞研究的发布，后续poc尽情期待
# CNVD Vulnerability Record: XML Entity Injection in Jinher OA

This vulnerability has been recorded by China National Vulnerability Database (CNVD).

## Vulnerability Information

| Field | Value |
|-------|-------|
| **CNVD ID** | CNVD-2026-15669  |
| **Vendor** | Beijing Jinher Network Technology Co., Ltd. |
| **Product** | Jinher OA (C6 series) |
| **Vulnerability Type** | XML External Entity (XXE) Injection |
| **Description** | An XXE injection vulnerability exists in the `/c6/JHSoft.Web.HrmAttendance/sp_manager_getUserlist.aspx/GetXmlHttp` endpoint. An unauthenticated attacker can read arbitrary files via an out-of-band attack. |
| **Impact** | Information disclosure (arbitrary file read) |
| **Discovered by** | [HuangQixin] |
| **CNVD Publication Date** | 2026-03-26 |
| **CNVD收录时间** | 2026-04-01 |

## Status

- **CVE Status**: Reserved (CVE ID pending)
- **PoC Disclosure**: Full PoC will be published after CVE assignment is finalized.

## Reference

- CNVD official page (if available): [link]
- This repository serves as a public reference for CVE assignment request.

## Notes

No exploit code is included in this repository. The purpose is to provide a public, non-exploitable reference for vulnerability verification.
