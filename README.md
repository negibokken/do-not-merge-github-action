# donot-merge-github-action

The `donot-merge-github-action` blocks to merge PR when the PR has `DO NOT
MERGE` sentence in the title of PR. The action simply checks if the PR title
contains `DO NOT MERGE` sentence or not.

So the example of blocked titles are the followings:

* DO NOT MERGE:
* [DO NOT MERGE]
* DO NOT MERGE

On the other hand, the example of __not__ blocked title are the followings:

* DONOT MERGE
* DONOT MERGE:
* [DONOT MERGE]
* donot merge:
* [donot merge]
* don't merge

## License

MIT
