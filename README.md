SBook5
======

Forked for a web-based addressbook in rails that will leverage Sbook's AI library.

Questions to address..
1. Can we build this on GNUStep? In theory yes, but in theory, theory and practice are identical; in practice they're not and we live in a world of practice, not theory.
2. Once the answer to 1 is "yes", we'll need to write a wrapper for this for the [addressbook](https://github.com/hasandiwan/addressbook) and incorporate it into the web application. There are [tests for how we'll call the backend](https://github.com/hasandiwan/addressbook/blob/master/test/integration/plain_text_tagging_test.rb).
