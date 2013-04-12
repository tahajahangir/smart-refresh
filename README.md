Smart Refresh (Firefox Addon)
=============

Firefox addon to add a toolbar button for re-render the page (without triggering cache reload).

By default when you press F5 (of reload button), all page resources will be revalidated using `If-Modified-Since` header,
but if you want to just *re-render* the page (but not reload it and it's resources) there is no easy way.

This addon adds a toolbar button for *smart* refreshing the page, and also binds `Shift+F5` to this action.
