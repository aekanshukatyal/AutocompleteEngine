# Autocomplete-Engine

This Project is built from scratch. No APIs no Libraries.

This is a implementation of the autocomplete feature using Tries.

I've implemented a Dictionary which consists of 10,000 most frequent used english words.

I've also added the functionality to choose a file of your own.


To run this just download the jar file and choose the correct-word file.

Word files are present in src/resources

File must be in txt format.

To use this:

in the Service class

```
  String[] words = 'your words';
  buildTrie(words)
```

The working:

![output_6czhqM](https://user-images.githubusercontent.com/10860936/55694884-d7806c00-59d3-11e9-9cf8-4d6bf495f675.gif)
