# Коллективний проект про області України

## Contribution guides
### Install project
```bash
git clone git@github.com:PentiumLuls/university-ukraine-regions.git
cd university-ukraine-regions
```
### Run
Start app by running script: `bash run.sh`
and open in browser: `localhost:8080`

### Add new region
1. in `index.html` add new `switch-case` that runs function `showRegionInfo` in `<script>` tag
2. create new folder and html file in it (! with the same name as a parameter in `showRegionInfo` function)
3. commit your changes