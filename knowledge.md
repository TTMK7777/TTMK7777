# TTMK7777 - Knowledge Base

## Technical Decisions

| Decision | Choice | Alternatives Considered | Rationale |
|----------|--------|------------------------|-----------|
| Badge service | shields.io | Custom images | Standard, consistent, auto-themed |
| Stats card | github-readme-stats.vercel.app | Custom API | Maintained, popular, dynamic |
| Layout | Table for projects, badges for tech | Cards, lists | Clean and scannable |
| Language | English | Japanese, bilingual | Wider audience on GitHub |

## Learnings

- GitHub profile README is created by making a repository with the same name as the username (TTMK7777/TTMK7777)
- README.md in the default branch is automatically displayed on the profile page
- shields.io badges support flat, flat-square, for-the-badge, and other styles
- github-readme-stats supports themes (default, dark, radical, etc.)
- Images in README.md should use absolute URLs for reliability

## External Resources

- GitHub profile README docs: https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme
- shields.io: https://shields.io/
- github-readme-stats: https://github.com/anuraghazra/github-readme-stats
- GitHub Flavored Markdown: https://github.github.com/gfm/

## FAQ

- **Q: How to make the README appear on the profile?** A: Create a public repository named exactly the same as your username, and add a README.md.
- **Q: How to update stats?** A: Stats are dynamic and update automatically via the vercel.app API.
