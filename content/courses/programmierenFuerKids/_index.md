---
# Course title, summary, and position.
linktitle: Programmieren für Kids
summary: Hier können Kinder spielerisch und mit Spaß programmieren lernen mithilfe einer speziell für Kinder entwickelten Software. Am Ende des Kurses haben sie mehrere kleine Spiele programmiert, die sie ihren Eltern vorführen können.
weight: 1

# Page metadata.
title: Überblick
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
#menu:
#  example:
#    name: Overview
#    weight: 1
---

## Spielerisch Programmieren lernen  - für Kinder

Weihnachten steht vor der Tür. Corona ebenso - und die Schulen werden bis auf weiteres geschlossen bleiben. Auch einige Zeit im neuen Jahr.

Was aber ist mit den Kindern? Sollen sie den ganzen Tag vor dem Fernseher oder dem Computer verbringen? Freunde treffen dürfen sie nicht, draußen warten nur Kälte und schlechtes Wetter.

Wenn sie schon Zeit vor dem Computer verbringen, warum sollen sie dann nicht etwas Sinnvolles lernen, das ihnen auch Spaß macht?

## Delete tutorials

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
