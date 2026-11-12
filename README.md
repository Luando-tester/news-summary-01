# World news summary

`main.py` assembles a deterministic English summary of the ten supplied world-news
events and writes it as UTF-8 text. It writes to `/output/entry.txt` when the
`/output` directory exists; otherwise it writes `entry.txt` next to the script.
The program checks that the summary contains between 1 and 2,000 characters.

Run it with Python 3.13:

```sh
python3 main.py
```

This project is provided under the MIT License; see [LICENSE](LICENSE).
