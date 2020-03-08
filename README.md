# Markdown-training
For trainig Markdown with WesBoss

## About paragraphs

Wes is **cool**. (bold with asterix)

Wes is __really__ cool. (bold with underscore)

*Wes* is cool. (italic with asterix)

_Wes_ is very cool. (italic with underscore)

Wes is ~~not~~ cool. (strikethrough with tilde)

## About headers

*Below header 3*

### Header 3

*Below header 4*

#### Header 4

*Below header 5*

##### Header 5

*Below header 6*

###### Header 6

## Links

*Link 1: wrapping with angle brackets*

<http://www.wesbos.com> - official WesBos site.

*Link 2: wrapping with square brackets*

Official [WesBos](http://www.wesbos.com) site.

*Link 3: wrapping with square brackets and __title tag__*

Official [WesBos](http://www.wesbos.com "WesBos site") site.

*Link 4: wrapping with two square brackets: **first** for highliight, **second** for keylink.*

Official [WesBos][1] site.
[Onet][2] site.


[1]: http://www.wesbos.com
[2]: http://www.onet.pl

## Images

*Basic form:*

![Wow great pic!!](http://unsplash.it/500/500?random "this is tooltip")

*Form with key (reference)*

![Link with reference][pictrue1]

[pictrue1]: http://unsplash.it/500/500?image=1012

*Link to pictrue*

[A link](http://unsplash.it/500/500?image=1000)

*Link with thumbnail*

[![](http://unsplash.it/50/50?image=1000)](http://unsplash.it/500/500?image=1000)

*Link with thumbnail in html style*

[<img src="http://unsplash.it/50/50?image=1000">](ttp://unsplash.it/500/500?image=1000)

*Link with thumbnail in html style with css inline style*

<img src="dog.jpg" width="500" height="500" alt="Dog">

<img src="http://unsplash.it/500/500?image=900" width="500" height="500" alt="Dog">

*Link with thumbnail in html style with css stling*

<img src="dog.jpg" alt="Dog"/>

<style>
    img {
        width: 200px;
        height: 160px;
    }
</style>







