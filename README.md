# oracle-onnx

ONNX packages of the Magic: The Gathering card art recognition model from
[cfbender/oracle](https://github.com/cfbender/oracle), used by the Command Tower Android app to
recognise cards with the camera.

Each [release](https://github.com/VCap1/oracle-onnx/releases) contains:

- `detector.onnx`: finds the four corners of the card;
- `embed.onnx`: turns the card art into a 128-number vector (the recogniser);
- `search.onnx` and `arts.json`: the gallery of Scryfall art vectors and its index;
- `manifest.json`: file list with SHA-256 checksums.

## Source

These files are derived from oracle by cfbender. Release `1.0` was exported from oracle commit
[`fb6030659bdd5d9e8b60c77456fe55bf14b4cad3`](https://github.com/cfbender/oracle/tree/fb6030659bdd5d9e8b60c77456fe55bf14b4cad3).
The source code of the model, its training and its export is in that repository.

## License

Mozilla Public License 2.0, the license of oracle: see [LICENSE](LICENSE).

Card images and art belong to Wizards of the Coast. This project is not affiliated with, endorsed
or sponsored by Wizards of the Coast or Scryfall.
