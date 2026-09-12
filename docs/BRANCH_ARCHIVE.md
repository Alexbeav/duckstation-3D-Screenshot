# Preserved development history

The default branch is the maintained source. The tags below preserve earlier source or separate candidates at exact commits.
No archived candidate gains new build, package, or gameplay acceptance through this cleanup.

A tag is a fixed source snapshot. Existing tree URLs and `git clone --branch <name>` can select these tags.
For local inspection, use `git fetch origin --tags` followed by `git switch --detach refs/tags/<name>`.
To resume development, create a temporary branch from the tag. Do not move an archive tag.

| Tag | Preserved commit | Disposition |
|---|---|---|
| `fix-linux-deadlock` | [`56ef131956291a1cab0ea33a3d3b8e9521afb050`](https://github.com/Alexbeav/duckstation-3D-Screenshot/tree/56ef131956291a1cab0ea33a3d3b8e9521afb050) | Contribution source preserved; upstream acceptance remains a separate record. |
| `master` | [`928dd0e6656ef76ea54b380ec356f872e5e92c42`](https://github.com/Alexbeav/duckstation-3D-Screenshot/tree/928dd0e6656ef76ea54b380ec356f872e5e92c42) | Contribution source preserved; upstream acceptance remains a separate record. |

Recorded 2026-09-13. Existing version tags and releases remain unchanged.
