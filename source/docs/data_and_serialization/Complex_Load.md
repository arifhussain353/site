title: Load HTML5 Canvas Stage from JSON Tutorial
---

To load a complex stage that originally contained images and event bindings using Konva,
we need to create a stage node using `Konva.Node.create()`, and then set the
images and event handlers with the help of selectors using the `get()` method.
Images and event handlers must be manually set because they aren't serializable.

{% iframe /downloads/code/data_and_serialization/Complex_Load.html %}

{% include_code Konva Load Complex Stage Demo data_and_serialization/Complex_Load.html %}
