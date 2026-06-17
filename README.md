# SpacePlanner

**An interactive, to-scale planning tool for laying out any space — a garden, a room, a patio, an entire property.** Draw the boundaries of your space, drop in accurately-sized objects, and see exactly how everything fits before you move a single real-world thing.

SpacePlanner runs entirely in your browser. There's nothing to install, no account to create, and your work saves automatically on your own device.

> SpacePlanner™ · © MYS · All rights reserved.

---

## Table of contents

- [What it's for](#what-its-for)
- [Quick start](#quick-start)
- [Core concepts](#core-concepts)
- [The toolbar](#the-toolbar)
- [Outlines — defining your space](#outlines--defining-your-space)
- [Objects — everything you place](#objects--everything-you-place)
- [Distance lines](#distance-lines)
- [Grouping objects](#grouping-objects)
- [The Measure tool](#the-measure-tool)
- [Saving, sharing & backups](#saving-sharing--backups)
- [Keyboard shortcuts](#keyboard-shortcuts)
- [A worked example](#a-worked-example)
- [Tips & good to know](#tips--good-to-know)
- [FAQ](#faq)

---

## What it's for

SpacePlanner answers the question *"will this actually fit, and where should it go?"* — accurately, before you commit.

Everything is drawn **to scale**, so a 3 m garden bed takes up exactly three of the one-metre grid squares, and the gap you see between a shed and a fence is the real gap. Typical uses:

- Garden and landscape layout (beds, trees, paths, patios, sheds)
- Room and furniture planning
- Driveways, parking, and outdoor areas
- Any project where you need to place real, measured things in a real, measured space

It works best on a **laptop or desktop** — the canvas and side panels need room to breathe.

---

## Quick start

1. **Open the app.** You'll see a demo plot (a 10 × 7 m rectangle) on a one-metre grid.
2. **Shape your space.** Click **Edit outline** and adjust the corners and side lengths to match your real space, then lock it.
3. **Add objects.** Click **Objects**, create something with real dimensions (say a 2 × 3 m patio), and place it.
4. **Position precisely.** Drag it, nudge it with the arrow keys, or type its exact distance from each wall.
5. **It's already saved.** Your layout is stored on your device automatically. Use **Export** to make a backup file you can keep or share.

That's the whole loop: *outline → objects → position → done.*

---

## Core concepts

A few ideas make everything else click into place:

**Everything is to scale.** The canvas works in real-world measurements (metres and centimetres, European style). The background grid is your ruler — by default each square is one metre, and it adapts as you zoom.

**The canvas is infinite.** Pan by dragging empty space, zoom with your scroll wheel. **Fit to view** reframes everything neatly whenever you get lost.

**There are three things you work with:** *outlines* (the boundaries of your spaces), *objects* (the items you place inside them), and *measurements* (a ruler for spot-checking distances). Each has its own button in the toolbar.

---

## The toolbar

Across the top:

| Button | What it does |
|---|---|
| **Edit outline** | Draw and reshape the boundaries of your space(s) |
| **Objects** | Create, place, and manage the items in your space |
| **Measure** | A two-click ruler for measuring any distance |
| **↶ Undo / ↷ Redo** | Step backward or forward through your changes |
| **Fit to view** | Reframe the canvas so everything is visible |
| **Export** | Download your whole layout as a file |
| **Import** | Load a layout file back in |

---

## Outlines — defining your space

An **outline** is the boundary of a space — your garden fence line, the walls of a room, the edge of a driveway. You can have **as many outlines as you like**, each with its own name and colour. For example: *Back Garden*, *House*, *Driveway*, *Front Garden* — all on the same canvas.

### Drawing an outline

Click **Edit outline**. You build the boundary out of **corners** (numbered 1, 2, 3…) connected by **sides** (lettered A, B, C…).

- **Add corner** drops a new corner onto the canvas.
- **Drag any corner** to shape the boundary by eye.
- **Type an exact side length** in the side list to set that wall precisely — drag to get close, then type the exact number.
- **Start from rectangle** gives you a clean four-corner box to reshape, which is the fastest start for most spaces.

> **Example — an L-shaped garden:** Start from rectangle, then add two more corners and drag them to carve out the "notch" of the L. Set each side's exact length in the side list until it matches your real measurements.

When it matches your real space, click **🔒 Lock this outline**. Locking fixes it in place so you can't nudge it by accident while placing objects. The panel then shows a summary — number of sides, bounding box, and total area in m². Click **🔓 Unlock to edit** any time to change it again.

### Multiple outlines

Each outline appears in the **Outlines list** at the top of the panel. From there you can:

- **Switch** which outline you're editing (click its row)
- **Rename** it (click the name and type)
- **Recolour** it (click the colour swatch)
- **Delete** it (🗑)
- **Add** another (**+ New outline**)

Each outline is filled with a soft, textured tint in its own colour so you can tell your zones apart at a glance.

---

## Objects — everything you place

An **object** is anything you put inside your space: a tree, a flower bed, a patio, a shed, a sofa, a parking spot. Objects are **circles, squares, or rectangles**, each drawn to its real size.

### Creating an object

In the **Objects** panel:

1. Give it a **name** (e.g. "Apple tree").
2. Choose a **shape** — Rectangle, Square, or Circle.
3. Enter its **dimensions** (width × length, a single side, or a diameter).
4. Pick a **colour**.
5. Click **+ Create & place** — it appears in the middle of your view, scaled correctly.

Each object shows its **name and dimensions** right on the canvas (e.g. "Apple tree · ⌀ 2 m").

### Moving and adjusting

Once an object is on the canvas:

- **Drag** its body to move it. (This works even with the Objects panel closed.)
- **Drag a corner handle** to resize it. Circles stay round.
- **Drag the handle on the stalk above** it to rotate.
- **Arrow keys** nudge the selected object **1 cm per tap** — hold **Shift** for 10 cm. Perfect for fine alignment.

### The object list

Every object appears as a row in the panel. Each row has:

- A **checkbox** (for grouping — see below)
- A **drag grip (⋮⋮)** — drag rows up and down to set **stacking order**. **Top of the list = in front**, so you control which object overlaps which.
- A **▸ expand arrow** — opens that object's detail editor
- **Duplicate (⧉)**, **Lock (🔒/🔓)**, and **Delete (🗑)**

### Editing an object's details

Click the **▸** on a selected object to open its editor, where you can change (when the object is unlocked):

- **Name** and **colour**
- **Size** — type exact dimensions
- **Position by distance** — type how far the object's centre should sit from each wall (left / right / up / down). Type "2" in the *left* box and the object jumps so its centre is exactly 2 m from the left wall.

The editor also shows a live read-out of the object's distance to each wall, and which outline it's currently inside.

> **Tip:** Lock an object (🔒) once it's exactly where you want it. Locked objects can't be moved or resized by accident, but you can still see them and their distances.

---

## Distance lines

Whenever you **select an object**, four dashed lines appear, running from its centre out to the four walls of the outline it sits inside — up, down, left, and right — each labelled with the real distance.

These update **live as you drag**, so you can position something by watching the numbers change. They're a fast way to answer "how far is this tree from each fence?"

A few details:

- Lines only appear when the object's centre is **inside an outline**. Drag it onto open canvas and they disappear.
- Each object measures only to **its own outline** — an object in the *House* never measures to the *Garden*.
- For a **group**, the lines measure from the group's overall centre (see below).

---

## Grouping objects

If several objects belong together — a cluster of plants, a table with its chairs — you can **group** them so they move as one.

1. **Tick the checkboxes** of two or more objects in the list.
2. Click **Group checked**.

Grouped objects get a small coloured **G#** badge. Now:

- **Dragging or nudging any member** moves the whole group together.
- **Clicking any member** selects the entire group.
- The **distance lines** measure from the group's overall centre to the walls.

To break a group up, tick one of its members and click **Ungroup**.

> **Example:** Group a patio table with its four chairs. Now you can shuffle the whole dining set around the patio to find the best spot, and they keep their arrangement.

---

## The Measure tool

The **Measure** tool is a free ruler for checking any distance — independent of objects.

1. Click **Measure**, then **+ New measurement**.
2. Click two points on the canvas. A red dot marks each, and the distance shows on the line.

You can place **as many measurements as you like**, and they all stay visible. Other features:

- **Snapping** — points snap to nearby outline corners and object centres, so "fence corner to tree" is exact, not approximate.
- **Edit after the fact** — drag the red endpoints to reposition, or type an exact length in the measurement's box to resize it.
- **Lock (🔒)** a measurement to keep it; **Clear all** removes the unlocked ones and keeps the locked ones.
- **Delete (🗑)** removes a single measurement.
- Press **Escape** to cancel a measurement mid-placement.

> **Example:** Measure the clear path between two flower beds to check a wheelbarrow will fit — click the edge of one bed, then the other, and read the gap.

---

## Saving, sharing & backups

**Your work saves automatically** to your own browser, on your own device, every time you make a change. Close the tab, come back later, refresh the page — your layout is still there.

A few important things to understand about how this works:

- **Saving is per-device and per-browser.** Your layout lives in the browser you're using. It is *not* automatically shared between computers or people.
- **To move a layout between devices or share it with someone**, use **Export** — it downloads a small `.json` file containing your whole plan. The other person (or your other computer) opens SpacePlanner and clicks **Import** to load it.
- **Export is also your backup.** If you ever clear your browser data or switch laptops, that file is how your layout survives. It's good practice to export a copy after a big session.

> **Sharing example:** You design the garden on your laptop and click **Export**. You send the `garden.json` file to your partner. They open the same SpacePlanner link, click **Import**, and see your exact layout — which they can then tweak and export back to you.

---

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| **Arrow keys** | Nudge selected object 1 cm |
| **Shift + Arrow keys** | Nudge selected object 10 cm |
| **Ctrl / ⌘ + Z** | Undo |
| **Ctrl / ⌘ + Y** (or **Ctrl/⌘ + Shift + Z**) | Redo |
| **Escape** | Cancel a measurement in progress |
| **Scroll wheel** | Zoom in / out |
| **Drag empty canvas** | Pan around |

---

## A worked example

Planning a small back garden, start to finish:

1. **Outline.** Click **Edit outline → Start from rectangle**. Set the sides to your real fence lengths — say 8 m × 6 m. The plot now matches your garden. Click **🔒 Lock this outline** and rename it "Back Garden".
2. **Add a second zone.** Click **+ New outline**, name it "Patio", give it a different colour, and shape it as a 3 × 4 m rectangle in one corner. Lock it.
3. **Place a tree.** Click **Objects**, create a circle named "Apple tree", diameter 2 m, green. Drag it into the garden. The four distance lines show how far it is from each fence.
4. **Position it exactly.** Open its editor (**▸**) and type "1.5" in the *left* box and "2" in the *up* box — it snaps to exactly 1.5 m from the left fence and 2 m from the top.
5. **Add beds.** Create a 1 × 3 m rectangle "Veg bed", duplicate it twice (⧉), and line them up using the arrow keys.
6. **Group the beds.** Tick all three veg beds, click **Group checked**. Now you can shuffle the whole set to find the sunniest spot.
7. **Check a gap.** Use **Measure** to confirm there's at least 80 cm between the beds and the patio for a wheelbarrow.
8. **Back it up.** Click **Export** and keep the file.

---

## Tips & good to know

- **The grid is your ruler.** By default one square = one metre; it relabels as you zoom so you always know the scale.
- **Lock things you're happy with** — both outlines and objects — so you can keep working without disturbing them.
- **Stacking order = list order.** If one object is hiding behind another, drag its row to the top of the list to bring it to the front.
- **Distances are centre-based.** The four lines and the position boxes measure from an object's centre, matching each other.
- **Export early, export often.** It's a one-click backup and the only way to move a plan between devices.

---

## FAQ

**Do I need an account or internet connection?**
No account, ever. Once the page has loaded it works offline, and your work saves locally.

**Will my saved layout be lost when the app updates?**
No. The save format is designed to carry forward, so new features won't erase existing layouts. For total peace of mind around a big change, export a backup first.

**Why doesn't it work well on my phone?**
SpacePlanner is built for the precision of a laptop or desktop — small touchscreens don't give the canvas and panels enough room. Use it on a larger screen for the best experience.

**Can two people edit the same plan at once?**
Not live. Saving is per-device. To collaborate, take turns: one person exports the file and the other imports it.

**What units does it use?**
Metres and centimetres (European style). Distances under a metre show in cm; larger ones in m.

---

*SpacePlanner™ · © MYS · All rights reserved. Trademark and copyright law applies.*
