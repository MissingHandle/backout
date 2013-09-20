Backout
-------
Backout is a small library that lets you marry together Backone.js and 
Knockout.js.
It provides two views, Backout.ModelView and Backout.CollectionView
which allow to pass in a Backbone.model (or collection) and a Knockout template
(for an individual model, in the case of a collection).
the views take care of seemlessly wiring together the backbone's
model attributes with knockout's in-html binding.
they should be close to the last two backbone views you'll ever need :).