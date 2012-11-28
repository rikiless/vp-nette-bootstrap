# Visual Paginator for Nette Framework + Twitter Bootstrap 2.2.* #

## instalation ##

http://addons.nette.org/cs/visualpaginator (czech)

## use ##

###php

``public function createComponentVp()
{
	return new \Nette\Extras\Addons\VisualPaginator;
}``

###latte

``
{control vp}
``

###available parameters

- **size**: ``medium`` *(def.)*, ``mini``, ``small`` and ``large``
- **align**: ``centered`` *(def.)*, ``left`` and ``right``

**example**:

``
{control vp left}
{control vp, right, large}
``

## authors ##

- David Grudl
- Richard Tekel (fork)

## license ##

New BSD License