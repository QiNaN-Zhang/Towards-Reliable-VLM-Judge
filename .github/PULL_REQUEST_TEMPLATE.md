&lt;!-- Thanks for contributing to GridWM-Judge! --&gt;

## Summary

&lt;!-- What does this PR change and why? Link related issues. --&gt;

Closes #&lt;!-- issue number, if any --&gt;

## Type of change

- [ ] Bug fix (non-breaking change that fixes an issue)
- [ ] New feature / task / probe
- [ ] Scoring or metric change
- [ ] Documentation / README update
- [ ] Refactor / tooling
- [ ] Other (please describe):

## Checklist

- [ ] I ran the relevant workflow from the repository root
- [ ] If generation / scoring was affected, I verified with `--profile smoke` (or a small subset)
- [ ] Scoring and experiment builders were tested with a **fresh** output directory
- [ ] If `--resume` behavior changed, resume invariants (code, config, seed, interpreter, renderer) are preserved or documented
- [ ] I did not commit generated outputs (`outputs/`, run directories, responses, or images)
- [ ] `environments/*.yml` / `requirements/*.lock.txt` are updated if dependencies changed
- [ ] README or relevant docs are updated for user-facing changes
- [ ] New code follows the existing `scripts -&gt; tools -&gt; tools/utils` layering (utilities import no project modules)

## Evidence (optional)

&lt;!-- Logs, score diffs, `scoring_receipt.json` excerpts, or screenshots supporting the change. --&gt;

## License

- [ ] I agree to license this contribution under the repository's MIT License.
