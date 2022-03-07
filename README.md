This is the OmniOS child of pkg(7)

Branches:

master

	This is the default development branch for OmniOS now. Besides
	ongoing development, this branch may be refreshed with merges from
	the "oi" branch from upstream. Commits in this branch are able to
	be cherry-picked by any upstream branch that wants them. Just follow
	the CDDL and give credit where due.

r151XXX

	As we issue releases, we branch for each release.

If you wish to discuss development here, join the discussion on
[Gitter](https://gitter.im/omniosorg/Lobby)

## Testing

In order to run the test-suite with 8 jobs in parallel:

```terminal
$ cd src
$ pfexec make test JOBS=8
```

Replace `pfexec` with `sudo` if that's your preference.

