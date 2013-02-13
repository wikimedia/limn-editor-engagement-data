# Limn &mdash; Editor Engagement Data

[Limn][limn] is a GUI Visualization Toolkit.  This repository is a port of a set of [toolserver dashboards][dario_dashboards].


## Using with Limn

 * Install [Limn][limn]
 * Link [Limn][limn] to [Limn Editor Engagement Data][limn_editor_engagement]

```
cd /path/to/limn/../
clone git@github.com:wikimedia/limn-editor-engagement.git
cd /path/to/limn
coke --data ../../../../limn-editor-engagement --to eee link_data
npm start
```

 * Browse the [Metrics Dashboard][metrics_dashboard] or the [Features Dashboard][features_dashboard]

[limn_editor_engagement]: https://github.com/wikimedia/limn-editor-engagement "Limn Editor Engagement Data on GitHub"
[limn]: https://github.com/wikimedia/limn "Limn on GitHub"
[dario_dashboards]: http://toolserver.org/~dartar/
[metrics_dashboard]: http://localhost:8081/dashboards/metrics
[features_dashboard]: http://localhost:8081/dashboards/features
