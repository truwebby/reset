Reset
=====

Reset the margin, padding and more CSS property, without writing any extra properties or classes.

There are basically two ways of adding <b> "reset" </b> to the project.

1. Using the sass file i.e.<i> reset.scss</i>.
2. Using the css file i.e. <i> reset.css</i>.

<h3>How it works</h3>

Suppose you created a class "xyz" with some properties along with margin and padding. Now you used the same class multiple times in the project but in some cases you don't want margin so you just need to add <i><b> ".no-Mn" </b></i> class in addition to your "xyz", for margin '0'. Similarly for padding also i.e. <i><b> ".no-Pg" </b></i> and so on.

<h3>What are the properties included in v0.01</h3>

- Margin, padding, background, box-shadow, border, top, right, bottom and left.

<h3>Naming Convetion</h3>

Class names are very easy to remember as they are nothing but the first and last alphabet of the property, which can be easily used with first alphabet as uppercase and the last one as lowercase along with hypen as seperation. Such as

- margin -- Mn
- padding -- Pg
- border -- Br
- top -- Tp
- right -- Rt
- bottom -- Bt
- left -- Lt
- box-shadow -- Bx-Sw
- text-shadow -- Tt-Sw

<b>Examples:</b>

    margin: 0 equivalent to ".no-Mn"
    
    padding: 0 equivalent to ".no-Pg"
    
    background: none equivalent to ".no-Bd"
    
    
