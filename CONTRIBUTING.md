# Contributing

Thanks for helping build Awesome Quran AI.

## What Belongs Here

Resources should be useful to developers, researchers, designers, or maintainers working on Quran AI, Quran search, Quran recitation, Quran education, Arabic NLP for Quranic text, or related Islamic computing projects.

Good additions include:

- APIs with stable documentation.
- Datasets with clear provenance and access terms.
- Models useful for Quranic Arabic, Arabic NLP, recitation, retrieval, or evaluation.
- Tools that help build, analyze, search, annotate, or validate Quran applications.
- Papers with a direct Quran AI, Quran NLP, Quran audio, or Quran corpus connection.
- Open-source projects with usable code.

## Submission Format

Add the item to both `README.md` and `data/resources.yml`.

README entry format:

```markdown
- [Name](https://example.com/) - Short neutral description.
```

YAML entry format:

```yaml
- name: Resource Name
  url: https://example.com/
  description: Short neutral description.
  tags: [quran, api, example]
  license: MIT
```

Use `verify` for license only when the resource is valuable but the license still needs checking. Prefer exact license identifiers where possible.

## Review Checklist

- The link works.
- The description is factual and not promotional.
- The resource has clear relevance to Quran AI developers.
- Quran text, tafsir, translation, and audio provenance is stated when available.
- License or terms are included when available.
- Generated religious answers, fatwas, or tafsir claims are not presented as authoritative.

## Sensitive Content Guidelines

Quran applications should handle religious text carefully. Avoid submitting resources that:

- Modify Quran text without clear labeling.
- Mix generated content with Quran, hadith, tafsir, or scholarly references without visible provenance.
- Scrape private or restricted datasets.
- Present unreviewed model output as religious authority.
- Hide licensing restrictions for translations, recitations, or tafsir.
