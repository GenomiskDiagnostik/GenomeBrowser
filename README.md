# GenomeBrowser

This repository contains a single-file D3.js genome browser prototype.

## Usage
1. Open `nextgen-genome-browser.html` directly in a modern browser (no build step).
2. Choose assembly, chromosome, and coordinates, then click **Load region**.
3. Pan/zoom via buttons or keyboard (`[`, `]`, `-`, `=`) and toggle tracks in the right sidebar.
4. Add JSON-based custom tracks via a CORS-enabled URL **or** paste inline JSON that returns `{name,start,end,strand,color}` objects.
5. Jump to the same region in UCSC using the header link. If UCSC REST is unreachable, the browser falls back to deterministic demo sequence/genes so tracks remain visible.
