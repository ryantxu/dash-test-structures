# id, path, naming strategies


Nested:
- folder structure id defined by layout on disk
- looks like normal file management



03-flat-ids-in-path
* flat structure
* no need to rename, move, re-structure the files
* Folders defined either:
- inside dashboards  (essentially what our SQL structure does)
- inside folders


Filenames and extensions?
* keep ".json" so tools all work :)
* maybe:
   ${slug}.dash.json
   ${slug}.alert.json
   ${slug}.panels.json // library panels

   // maybe in a parallel/differnet repo?
   ${slug}.dash.thumb.dark.webp 
   ${slug}.dash.thumb.light.webp
   ${slug}.snapshot.json // data dump from that dashboard

