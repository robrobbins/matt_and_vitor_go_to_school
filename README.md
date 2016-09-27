# matt_and_vitor_go_to_school
Can these kids code at all?

Using any public API that can fetch photos create a single page javascript app that lets me search by any random ass criteria and see a gallery of photos.

## controls

* search - should be able to be a single criteria or multiple (up to you on how to delimit). Maybe a text input with a placholder? Maybe a button somewhere? IDK you play designer. Some instructions might be nice somewhere, maybe a clever tooltip or modal... (tho i really hate modals).
* saved - the user, from the main gallery should be able to save their fave pics somehow to a different list/collection whatever. They should have a way to see only those if they choose. They should be able to add and remove things easily from the "saved" list

## gallery

* Big old bunch of thumbnails, prob not too large as there could be a bunch. There should be a way to see a bigger version of any pic the user wants, so it could be via click and showing a lightbox or some slider to increase the size of a selected photo, again, surprise me.
* pagination - could be many results so paginate this list if its over some reasonable amount. Most decent APIs understand pagination, if you dont then your work just got bigger... Obviously you'll need pagination controls somewhere here. Bonus for shit like `first`, `last`, skipping etc...

### Notes

This does not need any persistance, so it can be client side only, no server or database. In future iterations you could always spin up a server and get fancy...
If you want to have some small persistence you can always look into using the browser's LocalStorage but its not necessary.
