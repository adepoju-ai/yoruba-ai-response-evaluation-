# Sample Evaluations

These examples show how the evaluation framework can be applied.

## Example 1 --- Meaning mismatch

**Prompt:** Translate: I want to drink water.\
**AI response:** Mo fẹ́ jẹ omi.\
**Overall:** 2/5\
**Error:** Meaning mismatch\
**Correction:** Mo fẹ́ mu omi.

The response uses a verb that does not express drinking in the intended
sentence.

## Example 2 --- Correct response

**Prompt:** Translate: I want to play.\
**AI response:** Mo fẹ́ ṣeré.\
**Overall:** 5/5\
**Error:** None

The response is short, accurate, natural, and suitable for a beginner
child.

## Example 3 --- Tense/aspect issue

**Prompt:** Translate: The child is eating.\
**AI response:** Ọmọ náà máa jẹun.\
**Overall:** 3/5\
**Error:** Tense/aspect\
**Correction:** Ọmọ náà ń jẹun.

The correction directly expresses the ongoing action requested.

## Example 4 --- Missing diacritics

**Prompt:** Translate: I want to drink water.\
**AI response:** Mo fe mu omi.\
**Overall:** 4/5\
**Error:** Missing diacritics\
**Correction:** Mo fẹ́ mu omi.

The meaning is recoverable, but standard written Yoruba uses
tone/diacritic marks that should be preserved when the task expects
formal written output.

## Example 5 --- Instruction and child suitability

**Prompt:** Give a child a simple way to say: I want to play.\
**AI response:** Mo fẹ́ ṣe eré ìdárayá.\
**Overall:** 4/5\
**Error:** Naturalness/child suitability\
**Correction:** Mo fẹ́ ṣeré.

The original is understandable but less direct and less simple for a
beginner child.

## Portfolio note

The examples are synthetic. They are designed to demonstrate evaluation
ability, not to claim client experience.
