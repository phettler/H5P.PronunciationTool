# H5P Pronunciation Tool

A fork of H5P Audio Recorder for the purpose of creating a vocabulary list to practice pronunciation

## Getting started

Grab all the modules:

```bash
git clone https://github.com/phettler/H5P.PronunciationTool.git
cd H5P.PronunciationTool
npm install
```

## Developing
Build project for production:

```bash
npm run build
cd ..
h5p increase-patch-version H5P.PronunciationTool 
h5p pack H5P.PronunciationTool h5p-pronunciation-tool.h5p
```

Then upload `h5p-pronunciation-tool.h5p` to library.

Run tests:

```bash
npm test
```

## Translating

Help translate h5p-audio-recorder on [crowdin.com](https://crowdin.com/project/h5p-audio-recorder).

If your language isn't on the list, feel free to make a post in the community [forum](https://h5p.org/forum/6).

## License

*H5P Audio Recorder* is [MIT licenced](LICENCE.md)
