# God's Eye View — GitHub Actions + Hugging Face

This repository is the deployment wrapper for the user-provided `GodsEyeView-FreeEdition.zip`.

## Important

- Upload the original ZIP to the repository root with the exact name `GodsEyeView-FreeEdition.zip`.
- Create a **private Docker Space** on Hugging Face first, then add the `HF_TOKEN` GitHub Actions secret.
- GitHub Actions will unpack the ZIP and deploy it to that Space.
- No local Node.js installation is required for the cloud deployment path.
- API keys are optional in the supplied Free Edition. Without them, several keyless layers work; voice, photorealistic 3D tiles, live ships, wildfires, and live traffic require their respective providers/keys.

See [`SETUP-GUIDE.txt`](SETUP-GUIDE.txt) for beginner-friendly step-by-step instructions.

Source project attribution and its included licenses/notices are retained in the ZIP. Review `LICENSE`, `DATA_SOURCES.md`, and `FREE-EDITION.md` before public or commercial use.
