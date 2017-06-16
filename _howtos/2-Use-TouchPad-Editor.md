---
layout: howto
title: "Writing and Drawing On A Touchpad"
---

* [Overview](#overview)
* [Freeform Writing or Drawing](#freeform-writing-or-drawing)
* [Drawing Straight Line](#drawing-straight-line)
* [Drawing Rectangle or Ellipse](#drawing-rectangle-or-ellipse)
* [Drawing Polygon](#drawing-polygon)
* [Entering Text](#entering-text)
* [Entering Math Symbols](#entering-math-symbols)
* [Changing Stroke Width, Stroke Color and Fill Color](#changing-stroke-width-stroke-color-and-fill-color)
* [Selecting and Modifying a Shape](#selecting-and-modifying-a-shape)
* [Cleaning Up The Drawing Area](#cleaning-up-the-drawing-area)
* [Undo/Redo The Last Change](#undo-redo-the-last-change)
* [Preview The Page](#preview-the-page)

## Overview
The Leetmath Touchpad editor is optimized for performing quick drawings and showing rough work. In this regard,
it emulates drawing and scribbling on paper or a whiteboard, much like a sketching application. Where it differs
from most such applications is its support for drawing geometric shapes such as lines, rectangles, circles,
polygons and LateX based mathematical equations.

The editor is in _normal mode_ when the page loads and shows only the _Tools Tab_ 
(<img src="/assets/guide/images/touchpad/tool-tab.png" height="24px" alt="Tool Tab" style="vertical-align: middle;"/>). 
Touching the tab expands the _Tool Box_ and shows all the available tools. The picture below shows the expanded 
Tool Box and identifies the various tools.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/tool-box-annotated.png"/></center>

The Tool Box can be moved around anywhere on the page in both minimized and expanded forms by dragging the Tool Tab. This allows
full use of the editor area for drawing and scribblings.

In the normal mode, you can zoom-in or zoom-out the page by touching the drawing area with two fingers and
moving them apart or bringing closer to each other. You can also scroll vertically or horizontally by swiping.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/zoom-drawing-area.png"/></center>

The editor enters into _drawing mode_ when you activate a tool by touching the tool icon. The activation
is indicated by slight graying out of the tool icon. Zooming and scrolling 
is not possible in this mode as the effect of touch event depends on the activated tool. Touching the tool again
deactivates the tool and the icon reverts back to its original form.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/activated-deactivated.png"/></center>

## Freeform Writing or Drawing

Activate the _Pencil Tool_ and use your finger or a stylus to write or draw anywhere on the drawing area. Deactivate the
tool when you are done. Tip: You can zoom-in in the _normal mode_ before using the pencil tool to make better
use of the drawing area.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/touchpad-hand-drawing.png"/></center>

## Drawing Straight Line

Drawing a straight line is quite straight forward: activate the _Line Tool_ and touch at any point on the drawing area
and drag. Ending the drag completes the line.

## Drawing Rectangle or Ellipse

Activate the _Shapes Tool_. This exposes the _Rectangle_ and _Ellipse_ tools. Using these is fairly straight forward. Activate the
specific tool, touch a point on the drawing area and drag.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/drawing-rectangle-and-ellipse.png"/></center>

## Drawing Polygon

Activate the _Polygon Tool_, touch at a point, drag and lift and repeat. The first touch point becomes the starting
point and each subsequent lift point becomes a corner. The polygon could be a closed one (ie; the last point coincides with
the first point) or an open one. If you select a fill color before drawing the polygon, or even in the middle, then the
polygon will be filled with the selected color.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/drawing-polygon.png"/></center>

## Entering Text

Activate the _Text Tool_ and touch the drawing area. A text entry box appears. Use on screen keyboard to type-in the text. Note that
the in-progress text is within a dotted rectangular area. Deactivating the _Text Tool_ finalizes the text and the dotted rectangular
area disappears. The picture below shows this sequence, with the added steps to minimize and maximize the toolbox.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/typing-text.png"/></center>

_Known Limitation: You cannot change font, size or color of the text._

## Entering Math Symbols

One of the unique features of Leetmath Touchpad editor is that you can type-in math as a LaTeX expression. Just activate the _Math Tool_ and
touch the drawing area. A Math dialog box appears. Type-in the Latex expression and verify it in the preview area. 
You can also use the menu items to build the expression. Touching Okay transfers the image of the Latex expression to the drawing area.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/entering-math.png"/></center>

Visit [Leetmath Math Editor](#) editor for more on how to use this awesome tool.

## Changing Stroke Width, Stroke Color and Fill Color

Changing stroke width, stroke color and fill color follow the same sequence of steps: activate the tool and then select the
desired width or color from newly exposed icons. Subsequent shapes are drawn with the current stroke width, stroke color and fill color.
This is illustrated in the following picture.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/change-width-color.png"/></center>

## Selecting and Modifying A Shape

To select a shape, activate the _Selection Tool_ and touch the shape. A dotted box appears around the selected shape.
You can now change the position of the shape by dragging it around. You can also change its stroke width, stroke color or
fill color by activating the corresponding tool and selecting the value.

To delete the selected shape, activate the _Delete Selected Tool_.

_Known Limitation: You cannot change size of a selected shape._

## Cleaning Up The Drawing Area

This is super simple: just activate the _Cleanup Tool_.

## Undo/Redo The Last Change

The obvious action of activating the _Undo Tool_ reverts the last operation and activating the _Redo Tool_
after undoing an action cancels the effect of the _Undo Tool_.

## Preview The Page

On small touchpad devices such as a smart phone, the full drawing area is much larger than what is currently visible. 
On such devices, you can use the _Preview Tool_ to view the a one-fourth view of the full drawing area. Recall that you can scroll, either
vertically or horizontally, in non-editable mode to bring invisible area into view.

<center><img alt="Annotated Tool Box" src="/assets/guide/images/touchpad/preview.png"/></center>

Happy drawing on a Touchpad device!