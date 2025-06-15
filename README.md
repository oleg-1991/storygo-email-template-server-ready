[Live preview](https://oleg-1991.github.io/storygo-email-template-server-ready/)

# storygo-email-template-server-ready

Server-ready HTML email template for StoryGo.  
This version is optimized for integration with Django and other backend frameworks using template rendering.

## Features

- Django-style placeholders: `{{ headline }}`, `{{ deck }}`, `{{ body|safe }}`
- Modular structure: header, content block, footer
- Fully responsive and email-client friendly
- Easily extendable for personalized user content

## Example Usage in Django

```python
context = {
    'headline': 'Breaking News: Major Update',
    'deck': 'Summary of the article goes here.',
    'body': '<p>This is the full article content...</p>'
}
