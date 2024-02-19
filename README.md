# WebQC: Quality Control for Genomic Data

WebQC is an innovative, web-based tool designed to facilitate the quality control of raw data files across various domains including genomics, transcriptomics, proteomics, and metabolomics. It offers a seamless, user-friendly interface that allows researchers to upload and analyze their data files directly within the browser, ensuring data privacy and security by processing data locally on the user's computer.

## Features

- **Support for Multiple Data Types**: WebQC supports a wide range of file formats prevalent in biological data analysis, such as FASTQ, FASTA, BAM, and GZ.
- **Interactive Reports**: The tool generates comprehensive quality control reports featuring interactive visualizations for metrics like Per Base Sequence Quality, GC Content, Sequence Length Distribution, and more, using Plotly for dynamic data representation.
- **Data Repository Integration**: WebQC integrates with various data repositories including ENA for genomics, GEO for transcriptomics, Metabolight for metabolomics, and PRIDE for proteomics, enabling users to compare their data with existing datasets.
- **Drag-and-Drop Interface**: Users can easily upload their files using a simple drag-and-drop interface, enhancing the user experience and streamlining the data analysis process.

## Getting Started

To use WebQC, simply navigate to the tool's webpage and drag and drop your raw data files into the designated upload area. The tool will automatically process your files and generate detailed quality control reports without the need for any data to leave your browser.

For more detailed instructions and examples, please visit the [WebQC GitHub repository](https://github.com/xiaoranzhou/qc).

## License

WebQC is open-source software licensed under the GPL-3.0 license, allowing for widespread use and modification within the constraints of this license.

## Contributing

Contributions to WebQC are welcome! If you're interested in improving the tool or adding new features, please feel free to fork the repository, make your changes, and submit a pull request. For more information on contributing, please read the CONTRIBUTING.md file in the repository.

## Support

If you encounter any issues or have questions about using WebQC, please open an issue on the [GitHub issue tracker](https://github.com/xiaoranzhou/qc/issues). Our team is dedicated to providing support and ensuring that WebQC meets the needs of the research community.

## Acknowledgments

WebQC is part of the NFDI4Plants community, which aims to provide valuable resources and tools for plant research. We thank all contributors and users for their support and feedback, which help us improve WebQC continuously.
- Output: multiQC and fastQC like + spider or radar plot from Hannah Dörpholz 
- Input: fastq, gz, bam, or a folder. maximal file size 3.98GB (in theory it could take 4GB but I only found a 3.98GB file to test)
- WASM: compiled from FALCO https://github.com/smithlabcode/falco
- Visualization: customized plotly
 
 
