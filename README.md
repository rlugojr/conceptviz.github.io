# Gallery of Concept Visualization

The **Gallery of Concept Visualization** features projects which use pictures to communicate complex and difficult ideas, the same way data visualizations use pictures to make sense of data.

## Contribute

Feel free to <a href='mailto:joshuah@alum.mit.edu'>email</a> with comments, questions, and contributions.

Pull requests are welcome!

There's a build process involved: `build.sh` generates `data.json` from `src/index.yaml` and `index.js` from `src/index.jsx`. You will want to edit those files and then run `build.sh`. Include the build products as part of your PR; the use of github.io demands it!

`build.sh` requires `yaml2json` and `babel`. Both are available from `npm`.

With [http://entrproject.org/](entr), you can set up a nifty auto-build system:

```sh
ls src/* | entr ./build.sh
```
