# Decoding the f-stop: The Hidden Mathematics of Photography" — covering all 6 milestones!
1. Derives the 2 √2​ f-stop sequence from geometry and visualizes aperture area scaling with annotated circles and bar charts.
2. Models the exposure triangle as a linear equation in log-space (EV units), plots the full solution hyperplane for a given EV, and verifies the Sunny 16 rule mathematically.
3. Defines a multi-term cost function with ISO, shutter, and aperture penalties, implements numerical gradient descent in log-space, and visualizes both the loss curve and the 2D cost surface.
4. Simulates scene luminance as a log-normal distribution, implements all three metering modes as statistical estimators, and explains the 18% gray standard from first principles.
5. Builds a full constraint satisfaction solver — encoding photographer rules as hard logical constraints — and ranks valid exposure combinations by a preference score.
6. Wraps everything into a single exposure_advisor() function that takes a scene type and target EV, and returns a recommendation with full mathematical justification.

https://colab.research.google.com/drive/1jobGcoT_IoD9UICKUW5DRJCioXeel5P1#scrollTo=QZPri_rPjC21
