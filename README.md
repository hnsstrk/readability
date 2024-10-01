# Readability Index Color Experiment

This project is a **static webpage** designed to experiment with text colors adjusted according to **readability scores** against fixed background colors. The aim is to test how the readability index (ARI - Automated Readability Index) colors perform on different background shades such as light, dark, white, and dark blue.

This experiment specifically addresses the readability color misalignment issue discussed in the [Zettlr issue #5355](https://github.com/Zettlr/Zettlr/issues/5355). The goal is to better match readability colors with their intended purpose—such as green for easy-to-read text and red for difficult-to-read text—while testing them across various background colors. This project helps visualize and correct the discrepancy in readability mode colors observed in the Zettlr software.

## Features

- **Readability Index Colors**: Text is color-coded based on the ARI readability score, ranging from very readable (green) to difficult to read (red).
- **Fixed Background Colors**: The text is tested against the following fixed background colors:
  - Light Mode (`#F3F3E8`)
  - Dark Mode (`#14141E`)
  - White Background (`#FFFFFF`)
  - Dark Blue Background (`#002B36`)
- **Comparison Layout**: The webpage presents side-by-side comparisons of how readability index colors appear on different backgrounds.

## Project Structure

The webpage contains the following sections:
- **Readability Index Legend**: An explanation of the ARI readability score system and corresponding color codes.
- **Background Testing**: Four sections, each with a different fixed background color (light, dark, white, and dark blue), containing the same text styled according to the readability index.

## Usage

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/hnsstrk/readability.git
    ```
2. Open the `index.html` file in any modern web browser to view the webpage.
3. Explore how different readability index colors perform against fixed background colors.

## Purpose

The purpose of this project is to provide a simple, visual tool for testing how readability index colors work against different background colors. This experiment is particularly useful for projects like [Zettlr](https://github.com/Zettlr/Zettlr), where color schemes are vital for indicating readability but have faced challenges in accurate color representation.

## Contributions

Contributions are welcome! Feel free to:
- Suggest additional background colors or readability color schemes.
- Enhance the project with new readability metrics or additional features.

## License

This project is licensed under the BEER-WARE License - see the [LICENSE](LICENSE) file for details.