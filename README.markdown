#Git Completion
A bash completion script for git. 

## To install on linux
Simply copy `git-completion.bash into /etc/bash_completion.d/`<br />
That should run automatically.. if not, in your .bashrc file add the following line<br />
`. /etc/bash_completion.d/git-completion.bash`

## To install on MacOSX
You'll need to create the bash completion directory first.

`mkdir /opt/local/etc/bash_completion/`<br />
`cp git-completion.bash /opt/local/etc/bash_completion/`

## The coolness
When you `git<tab><tab>`
	<pre><code>
	add                 cherry              diff                instaweb            rebase              show-ref
	am                  cherry-pick         fast-export         log                 relink              st
	annotate            ci                  fetch               lost-found          remote              stash
	apply               citool              filter-branch       ls-files            repack              status
	archive             clean               format-patch        ls-remote           request-pull        submodule
	bisect              clone               fsck                ls-tree             reset               svnimport
	blame               co                  gc                  merge               revert              tag
	br                  commit              get-tar-commit-id   mergetool           rm                  up
	branch              config              grep                mv                  send-email          var
	bundle              convert-objects     gui                 name-rev            shortlog            verify-pack
	checkout            count-objects       imap-send           pull                show                whatchanged
	checkout-index      describe            init                push                show-branch
	</code></pre>