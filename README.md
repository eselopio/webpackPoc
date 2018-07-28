# Weckpack / React 

Prueba de concepto 

|-- README.md
|-- database
|   |-- constants.js
|   |-- queries
|   |   |-- CreateArtist.js
|   |   |-- DeleteArtist.js
|   |   |-- EditArtist.js
|   |   |-- FindArtist.js
|   |   |-- GetAgeRange.js
|   |   |-- GetYearsActiveRange.js
|   |   |-- SearchArtists.js
|   |   |-- SetNotRetired.js
|   |   |-- SetRetired.js
|   |   `-- db.js
|   `-- seeds
|       `-- artist.js
|-- dist
|   |-- 0.fca1a3070a51529c787ejs
|   |-- 1.db40a625217547a825f8js
|   |-- 2.88a7d26a88f7e7705030js
|   |-- bundle.31a1df63a29e95ac1b8cjs
|   |-- index.html
|   |-- manifest.f444e4d3965688e823f7js
|   `-- vendor.e9bf42a1eefb058c9d3bjs
|-- package-lock.json
|-- package.json
|-- server.js
|-- src
|   |-- actions
|   |   |-- index.js
|   |   `-- types.js
|   |-- components
|   |   |-- Header.js
|   |   |-- Home.js
|   |   |-- artists
|   |   |   |-- ArtistCreate.js
|   |   |   |-- ArtistDetail.js
|   |   |   |-- ArtistEdit.js
|   |   |   |-- ArtistFilter.js
|   |   |   |-- ArtistIndex.js
|   |   |   |-- ArtistMain.js
|   |   |   `-- Paginator.js
|   |   `-- filters
|   |       |-- Picker.js
|   |       |-- Range.js
|   |       |-- Switch.js
|   |       `-- index.js
|   |-- index.html
|   |-- index.js
|   |-- reducers
|   |   |-- ArtistsReducer.js
|   |   |-- ErrorReducer.js
|   |   |-- FilterCriteriaReducer.js
|   |   |-- SelectionReducer.js
|   |   `-- index.js
|   `-- router.js
|-- style
|   |-- materialize.css
|   |-- react-range.css
|   `-- style.css
`-- webpack.config.js

scripts
```
npm run clean  // rm /dist
npm run build // npm run clean && webpack -p
npm run server

```
