# Is This AI? - Visualizations

This repository contains interactive visualizations and experimental results for the research paper:

**"Is This AI? Exploring the Robustness of AI-Generated Music Detection"**  
Published in *Transactions of the International Society for Music Information Retrieval (ISMIR)*  
DOI: [10.5334/tismir.254](https://transactions.ismir.net/articles/10.5334/tismir.254)

## 🌐 Live Site

Visit the interactive visualizations at: **[https://is-this-ai.github.io/visualizations](https://is-this-ai.github.io/visualizations)**

## 📊 Contents

This repository hosts:

### Interactive Visualizations

- **[UMAP Projections](https://is-this-ai.github.io/visualizations/umap_plots.html)** - Interactive two-dimensional and three-dimensional UMAP projections of the audio feature space, revealing clustering patterns between AI-generated and human-composed music samples.

- **[Audio Analysis Results](https://is-this-ai.github.io/visualizations/audio_analysis_results.html)** - Experimental results from testing the IRCAM Amplify detector's robustness to audio transformations, including filtering and sampling rate conversions.

### Data

- `experiment_samples/` - Audio samples used in the robustness experiments
- `plots/` - Static visualization assets

## 📖 About the Research

This project investigates the robustness of AI music detection systems when audio undergoes various transformations. Key findings include:

- Analysis of how filtering transformations impact detection accuracy
- Evaluation of sampling rate conversion effects on AI detection
- UMAP visualizations revealing the structure of the audio feature space

The experimental methodology involved randomly selecting five samples per source from the test set to evaluate the IRCAM Amplify detector, which demonstrated perfect performance on untransformed audio.

## 🔗 Citation

If you use these visualizations or data in your research, please cite:

```bibtex
@article{isthisai2024,
  title={Is This AI? Exploring the Robustness of AI-Generated Music Detection},
  journal={Transactions of the International Society for Music Information Retrieval},
  year={2024},
  doi={10.5334/tismir.254},
  url={https://transactions.ismir.net/articles/10.5334/tismir.254}
}
```

## 📄 License

Please refer to the published paper for information about data usage and licensing.

## 👥 Contact

For questions or feedback about this research, please open an issue in this repository or contact the authors through the paper's contact information.
