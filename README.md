# fpg-photoshoot

## Getting Started
1. Clone the repository.
```bash
git clone git@github.com:akhale3/fpg-photoshoot.git
```
2. Use the `template.json` file as reference to append information in the
`photoshoot.json` file.

## Template
```json
{
  "locations": [{
    "name": "Location Name",
    "address": "Location Address",
    "scenes": [{
      "name": "Scene Name",
      "description": "Description of the scene layout",
      "actors": [
        "Actor 1",
        "Actor 2"
      ],
      "props": [
        "Property 1",
        "Property 2"
      ],
      "background": "Background for the scene",
      "storyboard": {
        "layout": "Positions of the props and actors in relation to the background",
        "angles": [
          "Camera angle 1 to shoot from",
          "Camera angle 2 to shoot from"
        ],
        "time": "Time of day to shoot at",
        "comments": [
          "Comments from the photographer",
          "Comments from the director"
        ]
      }
    }]
  }]
}
```
