# تشخیص کلاهبرداری (Scam Recognition — Farsi)

پیامک جعلی، تماس بانکی، کلون صدا و کلاهبرداری تلگرامی را قبل از اینکه
هزینه‌ای برایتان بسازد بشناسید — علامت‌های هشدار واقعی، نه حدس و گمان.

Native Farsi content covering Iran-specific fraud patterns — fake Sana/
subsidy SMS, card-to-card fraud, messenger account takeover, Telegram
investment scams, and AI voice cloning — **not a translation** of the
English `scam-fraud-recognition` sibling course. It shares that course's
psychological-foundations deck structure and icon set, but every example
past the foundations section is regionally accurate to Iran.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog — a
spaced-repetition flashcard course, ready to build and validate with the
standard Yaaddi course tooling.

## Structure

- `meta.json` — course metadata (`language: "fa"`, title, description, cover image, version)
- `source/` — authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images/)
- the built `.zip` — generated from `source/` via `build_course_zip.py`

## Editing this course

1. Edit `source/units.csv` / `source/cards.csv` / `source/glossary.csv` directly.
2. Run `python validate_course.py . --source` and fix anything it flags
   (use `PYTHONIOENCODING=utf-8` if running from a Windows terminal, so
   Farsi text in warnings/errors prints correctly).
3. Run `python build_course_zip.py .` to regenerate the shipped `.zip`.
4. Commit both the `source/` changes and the rebuilt `.zip`.
