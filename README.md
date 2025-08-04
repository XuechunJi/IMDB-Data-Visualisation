# IMDB-Data-Visualisation
This repo is for demonstration purposes only.

Visual Encoding of Worldwide Box Office Revenue

- Design Choice 1: Determine the optimal visual encoding for worldwide box office revenue in our Multiview interface.
Chosen Approach:
  - We encode revenue by mapping it to the size and colour value of circles in the scatterplot. Larger or darker circles represent higher revenue, while a complementary colour scale reinforces numerical
differences.
- Justification:
  - Circle size is an intuitively effective channel for conveying magnitude, as supported by  perceptual research and Munzner’s guidelines.
  - The scatterplot simultaneously plots directors (x-axis) and production companies (y-axis), so encoding revenue by circle size fits naturally within this two-dimensional layout.
  - This design adheres to the “overview first, zoom and filter, details on demand” paradigm, ensuring that revenue differences are immediately noticeable without sacrificing space.

Interactive Selection Strategy

Design Choice 2: Decision Definition: Select the most effective method for users to interact with and filter the movie data in a multiview environment.
- Chosen Approach:
  - We support a combined interaction strategy that integrates discrete click selection (via a point selection) with an interval brush (for multi-item selection), while also providing hover-enabled tooltips for immediate feedback.
- Justification:
  - This combined approach allows users to quickly obtain detailed information through
  hover, then click to fix a selection for deeper analysis.
  - The interval brush enables comprehensive multi-object selection, dynamically updating linked views (the ratings bar chart and the contributor tables) and enhancing exploratory analysis.
  - This hybrid interaction aligns with the “overview first, zoom and filter, details on demand” principle, providing adaptability and reducing cognitive load.
  - Empirical studies (e.g., Becker & Cleveland) support the flexibility of such combined strategies over purely click or purely hover interactions.
<img width="1458" height="785" alt="visual" src="https://github.com/user-attachments/assets/4b495ff5-e433-4035-82d4-733cd3f0d702" />
