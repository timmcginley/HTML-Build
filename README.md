# Building description using custom HTML entities
Developed based on conversations with [JosepMariaPujol](https://github.com/JosepMariaPujol/HTML-Build)
for his super awesome thesis project.

The idea is to use custom HTML entities to represent (ifc) building entities with minmal CSS to define layers of attributes and properties.

```HTML
<html>
	<head> <!--- this contains property links and entity attributes in css ---> </head>
	<body>
		<project->
			<site->
				<building->
					<core->
						<floor-></floor->
					</core->
				</building->
			</site->
		</project->
	</body>
<html>
```

![html-build-basic](img/preview.png)

Design principles / assumptions are.

1. The index.html file should be able to be opened in a modern browser and provide a useful description of the building
2. Use HTML5 principles to solve building modelling challenges
3. Follow IFC / standards as much as possible
4. Super easy to learn and fun for humans to hack
5. Provide a common file format across softwares / systems

This repo contains a minimal example with the basic CSS file. Other examples will be added soon.

