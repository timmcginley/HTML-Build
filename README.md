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

Design principles / assumptions are the approach should:

1. Be based on an index.html file that can provide a useful description of the building in a modern browser.
2. Use HTML5 principles to solve building modelling challenges.
3. Provide a common **human editable** file format across softwares / systems following IFC / ISO / National standards as much as possible.
4. Standardise a set of custom entities for building elements. 
5. Be super easy to learn [(from)](https://itc.scix.net/paper/w78-2021-paper-070) and **fun for humans** to hack.
6. Be extendable to Linked data, Speckle streams, IFC.js and other emerging AEC web technologies.

This repo contains a minimal example with the basic CSS file. Other examples will be added soon.

