# Projection Mapping Guide

Projection mapping is a technique that uses software to project images or videos onto irregularly shaped surfaces, turning objects into dynamic displays.

## 1. Download TouchDesigner (Free Version)

1. Go to [TouchDesigner Download Page](https://derivative.ca/download).
2. Click **Download** under the Free Non-Commercial license.
3. Install TouchDesigner on your computer.

## 2. Import a Movie File

1. Open TouchDesigner.
2. Drag a **Movie File In TOP** from the left panel into your network.
3. Click the Movie File In node and select your video file.

## 3. Use Kantan Mapper for Projection Mapping

1. Right-click in the network and add a **Kantan Mapper** node.
2. Connect the output of your Movie File In TOP to the input of Kantan Mapper.
3. Double-click Kantan Mapper to open its interface.
4. Use the tools to draw shapes over your projection surface.
5. Assign your video to the shapes for mapping.

## 4. Preview and Adjust

1. Connect Kantan Mapper’s output to a **Window COMP** to preview.
2. Adjust shapes and video placement as needed.
3. Project onto your physical surface.
