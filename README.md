# This is a reproduction of the build watch mode

### Reproduction

1. Clone this repo
2. Run yarn
3. Run yarn watch
4. Check dist folder after first build. It contain all files.
5. Make any changes in App.vue to trigger rebuild. Check dist folder agin,css file is missing.If you change a.css,after rebuilding,the contents of css in dist will not include the contents of b.css.
