# n00k-gallery

Photo cache for the Ascended N00K's Image Recovery console (VRChat).

- `img/NNN.jpg`: one photo per slot, 1024px max, in order.
- `manifest.json`: `count` and `items[]` with `caption`, `by`, `when`, `file`.

The world bakes 64 slot URLs; adding a photo = next `img/NNN.jpg` + a manifest entry. No reupload.
