# script-lang-matcher

This JSON file (script-lang-match.json) matches scripts (alphabets) to their languages.
ISO-15924 is used for the script codes. The languages codes are based on ISO-639-3.

Note that the Latin script is not included, because it is the default script.

Example for the Tamil script:

```json
  {
    "id": "Taml",
    "name": "Tamil",
    "notes": null,
    "langs": ["tam", "oty", "kev", "bfq", "iru", "pcg", "saz"]
  },
```

The "id" field is the ISO-15924 code for the script. The "name" field is the name of the script.
The "langs" field is an array of language codes based on ISO-639-3. In the case of the Tamil script it is
the Tamil language (tam), Old Tamil (oty), Kanikkaran (kev) and four other languages.

## References

The script-lang-match.json file is based on https://github.com/sigpwned/iso-15924-and-unicode-scripts, 
CC0 licensed.

The data is from https://en.wikipedia.org/wiki/ISO_15924

## License

MIT License