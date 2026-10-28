# Git Collaboration Lab

**A two-person exercise to practice a team Git workflow: feature branches, pull requests, code review and merge-conflict resolution.**

Built by Khadija Alaoui Mrani (student A) and [Rim Ben Moussa](https://github.com/RimBenMoussa) (student B).

## What we practiced

1. **Feature branches** – each student worked on their own branch: `feature/etudiant-a` and `feature/etudiant-b`.
2. **Conventional Commits** – messages such as `feat: add feature B` and `docs: update README`.
3. **Pull requests** – every change reached `main` through a reviewed pull request (#1 and #2).
4. **Merge conflict** – both students edited this README at the same time; the conflict was resolved by hand before merging.
5. **`.gitignore`** – ignoring `node_modules/` and log files.

## Files

| File | Added by |
|------|----------|
| `fonctionnalite-a.txt` | Student A |
| `fonctionnalite-b.txt` | Student B |

## Workflow summary

```bash
git switch -c feature/etudiant-a
# ...make changes...
git commit -m "feat: add feature A"
git push -u origin feature/etudiant-a
# open a pull request on GitHub, review, merge
git switch main && git pull
```
