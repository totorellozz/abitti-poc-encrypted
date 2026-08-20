# abitti-poc-encrypted

This repository contains **only an encrypted archive** (`abitti-poc.7z`).

It is AES-256 encrypted (7-Zip, with encrypted filenames), so the contents cannot be
read — or even listed — without the password. The password is provided in the
associated Hackabi report.

## Decrypt
```
7z x abitti-poc.7z        # 7-Zip (Windows/Linux); on macOS: brew install p7zip, or open with Keka
```
Enter the password when prompted, then see the extracted `README.md` for usage.
