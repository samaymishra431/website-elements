🧾 Final Detailed Prompt for Hero Slider Section (with animations & fade effect)

Prompt:

Create a modern responsive hero slider section using Bootstrap 5.
The slider should contain 3 slides, each with a full-screen background image, a dark semi-transparent overlay, and centered animated text content.

Each slide must include:

A bold H1 heading (animated to fade/slide in when the slide appears).

Two lines of paragraph text below the heading.

A “Read More” button that is transparent with a white border and changes to a solid white background with dark text on hover.

Functional & Visual Requirements:

The carousel should use Bootstrap’s fade transition (carousel-fade class) for a smooth dissolve effect between slides.

The carousel should auto-slide every 4 seconds (data-bs-interval="4000").

Include left and right arrows for manual navigation.

Add carousel indicators (dots) at the bottom.

Each slide should have a black overlay using rgba(0, 0, 0, 0.55) to enhance text readability.

The carousel height should be 90vh (90% of viewport height).

The text should be perfectly centered vertically and horizontally.

The content (heading, paragraph, button) should remain padded from both sides on mobile, so it never touches the screen edges.

The text should scale responsively (use smaller fonts on tablets and mobiles).

Use Bootstrap 5.3 CDN for both CSS and JS.

Animation Details:

The heading should animate in on each slide (e.g., fade-up or slide-in animation).

The animation should be subtle and smooth, using CSS keyframes or Bootstrap animation classes.

The paragraph and button can also have a slight fade-in delay for a layered effect.

Additional Styling Requirements:

Button design:

Transparent with a white border by default.

On hover → white background and black text.

Slightly rounded corners.

White text color for heading and paragraph.

Proper spacing and alignment for all content.

Technical Notes:

Use inline background images for each slide (3 different Unsplash URLs).

Include all custom CSS inside <style> tags in the same file.

Ensure everything is mobile-first and responsive.

Provide complete HTML code (from <!DOCTYPE html> to </html>).
