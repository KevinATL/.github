# iOS Project defaults

## Xcode

### xcconfig files

- [Build settings](https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj#/itcaec37c2a6)

### Customizing file header comment

- [Customize header comments](https://oleb.net/blog/2017/07/xcode-9-text-macros/) by creating `IDETemplateMacros.plist`.

Copy to one of the following:

- `<PROJECT_NAME>.xcodeproj/xcshareddata/IDETemplateMacros.plist`
- `<WORKSPACE_NAME>.xcworkspace/xcshareddata/IDETemplateMacros.plist`

* [Text macro reference](https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj#/dev7fe737ce0)
* [Text macro format reference](https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj#/devc8a500cb9)


# Default README

<body>
	<table>
		<thead>
			<tr>
				<th>Service</th>
				<th>Status</th>
			</tr>
		</thead>
		<tbody>
		<tr>
				<td>Circle CI</td>
				<td><a href="https://circleci.com/kevnm67/MobileCI">
						<img src="https://circleci.com/gh/kevnm67/MobileCI.svg?style=svg" />
				</a></td>
			</tr>
			<tr>
				<td>Maintainability</td>
				<td><a href="https://codeclimate.com/github/kevnm67/PROJECTNAME/maintainability">
						<img src="https://api.codeclimate.com/v1/badges/PROJECTNAME_ID/maintainability" />
					</a></td>
			</tr>
			<tr>
			<td>Code Coverage</td>
			<td><a href="https://codeclimate.com/github/kevnm67/PROJECTNAME/test_coverage">
					<img src="https://api.codeclimate.com/v1/badges/PROJECTNAME_ID/test_coverage" />
				</a></td>
			</tr>
		</tbody>
	</table>
</body>
<br>

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Setup](#setup)
- [Continuous integration](#continuous-integration)
	- [<img height="24" width="24" src="https://unpkg.com/simple-icons@latest/icons/circleci.svg" /> Circle CI](#img-height24-width24-srchttpsunpkgcomsimple-iconslatesticonscirclecisvg-circle-ci)
- [Features](#features)

<!-- /TOC -->

## Setup

## Continuous integration

### <img height="24" width="24" src="https://unpkg.com/simple-icons@latest/icons/circleci.svg" /> Circle CI

The [config file](.circleci/config.yml) defines multiple jobs and the workflow for circle builds.

## Features

- [ ] Documentation
