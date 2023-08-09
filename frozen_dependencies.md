slug: frozen-dependencies 
title: Frozen dependencies and dead projects
last_major_edit: 09/08/2022
tags_list: software
type: Journal
status: Finished

I have, on several ocassions, found myself tangled up trying to resurrect projects built in languages and package managers / tooling I'm not familiar with.

One can ease oneself into development in a different stack by starting with
small features, bug fixes etc. But outdated packages, frozen dependencies and
obscure package manager errors are much more demotivating obstacles to
overcome.
* Makes it tempting to try and reinvent the wheel in a stack where there is an
  apparent way to ensure high maintainability. But that would mean reinventing
  the wheel all the time, what with half of modern software being written in JS.
  *

Freezing packages seems like an anti-pattern, a thoughtless, expeditious
choice or, rather disappointingly, a default for modern tooling.
