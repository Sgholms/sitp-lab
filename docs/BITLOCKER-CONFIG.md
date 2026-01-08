# BitLocker Configuration (SITP)

## Goal
Protect data at rest on SITP systems using BitLocker drive encryption.

## Scope
- OS drive: BitLocker enabled (TPM-based where available)
- Data drives: BitLocker enabled for internal storage used for lab files and documentation

## Key Practices
- Save recovery keys securely (do not store in public repos)
- Use strong Windows account security and MFA where applicable
- Verify encryption status after enabling

## Verification
- Confirm drive shows "BitLocker on"
- Confirm recovery key was generated and stored securely
