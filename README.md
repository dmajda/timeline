# My Programming Languages Timeline

A timeline of programming languages I’ve used in my life. I made it mostly for
fun and for my own reference.

The timeline includes only languages I learned well and used substantially. I
omitted languages I used only for one-off projects and periods when I used a
language only occasionally.

You can download the timeline in [PNG](timeline.png) and [SVG](timeline.svg)
formats.

## Generating

The timeline is made using [Vega][vega], a declarative language for describing
visualizations. To generate the PNG and SVG images, follow these steps:

1. Install the dependencies:

    ```console
    $ npm install
    ```

2. Use `vg2png` and `vg2svg` to generate the images:

    ```
    $ npm exec vg2png timeline.json timeline.png
    $ npm exec vg2svg timeline.json timeline.svg
    ```

## License

This project is licensed under the [MIT License](LICENSE).

[vega]: https://vega.github.io/vega/
