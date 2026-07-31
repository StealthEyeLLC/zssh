# Upload Z / zssh Documentation to GitHub

Target repository: `StealthEyeLLC/zssh`  
Target branch: `main`

## Upload rule

Upload the complete contents of this package while preserving every relative path. Do not upload the enclosing `zssh-repository-initialization` directory as an extra repository level.

The repository root should contain `README.md`, `AGENTS.md`, `llms.txt`, `docs/`, `.github/`, `evidence/`, `assets/`, `src/`, `tests/`, and `scripts/` directly.

## Suggested initial commit

```text
docs: initialize Z SSH-native architecture
```

## Verification after upload

1. Open `README.md` from the repository root.
2. Confirm every link in `docs/INDEX.md` resolves.
3. Confirm `AGENTS.md` appears at the root.
4. Confirm `llms.txt` appears at the root.
5. Search the repository for `StealthEyeLLC/zssh`; the result must be empty.
6. Search for `StealthEyeLLC/zssh`; discovery documents should appear.
7. Search for `ProxyUseFdpass`, `AF_VSOCK`, `Network None`, and `zero Z processes`; the governing documents should be returned.
8. Confirm `evidence/README.md` says no implementation evidence exists yet.

GitHub code-search indexing may not be immediate after the first upload. The repository has redundant discovery surfaces so agents can navigate from the root even before full-text indexing completes.
