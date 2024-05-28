# jupyter-embedded-visualizer-example

This examples shows how to print custom HTML to the jupyter notebook and display interactive 3D objects.
It embeds the whole runtime inside the jupyter notebook that is totally offline.
This adds a few hundred KB to the jupyter notebook size but it's a constant overhead for each notebook but not for each displayed object.

```sh
# build the frontend
cd hyperion_visual
npm install -dev
npm run build
# or active development:
npm run dev
```

Then you can open `jupyter_display_test.ipynb`.
