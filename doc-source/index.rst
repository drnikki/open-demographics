.. Open Demographics documentation master file, created by
   sphinx-quickstart on Fri Nov  3 10:22:08 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Open Demographics documentation
=============================================
What is this?
^^^^^^^^^^^^^^^^^^^^^^^^
Open Demographics is a recommended set of questions that anyone can use to ask community members about their demographics.

Why  did this start?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
When talking about  the makeup of the people in their (open source) community, I hear project leaders say a variation of "I'd like to ask about it but I don't know the right way and I don't want to mess up."

So it felt like a logical next step to standardize the ways that we ask questions about peoples' identities and demographic data.

The content and format of these questions were initially crowdsourced as part of the `demographics of the web survey <https://github.com/drupaldiversity/diversity-of-the-web>`_, run with support from Pantheon.

What's the point?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Part of the challenge with measuring "diversity" in an open-source community is the very poor data from community to community.  If we can standardize the questions that we use, the answers (or range of answers) can be valid across communities.

Who is this for?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This repository, and the questions it contains, are designed for (mostly open source) communities that want to know about the demographic makeup of community members.  It was specifically created by and for open source software communities but could be used by any group that wants to ask its members questions.

How do I use it?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
The questions in this repo are set up each as their own file.   If you find yourself thinking - "I wonder where most of our community members live?" or "I wonder if the gender makeup of my community  matches the average in my country" - these questions can help you answer that.

These questions are *especially* useful if you're trying to measure changes to your community over time.

There is no technical component to this product.  We're not making any explicit recommendations about how to administer the survey (like Google Forms or SurveyMonkey).  If you want to use the question, all you have to do is copy it and use it in your survey.  If you do use the questions, and would like to give us feedback on the quality of the data you received, please do!  WE're always working to make these questions better.


What do we need?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This project isn't ethically complete - I have concerns about storing this data along side a user's federated identity. As one example, it's possible that people identify as LGBTQIA but are not or cannot be public about that for Reasons.  Thus, in its current state, it is not a recommendation for storage, only for the text of questions and some variations depending on level of detail.

Further plans
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
- Recommend field name and data storage formats
- Recommend linking or not to users identity
- Recommend workflows for anonymous storage
- Make this survey less US-centric and provide translations and additional questions appropriate for other countries.
- Get more contributors

Please get involved in our `github repository <https://github.com/drnikki/open-demographics/>`_

Full Contents
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
(still configuring this doc generator, so for now, everything has to be included below to make the nav on the left work properly. Does someone know how to get around this?)

.. toctree::
    :glob:

    get_involved
    todos
    questions/*
    references/*
