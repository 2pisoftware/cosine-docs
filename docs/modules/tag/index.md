# Tag Module

The Tag module provides functionality related to tagging objects in Cosine.
A tag is a string - typically user provided - associated with any database object.

The tag module provides a [partial](#TODO) that displays and allows editing of the tags associated with an object.

The first 3 tags are always displayed, while additional tags are only displayed on hover.
When the tag list is clicked, a modal is opened that allows adding, removing, or creating new tags.

## Usage

The partial is named `listTags` on the `tag` module.
It takes a single argument `object`, the database object to render the tags for.

```php
$w->partial("listTags", ["object" => $your_object], "tag");
```