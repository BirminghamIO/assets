# Favicons

Sourced from [Real Favicon Generator](http://realfavicongenerator.net/).

## API options

    {
        "favicon_generation": {
            "api_key": "[TODO: Copy your API key here]",
            "master_picture": {
                "type": "inline",
                "content": "[TODO: Copy the base64-encoded content of the image here]"
            },
            "favicon_design": {
                "ios": {
                    "picture_aspect": "background_and_margin",
                    "background_color": "#4a4a4a",
                    "margin": "25%"
                },
                "desktop_browser": [

                ],
                "windows": {
                    "master_picture": {
                        "type": "inline",
                        "content": "[TODO: Copy the base64-encoded content of the image here]"
                    },
                    "picture_aspect": "white_silhouette",
                    "background_color": "#2b5797",
                    "on_conflict": "override"
                },
                "android_chrome": {
                    "picture_aspect": "shadow",
                    "theme_color": "#4a4a4a",
                    "manifest": {
                        "name": "birmingham.io",
                        "display": "browser",
                        "orientation": "not_set",
                        "on_conflict": "override"
                    }
                }
            },
            "settings": {
                "compression": 1,
                "scaling_algorithm": "Mitchell",
                "error_on_image_too_small": false
            }
        }
    }
