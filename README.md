# ros2_snippets

[https://marketplace.visualstudio.com/items?itemName=HansRobo.ros2-snippets]()

## How to test locally

1. Clone this repository
2. Run`npm install` in root directory of this repository
3. Open this repository with VSCode
4. Press`F5` button

## How to publish(for publisher)

Before publish, please check the version number in package.json.　　

```bash
npm install -g vsce
vsce package
vsce publish
```

## RoadMap

See [roadmap.md](roadmap.md)
