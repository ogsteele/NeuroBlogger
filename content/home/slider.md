+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Ready to start reading?"
  content = "Head straight over to the blog"
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
  cta_label = "Neuroblog"
  cta_url = "https://sourcethemes.com/academic/"
  cta_icon_pack = "fas"
  cta_icon = "book"

[[item]]
  title = "Stay up to date"
  content = "Follow us on Twitter"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "twitter.jpg"  # Image path relative to your `static/media/` folder.
    # https://unsplash.com/photos/FVtG38Cjc_k, unsplash.com, @martenbjork
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Follow @BloggerNeuro"
  cta_url = "https://twitter.com/BloggerNeuro?ref_src=twsrc%5Etfw"
  cta_icon_pack = "fab"
  cta_icon = "twitter"

[[item]]
  title = "Got an idea or comment?"
  content = "Get in touch, we'd love to hear from you!"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "team.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  # https://unsplash.com/photos/FVtG38Cjc_k, unsplash.com, @martenbjork
  
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get in touch!"
  cta_url = "#contact"
  cta_icon_pack = "fas"
  cta_icon = "comments"
+++
