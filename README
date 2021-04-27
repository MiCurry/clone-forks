= clone-forks

I got tired of manually cloning and adding remotes from forks of repositories I
commonly hack on.

Just specify a nickname for the repo along with a list of forks URLs and remote
names and this utility will clone you the remote and automically add the
remotes you specified.

This will also be helpful as there will not be any 'origin' remote, which will
prevent users from mindlessly running a force push on an important branch (we
all have done it)


= Usage

Specify repositories and their remotes in  `~/.repos`. Give a repo its nickname
by: `= repo-name`, including the space following the `=`. Then, following that
add a list of pairs of remote names and remote url:


```
= repo-name
my-fork https://github.com/MiCurry/repo-name
your-fork https://github.com/YourName/repo-name
Frodos-fork https://github.com/FrodoBags/repo-name
```

And repeat for additional repositories, but ensure there is an empty line
between the next repo listing:

```
= repo-name
my-fork https://github.com/MiCurry/repo-name
your-fork https://github.com/YourName/repo-name
Frodos-fork https://github.com/FrodoBags/repo-name

= death-star-plans
curry https://github.com/MiCurry/death-star-plans
vader https://github.com/DarthVader/death-star-plans
organa https://github.com/PleiaOrgana/death-star-plans
solo https://github.com/12ParsecsHan/death-star-plans
```

Lines that start with '#' are ignored (**NOTE ONLY START WITH**):

``
# Repo for newest Death Star (not the old one)
= death-star-plans
curry https://github.com/MiCurry/death-star-plans
```
