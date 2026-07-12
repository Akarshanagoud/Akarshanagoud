# Setup Instructions

## 1. Create the GitHub profile repository

Sign in to the `Akarshanagoud` GitHub account and create a new **public** repository named exactly:

```text
Akarshanagoud
```

GitHub displays the `README.md` from this repository on the profile page.

## 2. Upload this package

Upload the following into the repository root:

```text
README.md
assets/
.github/
```

Preserve the folder structure.

## 3. Enable GitHub Actions

Open:

```text
Repository → Settings → Actions → General
```

Choose:

```text
Read and write permissions
```

Save the setting.

The contribution-snake workflow will then generate:

```text
output/github-contribution-grid-snake-dark.svg
```

## 4. Optional metrics token

The snake animation works with the built-in `GITHUB_TOKEN`.

The optional `metrics.yml` workflow requires a personal access token:

1. Create a GitHub personal access token.
2. Add it as a repository secret named `METRICS_TOKEN`.
3. Run the `Profile metrics` workflow manually.

Delete `metrics.yml` if you do not want this optional feature.

## 5. Add exact repository links

The current README contains project descriptions based on the supplied resume because the public repositories under the requested handle could not be verified.

After confirming the real repository names, replace each generic link:

```text
https://github.com/Akarshanagoud?tab=repositories
```

with the exact project repository URL.

## 6. Check the profile

Open:

```text
https://github.com/Akarshanagoud
```

The profile README should appear automatically.
