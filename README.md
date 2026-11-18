# Skills

Two [Agent Skills](https://agentskills.io), moved here from
[Open Machine](https://github.com/OpenMachineLabs/openmachine), whose history
keeps their earlier versions.

| Skill | Does |
| --- | --- |
| [`minimal-code`](skill-library/minimal-code) | Makes a coding agent deliver the smallest correct change |
| [`anthropic-style-illustrations`](skill-library/anthropic-style-illustrations) | Plans and renders original, evidence-bound diagrams and charts for a technical article |

Tests: `python3 -m unittest discover -s test/skill-library/<skill> -p 'test_*.py'`;
`minimal-code`'s needs PyYAML.

## License and notices

[MIT](LICENSE). Third-party material keeps its own terms:

- `anthropic-style-illustrations/references/` indexes links to public articles
  and figures, with short descriptions and quotes for reference. It holds no
  copy of them; their owners keep their rights.
- `anthropic-style-illustrations/requirements.txt` names PyMuPDF, which is
  AGPL-3.0 and installed separately; it is not part of this repository.
