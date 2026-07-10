# Endpoint Security Policy (Baseline)

Applies to corporate-issued Windows endpoints.

- Endpoint protection: Windows Defender Antivirus enabled with real-time protection.
- Secure boot: UEFI SecureBoot enabled; no BIOS/Legacy override allowed.
- Update hygiene: OS security updates installed within vendor-defined window.
- Firewall: Windows Firewall enabled for all profiles.
- Attestation evidence: collect baseline JSON monthly.

## Exceptions

- Temporary BIOS mode for certified firmware lab only; approval required from security.
