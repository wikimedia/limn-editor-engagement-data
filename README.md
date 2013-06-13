# Limn &mdash; Editor Engagement Dashboards

[Limn][limn] is a GUI Visualization Toolkit.  This repository is a port of a set of dashboard currently hosted on the [toolserver][dario_dashboards].


## Using with Limn

 * Install [Limn][limn]
 * Link [Limn][limn] to [Limn Editor Engagement Data][limn_editor_engagement]

```
cd /path/to/limn/../
clone git@github.com:wikimedia/limn-editor-engagement-data.git
cd /path/to/limn
coke --vardir ./var --data ../../../../limn-editor-engagement-data --to eee link_data
npm start
```

[limn_editor_engagement]: https://github.com/wikimedia/limn-editor-engagement-data "Limn Editor Engagement Data on GitHub"
[limn]: https://github.com/wikimedia/limn "Limn on GitHub"
[dario_dashboards]: http://toolserver.org/~dartar/
