DENOG Chatter List
------------------

Dieses Repo enthält die Daten, die genutzt werden, um die [DENOG
Chatterliste](https://www.denog.de/de/chatterliste_iframe.html) zu erstellen. Wenn du auf dieser Liste erscheinen
möchtest oder sich deine Daten geändert haben, bearbeite bitte die
[Datenquelle](https://github.com/denog/chatterliste/blob/master/_data/chatterliste.json) und stelle einen Pull
Request.

Sobald der PR gemerged wurde, werden die Daten [hier](https://www.denog.de/de/chatterliste_iframe.html) und
[hier](https://www.denog.de/chatterliste/) erscheinen.

Ist JSON nicht so deins? Eröffne eine Issue [hier](https://github.com/denog/chatterliste/issues/new/choose) und beantworte die Fragen. 

----------------

This repository contains the data used to generate the [DENOG Chatter
List](https://www.denog.de/de/chatterliste_iframe.html). If you want to appear on this list or want to update your data,
please edit the [data source](https://github.com/denog/chatterliste/blob/master/_data/chatterliste.json) and open a Pull
Request.

Once the PR has been merged, the data will appear [here](https://www.denog.de/de/chatterliste_iframe.html) and
[here](https://www.denog.de/chatterliste/).

Don't feel like editing JSON? Open a Issue [here](https://github.com/denog/chatterliste/issues/new/choose) and answer the questions.

Development
-----------

Run ``bundle install`` and ``bundle exec jekyll serve`` to see how the list will look like.

The general layout is in the ``_layouts`` directory, and the list itself is rendered from the data file in
``index.markdown``.
