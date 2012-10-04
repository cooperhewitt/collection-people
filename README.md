collection-people
==

concordances.csv
--

These are [people who've had a hand in the Cooper Hewitt collection](http://collection.cooperhewitt.org/people/) who we _think_
we know about at another institution or in another database of people. **As of
this writing there are some mistakes in this list** but it's mostly correct and
a valuable resource and a step, however small, in the right direction.

_This list was generated using some pretty naive code that really only concerned
itself with names and concordances that could be inferred with the simplest of
rulesets. There is lots of work to be done here but [we opted for doing the easy
thing first](https://github.com/cooperhewitt/collection-people/issues/1#issuecomment-9157141) in the service of our collections website so as not to get stuck in
the quicksand of edge cases._

Our hope is that people will use these concordances with their own datasets,
help us improve the data by correcting the mistakes we've let slip through the
cracks and by adding their own concordances for other data sources.

We currently have one or more concordances between Cooper-Hewitt "people" and
six other sources. They are:

[Freebase](http://www.freebase.com/)
---

Concordances are listed under the `freebase:id` column. For example
[ch:id=18536279](http://collection.cooperhewitt.org/people/18536279/) is the same as [freebase:id=m/01hlzm](http://www.freebase.com/m/01hlzm)

[Wikipedia](http://www.wikipedia.org/)
---

Concordances are listed under the `wikipedia:id` column. For example
[ch:id=18042217](http://collection.cooperhewitt.org/people/18042217/) is the same as [wikipedia:id=908990](http://en.wikipedia.org/wiki/index.html?curid=908990)

[Virtual Internet Authority File (VIAF)](http://viaf.org/)
---

Concordances are listed under the `viaf:id` column. For example
[ch:id=18042217](http://collection.cooperhewitt.org/people/18535633/) is the same as [viaf:id=103648062](http://viaf.org/viaf/103648062/)

[Library of Congress Name Authority File](http://id.loc.gov)
---

Concordances are listed under the `lcnaf:id` column. For example
[ch:id=18042217](http://collection.cooperhewitt.org/people/18049223/) is the same as [lcnaf:id=94029554](http://id.loc.gov/authorities/names/no94029554.html)

[Museum of Modern Art (MOMA)](http://www.moma.org/)
---

Concordances are listed under the `moma:id` column. For example
[ch:id=18055621](http://collection.cooperhewitt.org/people/18055621/) is the same as [moma:id=5392](http://www.moma.org/collection/artist.php?artist_id=5392)

[Indianapolis Museum of Art (IMA)](http://www.imamuseum.org/)
---

Concordances are listed under the `ima:id` column are a bit trickier than the
others. Specifically the IMA doesn't (yet) have public identifiers for the
people (called "actors" in IMA-speak) in their collection.

The Cooper-Hewitt [forked the IMA's public collection metadata and extracted all
the actors](https://github.com/cooperhewitt/ima-collection/tree/master/actors)
creating discrete records, and identifiers, for each one along the way.

These are the identifiers listed in the `concordances.csv` document. They will
almost certainly change. A [pull request with the newly minted
identifiers](https://github.com/IMAmuseum/ima-collection/pull/2) was sent to the
IMA but they will probably roll their own identifiers in the future as time and
circumstances permit.

_If you look carefully at our collections website you may notice that we also
claim to have concordances with the [Powerhouse Museum](http://www.powerhousemuseum.com/) in Sydney and the
[Victoria and Albert Museum](http://www.vam.ac.uk/) in London. They are not included here because
like the IMA they do not have public identifiers (and we haven't made any for
them yet ;-)_

See also
--

* [Cooper-Hewitt National Design Museum Collections website](http://collection.cooperhewitt.org/)

