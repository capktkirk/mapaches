+++
class_gallery = ["/uploads/background.jpg"]
title = "index.md"
welcome_to_rosedale_ = "??????????????????"

+++
<!DOCTYPE html>
<html lang="{{ $.Site.LanguageCode}}">
  <head>
    {{ partial "header.html" . }}
    <title>{{ $.Site.Title }}</title>
  </head>
  <body>
      {{ partial "navbar.html" . }}
      {{ partial "home.html" . }}
      {{ partial "footer.html" . }}
  </body>
</html>