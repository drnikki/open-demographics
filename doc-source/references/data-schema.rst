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
