Markdown Test-2
============

# Invalid links and references

Link to a non-existing page: https://www.this-link-points-to-a-non-existing-page.com/.

Link to a page returning 404 error: https://github.com/keep-network/keep-core/tree/non-existing-branch.

[This](https://www.this-link-points-to-a-non-existing-page.com/) is another link to a non-existing page.

[This](test-3.md) is a link to an invalid local doc.

The end of this sentence is [an invalid reference](#non_existing_reference).

# Valid links and references

Link to a valid page: https://www.google.com/.

[This](https://www.google.com/) is another link to a valid page.

[This](test-1.md) is a link to a valid local doc.

The end of this sentence is a valid reference to [another section](#invalid_links_and_references).
