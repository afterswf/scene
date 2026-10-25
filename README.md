# AwayJS Scene

This is [Mesmotronic](https://mesmotronic.com)'s fork of [awayjs/scene](https://github.com/awayjs/scene) for
[AfterSWF](https://github.com/afterswf/embed), published as [`@afterswf/scene`](https://www.npmjs.com/package/@afterswf/scene).
Its fixes are listed in [AfterSWF's README](https://github.com/afterswf/embed#more-advanced-as3-content).

It keeps the original package names in its imports, so install it, and any other afterswf packages you use, under
their original names with npm aliases:

```sh
npm install @awayjs/scene@npm:@afterswf/scene
```

[![Build Status](https://travis-ci.org/awayjs/scene.svg?branch=dev)](https://travis-ci.org/awayjs/scene)

Dependency for AwayJS applications requiring a heirarchical scenegraph: contains data structures for a collection of display object types, as well as geometric prefabs for simple 2D & 3D objects.

## Documentation

[Official AwayJS Documentation](https://awayjs.github.io/docs/scene)

## AwayJS Dependencies

* core
* graphics

## Internal Structure

* adapters<br>
used for scripting

* base<br>
Enums for various display object settings, root data classes for timeline and touch data

* bounds<br>
(to be moved to view module)

* controllers<br>
Custom interaction controls for display objects

* display<br>
display objects that can be added to a scene heirarchy, including basic billboards, lines and text, as well as more configurable Sprite objects that expose the graphics API

* errors<br>
Error types

* events<br>
Event objects for scene classes

* factories<br>
Interface for timelines

* lightpickers<br>
Objects for selecting lightsources (to be moved to materials module)

* managers<br>
manager classes for fonts and frame scripts

* prefabs<br>
Generator clases for simple display objects such as Cube, Sphere, Torus etc

* shadowmappers<br>
Helper classes for shadows (to be moved to materials module)

* text<br>
Helper classes for text

* tools<br>
Merge tool for combining display objects (or a heirarchy of display objects) into a single sprite

* utils<br>
Cast tool for converting data types (deprecated)

