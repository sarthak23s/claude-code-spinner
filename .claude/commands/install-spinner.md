Read the `spinners.json` file from the root of this repository. Then read the user's `~/.claude/settings.json` file.

Format of `spinners.json`:

```json
{
  "mode": "replace",
  "verbs": ["Phrase 1", "Phrase 2"]
}
```

If the `spinnerVerbs` field already exists in `~/.claude/settings.json`, replace its value. If it doesn't exist, create it. Field format:

```json
"spinnerVerbs": {
  "mode": "replace",
  "verbs": ["Phrase 1", "Phrase 2"]
}
```

IMPORTANT: Do not modify any other fields in `settings.json`. Only change `spinnerVerbs`.
