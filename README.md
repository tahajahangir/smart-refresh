Smart Refresh (Firefox Addon)
=============

Firefox addon to add a toolbar button for smart refresh the page (without triggering cache reload).

By default when you press F5 (of reload button), all page resources will be revalidated using `If-Modified-Since` header, but if you want to just *reload* the page (but not it's resources) there is no easy way. By default you can go to address bar and press enter, but this solution does not work if page url has hash part (#hash-part).

This addon adds a toolbar button for *smart* refreshing the page, and also binds `Shift+F5` to this action
