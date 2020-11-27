+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Theme 1 Title"
  content = "Theme 1 Subtitle"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "brain.jpg"  # Image path relative to your `static/media/` folder.
  # https://unsplash.com/photos/IHfOpAzzjHM, @avery, 
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Theme 1"
  cta_url = "../theme_1_page"
  cta_icon_pack = "fas"
  cta_icon = "book"

[[item]]
  title = "Theme 2 Title"
  content = "Theme 2 Subtitle"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "twitter.jpg"  # Image path relative to your `static/media/` folder.
    # https://unsplash.com/photos/FVtG38Cjc_k, unsplash.com, @martenbjork
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Theme 2"
  cta_url = "../theme_2_page"
  cta_icon_pack = "fab"
  cta_icon = "twitter"

[[item]]
  title = "Theme 3 Title"
  content = "Theme 3 Subtitle"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "team.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  # https://unsplash.com/photos/FVtG38Cjc_k, unsplash.com, @martenbjork
  
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Theme 3"
  cta_url = "../theme_3_page"
  cta_icon_pack = "fas"
  cta_icon = "comments"
+++
