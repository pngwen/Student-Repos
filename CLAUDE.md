# mkstudr

## Commits

When creating git commits, list Claude as the author and pngwen as co-author:

```
git commit --author="Claude Sonnet 4.6 <noreply@anthropic.com>" -m "$(cat <<'EOF'
<message>

Co-Authored-By: pngwen <pngwen@acm.org>
EOF
)"
```
