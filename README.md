# Skelett MContainer
A barebones (German: Skelett) media query library without any styling.

See other Skelett tools [skelett-flexbox-grid](https://github.com/kaspar-allenbach/skelett-flexbox-grid) and [sekelett-media-queries](https://github.com/kaspar-allenbach/skelett-media-queries).


## The Skelett
- The Skelett repos are a bunch of standalone scss libraries without any styling so they don't interfere with your very beautiful project.
- No padding
- No margin
- no colors
- no nothing
- ITCSS naming to prevent style injections

# Container

Add the container class `o.container` around your stuff. This will center everything and ads padding from `md__down` to have some breathing room on smaller devices

## Inner Outer + Fluid

- All containers ar always centered 
- `.o-container` standard container. locks at `$lg-width` 
- `.o-container-fluid` go full width until the the very end
- `.o-container-inner`  smaller container than standard but locks at `$md-width`
- `.o-container-lock-XX__up` locks the container size at your requested media query size. 
- Use all classes also as an extend  
