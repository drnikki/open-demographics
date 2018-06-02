---------------------------
JSON Design Schema
---------------------------

This document is intended to capture the data points needed to render a form based on a JSON file.

Data Needed
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This is a list of all of the pieces of information we'll want to share. The `[text]` is a proposed field name.

- a question ID `[id]`
- text of the question prompt `[question_prompt]`
- the type of field(s) needed
  - this gets tricky because some fields are radio/checkboxes plus a "fill in the blank"
- a longer description of what the field is asking `[long_description]`
- for each question: `[options]`
  - the type of field `[option_type]`
  - the text displayed to the user `[option_label]`
  - the internal value `[option_value]`








## Questions:
- in the case of age, we have a long and a short version of the question.  Folks have expressed interest in this, and I think it's worth considering that question consumers might not always want the _full_ list of options.
- aspects are repeated. How do we want to indicate those so that we don't have to include them in the list of choices.
  - self Identify
  - prefer not to answer
  - does not apply
