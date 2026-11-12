# Music Note Identification from Spectrograms

A 2021 course project exploring whether a convolutional neural network can help identify musical notes from electric-piano spectrograms.

**[Read the original project report](https://tristowww.github.io/MusicNote_CVproject/)** · [Report source](index.html)

The project uses a subset of the Multimodal Sheet Music Dataset (MSMD) to explore the path from audio representations to note sequences and MIDI-style output. The original report describes preprocessing, the model approach, and evaluation through reported precision and recall, visual comparisons, and listening to generated output.

## Project context

The report credits **Sally Owen, Teresa Ristow, and Felipe Restrepo** for the ECE 4554/5554 course project. It preserves the scope and interpretation of that work. The experiments were limited to electric-piano pieces; the report does not establish performance across instruments or a general-purpose transcription system.

## What is in this repository

| Path | Contents |
| --- | --- |
| [index.html](index.html) | Original project question, methods, figures, discussion, and references |
| [images/](images/) | Original diagrams, training screenshots, and visual examples |
| [css/](css/) and [js/](js/) | Assets for the exported Webflow report website |

This is the report website. Training code, model weights, and the MSMD dataset are not included, so the repository alone cannot reproduce the model experiments. Other exported HTML pages contain template material; `index.html` is the project report.

## Preview the report locally

From the repository root:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`. This serves the existing report without running a model or downloading a dataset. Some website assets and media depend on external services.

## Data and interpretation

The [MSMD source project](https://github.com/CPJKU/msmd) provides dataset context and acquisition guidance. The report's figures and claims remain part of the original course project; they have not been re-estimated or independently validated in this presentation update. The original report, website files, and images are preserved.
