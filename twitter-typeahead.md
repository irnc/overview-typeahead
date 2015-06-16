* https://github.com/twitter/typeahead.js

* Beware of `_` variable in sources, it is not `lodash`, it is internal utils defined in [`src/common/utils.js`][utils].

[utils]: https://github.com/twitter/typeahead.js/blob/master/src/common/utils.js

## Typeahead

* `Dateset`
  * `options`
    * `templates`
    * `source` required
    * `node` required
      * jQuery-wrapped at `this.$el`
    * `name`
    * `highlight`
    * `limit`
    * `display`, `displayKey`
    * `async`
* Bloodhound as `source`
  * https://github.com/twitter/typeahead.js/commit/a41ee5ae4e945d4f22284fa9069ce584220aa7fd

## Bloodhound

* https://github.com/twitter/typeahead.js/blob/master/doc/bloodhound.md
* _internal search index_

### `tokenizers`

* `whitespace`
* `obj.whitespace()`
* see https://github.com/twitter/typeahead.js/blob/master/src/bloodhound/tokenizers.js
