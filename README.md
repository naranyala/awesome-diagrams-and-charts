# Awesome Diagrams & Charts

> A curated collection of libraries, tools, and resources for creating diagrams, charts, and data visualizations.

---

## Table of Contents

- [JavaScript Charting Libraries](#javascript-charting-libraries)
  - [General Purpose](#general-purpose)
  - [Lightweight & Specialized](#lightweight--specialized)
  - [Financial & Trading](#financial--trading)
- [Diagram & Flowchart Libraries](#diagram--flowchart-libraries)
- [Text-to-Diagram Tools](#text-to-diagram-tools)
  - [AI-Powered Diagram Tools](#ai-powered-diagram-tools)
- [React Chart Libraries](#react-chart-libraries)
- [Vue Chart Libraries](#vue-chart-libraries)
- [Svelte Chart Libraries](#svelte-chart-libraries)
- [Angular Chart Libraries](#angular-chart-libraries)
- [Python Visualization Libraries](#python-visualization-libraries)
  - [General Purpose](#python-general-purpose)
  - [Scientific & Specialized](#python-scientific--specialized)
  - [Dashboards & Web Apps](#python-dashboards--web-apps)
  - [Diagrams as Code](#python-diagrams-as-code)
- [PHP Visualization Libraries](#php-visualization-libraries)
- [R Visualization Libraries](#r-visualization-libraries)
- [Java & Kotlin Visualization Libraries](#java--kotlin-visualization-libraries)
- [Go Visualization Libraries](#go-visualization-libraries)
- [Ruby Visualization Libraries](#ruby-visualization-libraries)
- [C++ & .NET Visualization Libraries](#c--net-visualization-libraries)
- [Mobile Chart Libraries](#mobile-chart-libraries)
  - [Android](#android)
  - [iOS](#ios)
  - [Cross-Platform (Flutter/React Native)](#cross-platform)
- [3D Visualization](#3d-visualization)
- [SVG, Canvas & Graphics Libraries](#svg-canvas--graphics-libraries)
- [Animation Libraries](#animation-libraries)
- [Graph & Network Visualization](#graph--network-visualization)
- [Mapping & Geospatial](#mapping--geospatial)
- [Infrastructure as Code Diagrams](#infrastructure-as-code-diagrams)
- [Whiteboard & Collaborative Tools](#whiteboard--collaborative-tools)
- [Diagramming SDKs & Frameworks](#diagramming-sdks--frameworks)
- [CLI Tools](#cli-tools)
- [Online Editors & Platforms](#online-editors--platforms)
- [Specialized Diagram Types](#specialized-diagram-types)
  - [UML & Software Design](#uml--software-design)
  - [Neural Network & AI Architectures](#neural-network--ai-architectures)
  - [Timelines & Gantt](#timelines--gantt)
  - [Mind Maps & Concept Maps](#mind-maps--concept-maps)
  - [Heatmaps & Calendars](#heatmaps--calendars)
  - [Org Charts & Hierarchical](#org-charts--hierarchical)
  - [ERD & Database](#erd--database)
  - [Network Topology](#network-topology)
- [Data Sources & Formats](#data-sources--formats)
- [Resources](#resources)
  - [Learning & Inspiration](#learning--inspiration)
  - [Awesome Lists](#awesome-lists)
  - [Design Guidelines](#design-guidelines)

---

## JavaScript Charting Libraries

### General Purpose

- [**D3.js**](https://d3js.org/) — Data-driven document manipulation using HTML, SVG, and CSS. Modular architecture with over 30 standalone packages. License: ISC.
- [**Chart.js**](https://www.chartjs.org/) — Canvas-based charting. Core chart types: line, bar, pie, doughnut, polar area, bubble, scatter, radar. Zero dependencies. License: MIT.
- [**Apache ECharts**](https://echarts.apache.org/) — Canvas/WebGL renderer. Chart types include line, bar, pie, scatter, map, tree, graph, heatmap, candlestick, funnel. Modular build system. License: Apache-2.0.
- [**Plotly.js**](https://plotly.com/javascript/) — Built on D3.js and stack.gl. Chart types include line, scatter, bar, pie, heatmap, contour, 3D surface, Sankey, treemap. License: MIT.
- [**Highcharts**](https://www.highcharts.com/) — SVG/VML rendering. Chart types include line, spline, area, areaspline, column, bar, pie, scatter, gauge, arearange, columnrange, bubble, series, polygon, pyramid, funnel, heatmap, treemap. Free for personal/non-commercial use; commercial license required otherwise.
- [**ApexCharts**](https://apexcharts.com/) — SVG rendering. Chart types: line, area, bar, column, scatter, bubble, heatmap, treemap, pie, donut, radialBar, radar, polarArea, rangeArea, boxPlot, candlestick, funnel, timeline. Built-in toolbar with zoom, pan, reset, and export. License: MIT.
- [**Google Charts**](https://developers.google.com/chart) — Chart types: line, area, bar, column, pie, geo, scatter, bubble, candlestick, combo, gauge, histogram, timeline, tree map, organizational chart. Loaded via Google CDN. Data sent to Google servers for rendering.
- [**amCharts 5**](https://www.amcharts.com/) — TypeScript-based. WebGL/SVG hybrid rendering. Chart types: XY (line, column, step, candlestick), Pie, Radar, Radar, Sunburst, Tree, Chord, Sankey, Map. Streaming data support. License: proprietary with free tier (watermark).
- [**AnyChart**](https://www.anychart.com/) — Built on GraphicsJS. Chart types: line, spline, step, area, bar, column, pareto, waterfall, marimekko, pie, donut, radar, polar, scatter, bubble, stock, Gantt, heat, map, tree, treemap, Sankey, chord, connector. License: proprietary with free tier.
- [**ZingChart**](https://www.zingchart.com/) — Canvas/SVG rendering. Chart types: line, area, bar, pie, scatter, bubble, heatmap, treemap, radar, polar, funnel, Gantt, boxplot, bullet, sparkline, stock. License: proprietary with free tier (watermark).
- [**PolyChart**](https://polychart.io/) — WebGL-based rendering framework. Integrates with React, Vue, Angular, or vanilla JS. License: proprietary.
- [**Observable Plot**](https://observablehq.com/plot/) — Built by creators of D3. Chart types: dot, cell, rule, text, link, line, area, bar, rect, image, vector, frame. License: ISC.
- [**AntV G2**](https://g2.antv.vision/) — Visualization grammar based on Wilkinson's Grammar of Graphics. TypeScript. Canvas/SVG rendering. Chart types: line, area, interval (bar, column, rose, funnel, pyramid), point, polygon, edge, schema, heatmap, density, tree, treemap, venn, wordCloud, sankey, chord, stock, radar, gauge, liquid, progress. License: MIT.
- [**Lightning Charts JS**](https://www.arction.com/lightningchart-js/) — GPU-accelerated WebGL rendering. Chart types: line, spline, area, range, bar, column, candlestick, OHLC, pie, gauge, radar, heatmap, contour, scatter, polar, spider, pyramid, funnel, box-whisker, histogram. License: proprietary.

### Lightweight & Specialized

- [**Vega / Vega-Lite**](https://vega.github.io/) — JSON-based declarative specification. Vega-Lite compiles to Vega. Chart types: bar, line, area, point, tick, rect, rule, geo, arc, image, text. License: BSD-3-Clause.
- [**NVD3**](https://nvd3.org/) — Built on D3.js v3. Chart types: line, scatter, bar, pie, stacked area, stacked bar, bullet, sparkline, multiBar, linePlusBar, historicalBar, cumulativeLine, ohlc, candlestick, boxPlot. License: Apache-2.0.
- [**C3.js**](https://c3js.org/) — Wrapper around D3.js. Chart types: line, spline, step, area, area-spline, area-step, bar, scatter, pie, donut, gauge. License: MIT.
- [**Chartist.js**](https://gionkunz.github.io/chartist-js/) — SVG-based. Responsive with CSS media queries. Chart types: line, bar, pie. License: MIT/WTFPL.
- [**Dygraphs**](https://dygraphs.com/) — Canvas-based line charts. Supports error bands, annotations, ranges. License: MIT.
- [**MetricsGraphics.js**](https://metricsgraphicsjs.org/) — Optimized for time-series data. Built on D3.js. Chart types: line, histogram, scatterplot, missing data. License: MPL-2.0.
- [**Rickshaw**](http://code.shutterstock.com/rickshaw/) — Time-series charts using D3.js. Chart types: line, area, bar, scatterplot. License: BSD-style.
- [**Morris.js**](https://morrisjs.github.io/morris.js/) — Requires jQuery and Raphael.js. Chart types: line, bar, area, donut. License: BSD-2-Clause.
- [**Flot**](https://www.flotcharts.org/) — jQuery plugin. Canvas rendering. Chart types: line, bar, pie, area, stack. License: MIT.
- [**Smoothie Charts**](https://smoothiecharts.org/) — Real-time streaming data charts. License: MIT.
- [**CanvasJS**](https://canvasjs.com/) — Canvas-based. Chart types: line, spline, stepLine, area, splineArea, stepArea, bar, column, stackedBar, stackedColumn, pie, doughnut, funnel, pyramid, scatter, bubble, candlestick, OHLC, boxAndWhisker, waterFall, rangeSpline, rangeArea, rangeBar, rangeColumn, error, dynamic. License: proprietary with free tier (watermark).
- [**uPlot**](https://github.com/leeoniya/uPlot) — Canvas-based line charts. Supports multiple series, bands, sparklines. License: MIT.

### Financial & Trading

- [**TradingView Lightweight Charts**](https://www.tradingview.com/lightweight-charts/) — TypeScript. Chart types: candlestick, bar, line, area, histogram. License: Apache-2.0.
- [**TechanJS**](https://techanjs.org/) — D3.js-based technical analysis. Chart types: candlestick, OHLC, line, area, volume, MACD, RSI, EMA, SMA, Bollinger Bands, stochastic. License: MIT.
- [**d3fc**](https://d3fc.io/) — D3.js-based financial charting components. SVG/Canvas/WebGL rendering. Chart types: candlestick, OHLC, waterfall, waterfall 3D. License: MIT.

---

## Diagram & Flowchart Libraries

- [**JointJS**](https://jointjs.com/) — SVG-based. Predefined shapes for ERD, Org chart, UML, BPMN. Custom SVG/programmatic shapes. JSON serialization. Core is MIT-licensed; JointJS+ (commercial) adds 200+ predefined shapes, undo/redo, clipboard.
- [**GoJS**](https://gojs.net/latest/index.html) — Canvas/SVG rendering. Diagram types: flowchart, BPMN, org chart, UML, ER, Gantt, Sankey, mind map, state chart, data flow. Data-bound models, undo/redo, automatic layouts. 150+ samples. License: proprietary (free with watermark for evaluation).
- [**mxGraph**](https://github.com/jgraph/mxgraph) — SVG/HTML5 rendering. No third-party dependencies. Repository archived; maintained via forks. Powers Draw.io. License: Apache-2.0.
- [**Mermaid.js**](https://mermaid.js.org/) — Text-based diagram definition. Diagram types: flowchart, sequence, class, state, gantt, pie, er, gitGraph, journey, timeline, mindmap, block, zenuml. License: MIT.
- [**AntV X6**](https://x6.antv.vision/) — SVG/HTML rendering. Node-based diagram editing. Custom shape registration. Plugin architecture. License: MIT.
- [**AntV G6**](https://g6.antv.vision/) — Graph visualization engine. Built-in layouts: force, circular, radial, tree, grid, compact. Canvas/SVG/WebGL rendering. License: MIT.
- [**LogicFlow**](https://github.com/didi/LogicFlow) — Flowchart editing framework by DiDi. Supports BPMN, custom nodes, plugins. License: Apache-2.0.
- [**React Flow**](https://reactflow.dev/) — Node-based UI library for React. Custom node types, zoom/pan, minimap, background patterns, snap-to-grid. License: MIT.
- [**Vue Flow**](https://vueflow.dev/) — Vue 3 port of React Flow (same codebase, XYFlow). License: MIT.
- [**Svelvet**](https://github.com/open-source-labs/Svelvet) — Svelte component for node-based diagrams. Uses D3 for zoom. License: MIT.
- [**Drawflow**](https://github.com/jerosoler/Drawflow) — Node-based editor. Vanilla JS. License: MIT.
- [**JsPlumb Toolkit**](https://jsplumbtoolkit.com/) — SVG-based connectivity. Community edition (MIT) and commercial edition.
- [**LeaderLine**](https://anseki.github.io/leader-line/) — Draws connector lines between HTML elements. License: MIT.
- [**BPMN.js**](https://bpmn.io/toolkit/bpmn-js/) — BPMN 2.0 rendering and modeling. Uses diagrams.js. License: BSD-2-Clause.
- [**diagrams.js**](https://github.com/bpmn-io/diagram-js) — Diagramming toolkit. Extensible modeling environment. License: MIT.
- [**RoughJS**](https://roughjs.com/) — Sketchy/hand-drawn style graphics. Canvas/SVG rendering. License: MIT.
- [**Nomnoml**](https://www.nomnoml.com/) — UML from text. Uses dagre for layout. License: MIT.
- [**Fabric.js**](https://fabricjs.com/) — Canvas library with object model. SVG parsing. License: MIT.
- [**Paper.js**](http://paperjs.org/) — Vector graphics scripting on Canvas. Bézier curves, path operations. License: MIT.
- [**Two.js**](https://two.js.org/) — Renderer-agnostic 2D API (WebGL, Canvas, SVG). License: MIT.
- [**p5.js**](https://p5js.org/) — Creative coding library. Graphics, animation, sound. License: LGPL-2.1.
- [**Tldraw**](https://www.tldraw.com/) — Drawing library with hand-drawn aesthetic. Smart arrows, snapping, sticky notes. License: seaware (free for personal/commercial use).
- [**Konva.js**](https://konvajs.org/) — 2D Canvas library with stage/layer/shapes model. License: MIT.
- [**SVG.js**](https://svgjs.dev/) — SVG manipulation library. License: MIT.

---

## Text-to-Diagram Tools

- [**Mermaid**](https://mermaid.js.org/) — Diagram types: flowchart, sequence, class, state, gantt, pie, er, gitGraph, journey, timeline, mindmap, block, zenuml. Renders via D3. License: MIT.
- [**Mermaid Online**](https://mermaidonline.org/?utm_source=awesome-diagrams-charts&utm_medium=github_awesome_list&utm_campaign=mo_backlink) — Browser-based Mermaid preview and export tool. Exports PNG, SVG, JPG, WebP, and PDF for documentation, READMEs, blogs, and slides.
- [**PlantUML**](https://plantuml.com/) — Diagram types: sequence, use case, class, activity, component, state, object, deployment, timing, network, salt (UI mockup), Gantt, math, mindmap, AsciiMath. Uses Graphviz for layout. License: GPL/LGPL/EPL.
- [**D2**](https://d2lang.com/) — Diagram scripting language. Supports layouts: DAG, ELK, Tree. Themes available. Compiles to SVG/PNG. License: MPL-2.0.
- [**Graphviz**](https://graphviz.org/) — Layout engines: dot (hierarchical), neato (spring), fdp (force), sfdp (multiscale), circo (circular), twopi (radial), osage (array), patchwork (squarified treemap). DOT language input. License: EPL.
- [**Ditaa**](https://ditaa.sourceforge.net/) — Converts ASCII art with box-drawing characters into PNG diagrams. License: GPL-2.0.
- [**BlockDiag**](http://blockdiag.com/) — Diagram types: blockdiag, seqdiag, actdiag, nwdiag, packetdiag, rackdiag. Python-based. License: Apache-2.0.
- [**ERD**](https://github.com/BurntSushi/erd) — Entity-relationship diagrams from simple markup. Haskell-based. License: Unlicense.
- [**Penrose**](https://penrose.cs.cmu.edu/) — Creates diagrams from mathematical notation. Uses optimization-based layout. Substance language for domain specification. License: MIT.
- [**Structurizr**](https://structurizr.com/) — C4 model implementation. DSL for architecture diagrams. License: proprietary with open-source DSL.
- [**Kroki**](https://kroki.io/) — Unified REST API for 30+ diagram tools: BlockDiag, BPMN, Bytefield, C4 with PlantUML, DBML, Diagrams.net, Ditaa, D2, GraphViz, Mermaid, Nomnoml, PlantUML, SvgBob, Symbolator, UMLet, Vega, VegaLite, WaveDrom. License: MIT.
- [**WaveDrom**](https://wavedrom.com/) — Digital timing diagrams from JSON text. License: MIT.
- [**DBML**](https://www.dbml.org/) — Database markup language. Renders entity-relationship diagrams. CLI and online editor. License: MIT.
- [**Svgbob**](https://ivanceras.github.io/svgbob/) — Converts ASCII diagrams to SVG. License: MIT.
- [**Bytefield SVG**](https://github.com/Deep-Symmetry/bytefield-svg) — Network protocol header diagrams. License: MIT.
- [**Symbolator**](https://kevinpt.github.io/symbolator/) — VHDL/Verilog component symbol diagrams. License: MIT.
- [**UMLet**](https://www.umlet.com/) — UML tool with fast text-based input. Standalone and Eclipse plugin. License: GPL.
- [**C4-PlantUML**](https://github.com/plantuml-stdlib/C4-PlantUML) — PlantUML macros for C4 model. License: MIT.
- [**LikeC4**](https://likec4.com/) — Architecture-as-code. Live diagrams from code specs. License: MIT.

### AI-Powered Diagram Tools

- [**Diagram AI**](https://aidiagram.net/) — Text-to-diagram generation. Exports XML/SVG/PNG.
- [**Diagram Generator AI**](https://diagramgeneratorai.com/) — Generates flowcharts, ER diagrams, sequence diagrams, mind maps from text descriptions.
- [**Codigram**](https://codigram.app/) — Converts natural language to Mermaid diagrams: flowcharts, sequence, class diagrams.
- [**ConceptViz**](https://conceptviz.app/tools/text-to-diagram-generator) — AI-powered text to diagram generation for flowcharts, architectures, process maps.
- [**FlowcastGPT**](https://flowcastgpt.com/) — Text-to-diagram visualization using AI.
- [**InfraSketch**](https://infrasketch.net/) — Generates architecture diagrams and design docs from text.
- [**Next AI Draw.io**](https://www.draw.io/?ai=next) — AI-assisted diagram creation within the Draw.io editor.

---

## React Chart Libraries

- [**Recharts**](https://recharts.org/) — Built on D3. Composable React components. Chart types: line, area, bar, column, pie, radar, radialBar, scatter, funnel, treemap. SVG rendering. License: MIT.
- [**Nivo**](https://nivo.rocks/) — Built on D3. Chart types: line, area, bar, pie, donut, scatter, bubble, heatmap, tree map, sunburst, chord, sankey, radar, parallel coordinates, swarm plot, calendar, choropleth. SSR support via HTML/SVG rendering. License: MIT.
- [**Visx**](https://airbnb.io/visx/) — Airbnb's D3 primitives as React components. Tree-shakeable modules. TypeScript. Components: axes, scales, shapes, glyphs, curves, gradients, patterns, tooltips, drag, zoom. License: MIT.
- [**Victory**](https://commerce.nearform.com/open-source/victory/) — React + React Native support. Chart types: VictoryChart, VictoryLine, VictoryArea, VictoryBar, VictoryPie, VictoryScatter, VictoryCandlestick, VictoryBoxPlot, VictoryErrorBar, VictoryHistogram, VictoryVoronoi, VictoryTooltip. License: MIT.
- [**React ChartJS 2**](https://react-chartjs-2.js.org/) — Chart.js wrapper for React. License: MIT.
- [**MUI X Charts**](https://mui.com/x/react-charts/) — Part of MUI X suite. Chart types: line, area, bar, pie, scatter, sparkline. MIT-licensed community tier; Pro/Plan tiers for advanced features.
- [**TanStack Charts**](https://tanstack.com/charts) — Headless architecture. D3-based data processing. No built-in UI components. License: MIT.
- [**React-vis**](https://uber.github.io/react-vis/) — Uber's visualization library. Chart types: XYPlot, LineSeries, VerticalBarSeries, HeatmapSeries, ContourSeries, LabelSeries, Hint. License: MIT. Archived by maintainers.
- [**Tremor**](https://www.tremor.so/) — Dashboard components built on Tailwind CSS. Uses Recharts internally. Components: AreaChart, BarChart, LineChart, DonutChart, ScatterChart. License: Apache-2.0.
- [**AG Charts (React)**](https://www.ag-grid.com/charts/) — Canvas rendering. Part of AG Grid ecosystem. Chart types: line, area, bar, column, pie, scatter, bubble, histogram, heatmap, radar, combo. License: MIT (community), commercial (enterprise).
- [**ReaFlow**](https://reaflow.dev/) — React flowchart and workflow diagram library. License: Apache-2.0.
- [**BizCharts**](https://bizcharts.net/) — Based on AntV G2. License: MIT. Not actively maintained; AntV G2 recommended.

---

## Vue Chart Libraries

- [**Vue Chart.js**](https://vue-chartjs.org/) — Chart.js wrapper for Vue 3. License: MIT.
- [**Vue ECharts**](https://github.com/ecomfe/vue-echarts) — Apache ECharts wrapper for Vue. License: MIT.
- [**ApexCharts Vue**](https://apexcharts.com/docs/vue-charts/) — Official Vue wrapper. License: MIT.
- [**V-Charts**](https://v-charts.js.org/) — Vue 2.x + ECharts wrapper. License: MIT. Vue 2 only.
- [**Chartist Vue**](https://github.com/rafagafe/chartist-vue) — Chartist.js wrapper for Vue. License: MIT.

---

## Svelte Chart Libraries

- [**LayerChart**](https://www.layerchart.com/) — D3-based composable chart primitives for Svelte. Chart types: line, area, bar, scatter, pie, donut. License: MIT.
- [**Svelte Chart.js**](https://github.com/SvelteCharts/svelte-chartjs) — Chart.js wrapper for Svelte. License: MIT.
- [**Svelvet**](https://github.com/open-source-labs/Svelvet) — Svelte node-based diagram library. License: MIT.
- [**Svelte ECharts**](https://github.com/ahmerkhani/svelte-echarts) — Apache ECharts wrapper for Svelte. License: MIT.

---

## Angular Chart Libraries

- [**ng2-charts**](https://valor-software.com/ng2-charts/) — Chart.js wrapper for Angular. License: MIT.
- [**Angular ECharts**](https://github.com/xieziyu/ngx-echarts) — Apache ECharts wrapper for Angular. License: MIT.
- [**Swimlane/ngx-charts**](https://swimlane.github.io/ngx-charts/) — Component-based charting for Angular using D3. SVG rendering. Chart types: area, bar, line, pie, bubble, number card, gauge, tree map, heat map, advanced pie, pie grid. License: MIT.
- [**Angular Highcharts**](https://github.com/highcharts/highcharts-angular) — Official Highcharts wrapper for Angular. License: proprietary (requires Highcharts license).

---

## Python Visualization Libraries

### Python: General Purpose

- [**Matplotlib**](https://matplotlib.org/) — 2D plotting library. Plot types: line, bar, scatter, histogram, contour, contourf, imshow, pie, errorbar, boxplot, violin, streamplot, quiver, stem, step, fill, polar, 3D (surface, wireframe, scatter, plot, bar, contour). Integrates with NumPy. License: PSF-style.
- [**Seaborn**](https://seaborn.pydata.org/) — Based on Matplotlib. Plot types: relplot (scatter, line), displot (hist, kde, ecdf, rug), catplot (strip, swarm, box, violin, boxen, point, bar, count), heatmap, clustermap, pairplot, jointplot, regplot, residplot, lmplot. License: BSD-3-Clause.
- [**Plotly (Python)**](https://plotly.com/python/) — Interactive charts via Plotly.js. Plot types: scatter, line, area, bar, histogram, pie, donut, box, violin, heatmap, contour, 3D surface, 3D scatter, 3D mesh, 3D cone, Sankey, treemap, sunburst, icicle, funnel, waterfal, parcoords, parallel categories, choropleth, density map. License: MIT.
- [**Bokeh**](https://docs.bokeh.org/) — Interactive browser-based plots. Plot types: line, scatter, bar, patch, hex, step, segment, ray, image, image_rgba, wedge, annulus, annular_wedge. Supports streaming data and server-side callbacks. License: BSD-3-Clause.
- [**Altair**](https://altair-viz.github.io/) — Declarative API based on Vega-Lite. Mark types: area, bar, boxplot, circle, errorband, errorbar, geopoint, image, line, point, rect, rule, square, text, tick, trail. License: BSD-3-Clause.
- [**Pygal**](http://www.pygal.org/) — SVG charts. Chart types: Line, StackedLine, Bar, StackedBar, HorizontalBar, HorizontalStackedBar, XY, HorizontalXY, StackedBar100, Pie, HalfPie, PieChart, Radar, Box, Dot, Funnel, SolidGauge, Gauge, Treemap, Calendar, Maps. License: LGPL-3.0.
- [**HoloViews**](https://holoviews.org/) — Declarative visualizations on top of Bokeh/Matplotlib. Element types: Curve, Scatter, Path, Area, Spread, Bars, BoxWhisker, Violin, Points, VectorField, HeatMap, Image, RGB, Contours, Graph, Sankey, Chord, Histogram. License: BSD-3-Clause.
- [**Pandas Plotting**](https://pandas.pydata.org/docs/user_guide/visualization.html) — Built-in `.plot()` interface using Matplotlib. Plot types: line, bar, barh, hist, box, kde, density, area, pie, scatter, hexbin. License: BSD-3-Clause.

### Python: Scientific & Specialized

- [**Plotnine**](https://plotnine.org/) — Grammar of graphics implementation (ggplot2 port). Geoms: geom_point, geom_line, geom_bar, geom_col, geom_histogram, geom_density, geom_boxplot, geom_violin, geom_smooth, geom_ribbon, geom_area, geom_tile, geom_raster, geom_polygon, geom_path, geom_text, geom_label, geom_segment, geom_abline, geom_hline, geom_vline, geom_jitter, geom_count, geom_bin2d, geom_hex, geom_contour, geom_sf. License: GPL-2.0.
- [**Ggpy**](http://yhat.github.io/ggpy/) — ggplot2-inspired plotting. License: GPL-2.0. Not actively maintained.
- [**Missingno**](https://github.com/ResidentMario/missingno) — Matrix, bar, heatmap, dendrogram for missing data. License: MIT.
- [**PyQtGraph**](http://www.pyqtgraph.org/) — Real-time 2D/3D plotting using PyQt/PySide and NumPy. Plot types: PlotWidget (line, scatter, bar, graph), ImageView, HistogramLUT, PlotItem, LegendItem, ROI, ViewBox, IsocurveItem. License: MIT.
- [**VisPy**](https://vispy.org/) — GPU-based 3D visualization using OpenGL. Visual types: line, scatter, image, mesh, surface, volume, arrow, axis, colorbar, contour, graph, histogram, infographic, isocurve, isosurface, marker, mesh, polygon, polygon_collection, regular_polygon, ring, scroll_chain, spectrogram, surface, text, tube, volume, windbarb. License: BSD-3-Clause.
- [**Glumpy**](https://glumpy.github.io/) — OpenGL visualization. License: BSD-2-Clause.
- [**NetworkX**](https://networkx.org/) — Graph data structures and algorithms. Layout: spring, spectral, circular, shell, random, fruchterman_reingold, kamada_kawai, bfs, dfs, centrality, clustering, shortest_path, minimum_spanning_tree. License: BSD-3-Clause.
- [**GeoPandas**](https://geopandas.org/) — Geospatial data with plotting via Matplotlib. License: BSD-3-Clause.
- [**Datashader**](https://datashader.org/) — Rasterizes large datasets for visualization. Pipeline: project, transform, aggregate, transform, shade. License: BSD-3-Clause.
- [**PyDeck**](https://pydeck.gl/) — Python binding for deck.gl. Layers: ArcLayer, ColumnLayer, GeoJsonLayer, GridLayer, HeatmapLayer, HexagonLayer, PathLayer, PointCloudLayer, PolygonLayer, ScatterplotLayer, ScreenGridLayer, TextLayer, TripsLayer. License: MIT.

### Python: Dashboards & Web Apps

- [**Dash (Plotly)**](https://dash.plotly.com/) — Flask + Plotly.js + React. Callbacks for interactivity. License: MIT.
- [**Streamlit**](https://streamlit.io/) — App framework for ML/data apps. Built-in charting via Altair/Plotly. License: Apache-2.0.
- [**Panel (HoloViz)**](https://panel.holoviz.org/) — Dashboarding for PyViz ecosystem. License: BSD-3-Clause.
- [**Gradio**](https://www.gradio.app/) — UI for ML models. License: Apache-2.0.
- [**Reflex**](https://reflex.dev/) — Full-stack Python-to-web framework. Chart components. License: Apache-2.0.

### Python: Diagrams as Code

- [**Diagrams**](https://diagrams.mingrammer.com/) — Cloud architecture diagrams. Provider nodes: AWS, Azure, GCP, Kubernetes, DigitalOcean, Oracle Cloud, Firebase, IoT, Programming, Generic. License: MIT.
- [**Graphviz (Python)**](https://graphviz.readthedocs.io/) — Python API for Graphviz. License: MIT.
- [**TerraformGraph**](https://pypi.org/project/terraformgraph/) — Generates diagrams from Terraform state. License: MIT.
- [**Archimatexl-python**](https://github.com/ArchimateXL) — Generates ArchiMate diagrams from YAML. License: MIT.

---

## PHP Visualization Libraries

### Laravel

- [**Livewire Charts**](https://github.com/asantibanez/livewire-charts) — Livewire components: pie, area, bar, line charts. Uses Chart.js. License: MIT.
- [**Laravel Charts**](https://github.com/ConsoleTVs/Charts) — Multi-library charting (Chartist, Chart.js, ECharts, FusionCharts, Highcharts, JustGage, Plottable.js). License: MIT.
- [**Chartkick.php**](https://chartkick.com/) — One-line chart creation (Ruby/Python/PHP). Supports Chart.js, Google Charts, Highcharts. License: MIT.

---

## R Visualization Libraries

- [**ggplot2**](https://ggplot2.tidyverse.org/) — Grammar of Graphics implementation. Geoms: geom_point, geom_line, geom_bar, geom_histogram, geom_boxplot, geom_violin, geom_smooth, geom_area, geom_tile, geom_polygon, geom_path, geom_text, geom_segment, geom_abline, geom_hline, geom_vline, geom_jitter, geom_count, geom_rug, geom_ribbon, geom_contour, geom_sf, geom_hex, geom_bin2d, geom_dotplot, geom_freqpoly, geom_density, geom_qq, geom_qq_line, geom_spoke, geom_col. License: GPL-2.0.
- [**Plotly for R**](https://plotly.com/r/) — ggplotly() converts ggplot2 to interactive charts. License: MIT.
- [**Shiny**](https://shiny.posit.co/) — Interactive web app framework. License: GPL-3.0.
- [**Lattice**](https://lattice.r-forge.r-project.org/) — Trellis graphics. License: GPL-2.0.
- [**Ggvis**](https://ggvis.rstudio.com/) — Vega-based interactive graphics. License: GPL-3.0.
- [**RGL**](https://dmurdoch.github.io/rgl/) — OpenGL 3D visualization. License: GPL-2.0.
- [**VisNetwork**](https://datastorm-open.github.io/visNetwork/) — Network visualization via vis.js. License: GPL-2.0.
- [**RBokeh**](https://github.com/bokeh/rbokeh) — R interface to Bokeh. License: GPL-2.0.
- [**ECharts4R**](https://echarts4r.john-coene.com/) — Apache ECharts wrapper for R. License: GPL-3.0.
- [**Esquisse**](https://dreamrs.github.io/esquisse/) — Drag-and-drop ggplot2 builder. License: GPL-3.0.

---

## Java & Kotlin Visualization Libraries

- [**XChart**](https://knowm.org/open-source/xchart/) — Chart types: line, scatter, area, bar, stacked bar, column, stacked column, histogram, pie, donut, ring, bubble, candlestick, OHLC, error, dial, gauge, box, heatmap, contour, surface, vector, polar, radar, radar_area, wind, compass, clock, meter, xy. License: Apache-2.0.
- [**JFreeChart**](https://www.jfree.org/jfreechart/) — Chart types: line, bar, pie, scatter, Gantt, waterfall, XY, time series, category, polar, spider, radar, box-and-whisker, histogram, thermomete, compass, wind, meter. Swing/JavaFX. License: LGPL.
- [**JavaFX Charts**](https://openjfx.io/) — Built-in chart controls in JavaFX. Chart types: AreaChart, BarChart, BubbleChart, LineChart, PieChart, ScatterChart, StackedAreaChart, StackedBarChart. License: GPL-2.0.
- [**Lets-Plot**](https://lets-plot.org/) — Grammar of graphics for Kotlin/Java. Geoms: point, line, path, area, bar, histogram, boxplot, contour, density, tile, polygon, text, label, rug, abline, hline, vline, smooth, jitter, count, bin2d, hex. License: MIT.
- [**GCharts**](https://github.com/GDSSecurity/GCharts) — Google Charts API wrapper for Java. License: LGPL.

---

## Go Visualization Libraries

- [**Go-echarts**](https://github.com/go-echarts/go-echarts) — Apache ECharts wrapper for Go. Chart types: Bar, BoxPlot, CandleStick, Custom, EffectScatter, Funnel, Gauge, Geo, Graph, HeatMap, Kline, Line, Line3D, Liquid, Map, Page, Parallel, Pie, Radar, Sankey, Scatter, Scatter3D, Sunburst, Surface3D, ThemeRiver, Tree, TreeMap, WordCloud. License: MIT.
- [**Plotinum**](https://github.com/gonum/plot) — Plotting library for Gonum. Plot types: line, scatter, error bars, box plot, histogram, heat map, contour, bubble, function, grid, legend. License: BSD-3-Clause.
- [**Chart**](https://github.com/go-playground/chart) — Chart.js-style charts in Go. License: MIT.
- [**Go-chart**](https://github.com/wcharczuk/go-chart) — Chart types: line, continuous, bar, stacked bar, pie, donut, value, time series, sparkline, bullet. SVG/PNG output. License: MIT.
- [**tdewolff/canvas**](https://github.com/tdewolff/canvas) — Vector graphics engine for Go. Output formats: SVG, PDF, EPS, TeX. License: MIT.

---

## Ruby Visualization Libraries

- [**Chartkick**](https://chartkick.com/) — One-line chart creation. Supports Chart.js, Google Charts, Highcharts. Chart types: line, pie, column, bar, area, scatter, geo, timeline. License: MIT.
- [**Gruff**](https://gruff.rubyforge.org/) — Graph library for Ruby based on RMagick. Chart types: line, bar, pie, side_bar, stacked_bar, area, mini_bar, dot, net, spider. License: MIT.
- [**Ruby-plot**](https://github.com/SanketDG/ruby-plot) — Multi-backend plotting (Matplotlib via matplotlib4ruby, Gnuplot). License: MIT.

---

## C++ & .NET Visualization Libraries

- [**VTK (Visualization Toolkit)**](https://vtk.org/) — 3D computer graphics, image processing, visualization. Modules: rendering, imaging, filtering, IO, interaction, widgets, volume rendering, parallel, geovis, information visualization. License: BSD-3-Clause.
- [**MathGL**](http://mathgl.sourceforge.net/) — 3D data plotting library. Plot types: plot, subplot, surf, mesh, contour, density, axis, box, grid, label, light, camera. License: GPL.
- [**ImPlot**](https://github.com/epezent/implot) — Immediate mode plotting for Dear ImGui. Plot types: line, scatter, shaded, bars, error bars, stems, stairs, pie, heatmap. License: MIT.
- [**QCustomPlot**](https://www.qcustomplot.com/) — Qt-based 2D plotting. Plot types: graph, curve, statistical (box plot), candlestick, OHLC, bar, color map, financial. License: GPL/commercial.
- [**OxyPlot**](https://oxyplot.org/) — .NET charting library. Platforms: WPF, Windows Forms, UWP, Xamarin, Avalonia. Plot types: line, area, scatter, bar, column, pie, heatmap, contour, candlestick, box plot, polygon, pie, scatter, stem, tile map. License: MIT.
- [**ScottPlot**](https://scottplot.net/) — Interactive plotting for .NET. Platforms: WinForms, WPF, Avalonia, Blazor. Plot types: scatter, line, bar, pie, box plot, error bar, finance, histogram, heatmap, contour, image, polygon, arrow, ellipse, text, axis line, axis span, bracket, callout, coordinate line, coordinate span, crosshair, error bar, filled curve, function, heatmap, image, line, marker, OHLC, pie, polygon, population, radar, radial gauge, rectangle, scale bar, scatter, signal, signal constant, signal xy, text, tick, vector, vector field. License: MIT.
- [**LiveCharts2**](https://lvcharts.net/) — .NET charts with animations. Platforms: WPF, WinForms, Avalonia, Uno, Xamarin. Chart types: line, column, row, pie, area, stacked area, stacked column, stacked row, step line, live, gage, guage, geometries. License: MIT.
- [**Microcharts**](https://github.com/microcharts-dotnet/Microcharts) — Simple Xamarin.Forms charts. Chart types: point, line, bar, donut, radar. License: MIT.

---

## Mobile Chart Libraries

### Android

- [**MPAndroidChart**](https://github.com/PhilJay/MPAndroidChart) — Chart types: LineChart, BarChart, HorizontalBarChart, PieChart, ScatterChart, CandleStickChart, BubbleChart, RadarChart, CombinedChart. License: Apache-2.0.
- [**WilliamChart**](https://github.com/diogobernardino/WilliamChart) — Chart types: LineChartView, BarChartView, StackedBarChartView. License: Apache-2.0.
- [**DecoView**](https://github.com/bmarrdev/android-DecoView-chart) — Circular arc charts. License: MIT.
- [**HelloChart**](https://github.com/lecho/hellocharts-android) — Chart types: LineChartView, ColumnChartView, PieChartView, BubbleChartView, ComboChartView, PreviewChartView. License: Apache-2.0.
- [**EazeGraph**](https://github.com/blackfizz/EazeGraph) — Chart types: BarChart, StackedBarChart, PieChart, LineChart, RadarChart. License: Apache-2.0.

### iOS

- [**Charts (iOS)**](https://github.com/danielgindi/Charts) — Port of MPAndroidChart. Swift/Obj-C. Chart types: LineChart, BarChart, HorizontalBarChart, CandleStickChart, PieChart, ScatterChart, BubbleChart, RadarChart, CombinedChart. License: Apache-2.0.
- [**PNChart**](https://github.com/kevinzhow/PNChart) — Chart types: PNLineChart, PNBarChart, PNPieChart, PNCircleChart, PNScatterChart, PNRadarChart. License: MIT.
- [**BEMSimpleLineGraph**](https://github.com/Boris-Em/BEMSimpleLineGraph) — Line graphs. License: MIT.
- [**SwiftChart**](https://github.com/gpbl/SwiftChart) — Line, area charts. License: MIT.
- [**FSInteractiveMap**](https://github.com/ArthurGuibert/FSInteractiveMap) — Interactive SVG map charts. License: MIT.

### Cross-Platform

- [**FL Chart (Flutter)**](https://github.com/imaNNeo/fl_chart) — Chart types: LineChart, BarChart, PieChart, ScatterChart, RadarChart. License: MIT.
- [**Syncfusion Flutter Charts**](https://github.com/syncfusion/flutter-examples) — Chart types: line, spline, area, spline area, column, range column, bar, stacking column, stacking bar, range bar, pie, doughnut, funnel, pyramid, radial bar, radar, polar, hi-low, hi-low-open-close, candle. License: proprietary (free tier available).
- [**React Native SVG Charts**](https://github.com/JesperLekland/react-native-svg-charts) — Chart types: LineChart, Grid, AreaChart, BarChart, PieChart, ProgressCircle, Layer, Decorators, XAxis, YAxis. License: MIT.
- [**Victory Native**](https://github.com/FormidableLabs/victory-native-xl) — React Native charting using Skia. Components: Chart, Line, Path, BoxPlot, Candlestick, Voronoi, Scatter, Area, Bar, Group, Stack, Axis, Grid, Label, Tooltip, Legend, Brush. License: MIT.

---

## 3D Visualization

- [**Three.js**](https://threejs.org/) — WebGL 3D library. Features: geometries (Box, Sphere, Cylinder, Cone, Plane, Ring, Torus, Lathe, Extrude, Tube, Polyhedron, Icosahedron, Octahedron, Tetrahedron, Dodecahedron, Shape, Text), materials (MeshStandard, MeshPhong, MeshLambert, MeshBasic, MeshNormal, MeshDepth, MeshDistance, MeshPhysical, MeshMatcap, MeshToon, Shadow, Sprite), lighting (Ambient, Directional, Point, Spot, Hemisphere, RectArea), rendering (WebGLRenderer, WebGL1Renderer, WebGPURenderer). License: MIT.
- [**Babylon.js**](https://www.babylonjs.com/) — 3D engine. WebGL/WebGPU. Features: meshes, materials, textures, lights, cameras, animations, physics, collisions, particles, post-processing, shaders, GUI. License: Apache-2.0.
- [**Deck.gl**](https://deck.gl/) — GPU-accelerated geospatial layers. Layer types: ArcLayer, BitmapLayer, ColumnLayer, GeoJsonLayer, GridLayer, HeatmapLayer, HexagonLayer, IconLayer, LineLayer, PathLayer, PointCloudLayer, PolygonLayer, ScatterplotLayer, ScreenGridLayer, SolidPolygonLayer, TextLayer, TileLayer, TripsLayer. License: MIT.
- [**SciChart.js**](https://www.scichart.com/) — WebGL/WebAssembly rendering. 2D/3D charts, heatmaps. Chart types: line, scatter, column, mountain, candlestick, OHLC, error, heatmap, contour, polar, radar, pie, donut, funnel, surface mesh, 3D scatter, 3D surface. License: proprietary.
- [**D3-3D**](https://github.com/Niekes/d3-3d) — 3D projection for D3.js. License: MIT.
- [**Kepler.gl**](https://kepler.gl/) — Large-scale geospatial analysis. deck.gl-based. License: MIT.
- [**OGL**](https://oframe.github.io/ogl/) — Minimal WebGL library. License: MIT.
- [**Regl**](https://regl.party/) — Functional WebGL state management. License: MIT.
- [**A-Frame**](https://aframe.io/) — WebVR framework built on Three.js. HTML-based scene graph. License: MIT.
- [**Luma.gl**](https://luma.gl/) — WebGL2-powered rendering. Part of vis.gl ecosystem. License: MIT.
- [**MathBox.js**](https://github.com/unconed/mathbox) — 3D/4D math visualization. Built on Three.js. License: MIT.

---

## SVG, Canvas & Graphics Libraries

- [**Snap.svg**](https://snapsvg.io/) — SVG manipulation library. License: Apache-2.0.
- [**Raphaël**](https://raphaeljs.com/) — Cross-browser SVG/VML abstraction. License: MIT.
- [**Fabric.js**](https://fabricjs.com/) — Canvas library with object model. SVG parsing. License: MIT.
- [**Paper.js**](http://paperjs.org/) — Vector graphics scripting. License: MIT.
- [**Two.js**](https://two.js.org/) — Renderer-agnostic 2D API. License: MIT.
- [**p5.js**](https://p5js.org/) — Creative coding. License: LGPL-2.1.
- [**Konva.js**](https://konvajs.org/) — 2D Canvas library with stage/layer/shapes model. License: MIT.
- [**RoughJS**](https://roughjs.com/) — Sketchy hand-drawn style. License: MIT.
- [**SVG.js**](https://svgjs.dev/) — SVG manipulation library. License: MIT.

---

## Animation Libraries

- [**GSAP (GreenSock)**](https://greensock.com/) — Timeline-based animation. Works with SVG, Canvas, DOM. License: standard license (free for most non-commercial; Club GreenSock for commercial features).
- [**Anime.js**](https://animejs.com/) — CSS, SVG, DOM, JS property animation. License: MIT.
- [**Motion (Framer Motion)**](https://motion.dev/) — React animation library. Layout animations, gestures, SVG paths. License: MIT.
- [**Lottie (Bodymovin)**](https://airbnb.io/lottie/) — JSON-based animations from After Effects. Platforms: Web, iOS, Android, React Native. License: Apache-2.0.
- [**Popmotion**](https://popmotion.io/) — Spring, decay, keyframe tweens. License: MIT.
- [**Vivus**](https://maxwellito.github.io/vivus/) — SVG drawing animation. License: MIT.

---

## Graph & Network Visualization

- [**Cytoscape.js**](https://js.cytoscape.org/) — Graph theory: BFS, DFS, Dijkstra, PageRank, betweenness. Layouts: grid, circle, concentric, breadth-first, cose, cose-bilkent, euler, spread, klay, dagre, avsdf. JSON serialization. License: MIT.
- [**Sigma.js**](https://www.sigmajs.org/) — WebGL graph rendering. Layouts: ForceAtlas2, ForceLink, Circular, Random. License: MIT.
- [**VivaGraph**](https://github.com/anvaka/VivaGraphJS) — Force-directed, N-body layout. License: BSD-3-Clause.
- [**Vis.js Network**](https://visjs.github.io/vis-network/) — Dynamic network visualization. Layouts: hierarchical, force-directed. License: Apache-2.0/MIT (dual).
- [**Gephi**](https://gephi.org/) — Desktop application. Layouts: ForceAtlas2, Yifan Hu, Fruchterman-Reingold, OpenORD, Label Propagation, Layout Run. License: CDDL-1.0.
- [**Graphology**](https://graphology.github.io/) — Graph data structure. Methods: BFS, DFS, connected components, centrality, degree, density. License: MIT.
- [**Netwulf**](https://netwulf.readthedocs.io/) — Python + D3 interactive network visualization. License: MIT.
- [**ngraph**](https://github.com/anvaka/ngraph.graph) — Graph data structure with 20+ layout algorithms. License: BSD-3-Clause.
- [**Graphin**](https://graphin.antv.vision/) — React + G6 graph analysis toolkit. License: MIT.

---

## Mapping & Geospatial

- [**Leaflet**](https://leafletjs.com/) — Tile layers, markers, polygons, GeoJSON. Plugin ecosystem available. License: BSD-2-Clause.
- [**Mapbox GL JS**](https://docs.mapbox.com/mapbox-gl-js/) — Vector tiles. WebGL. Requires Mapbox access token (usage-based pricing for high volume). License: proprietary (BSD-3-Clause for v1.x).
- [**OpenLayers**](https://openlayers.org/) — 2D map library. Supports WMS, WMTS, Vector tiles. License: BSD-2-Clause.
- [**CARTO**](https://carto.com/) — Geospatial platform. deck.gl-based widgets. License: proprietary with open-source components.
- [**Cesium**](https://cesium.com/cesiumjs/) — 3D globe and map engine. 3D Tiles, terrain, imagery. License: Apache-2.0.
- [**DataMaps**](https://datamaps.github.io/) — D3-based SVG maps. License: MIT.
- [**D3-geo**](https://d3js.org/d3-geo) — Projections: Mercator, Albers, Orthographic, Azimuthal, Conic, Cylindrical. License: ISC.
- [**Turf.js**](https://turfjs.org/) — Geospatial analysis: buffers, unions, intersects, distance, area, along, nearest, transform, measurement, interpolation, classification, conversion, helper. License: MIT.
- [**MapLibre GL JS**](https://maplibre.org/) — Fork of Mapbox GL JS v2 (before license change). Open-source. License: Apache-2.0.
- [**GeoJSON.io**](http://geojson.io/) — Browser-based GeoJSON editor. License: ISC.
- [**IPyleaflet**](https://ipyleaflet.readthedocs.io/) — Leaflet maps in Jupyter notebooks. License: MIT.

---

## Infrastructure as Code Diagrams

- [**Diagrams (Python)**](https://diagrams.mingrammer.com/) — Provider nodes: AWS, Azure, GCP, Kubernetes, DigitalOcean, Oracle Cloud, Firebase, IoT, Programming, Generic. License: MIT.
- [**Cloudcraft**](https://www.cloudcraft.co/) — AWS architecture diagrams with live data import. 3D visualization. License: proprietary (AWS subsidiary).
- [**TerraformGraph**](https://pypi.org/project/terraformgraph/) — Parses Terraform state to generate interactive diagrams. License: MIT.
- [**Cloudiscovery**](https://github.com/cloud-craft/cloudiscovery) — Discovers cloud resources and generates diagrams. Supports AWS, GCP, Azure, AliCloud, Tencent. License: MIT.
- [**Kubevious**](https://kubevious.io/) — Kubernetes visualization: application-centric view, rules engine, time machine. License: Apache-2.0.
- [**Kiali**](https://kiali.io/) — Istio service mesh observability. Graph of traffic flow, health, metrics. License: Apache-2.0.

---

## Whiteboard & Collaborative Tools

- [**Excalidraw**](https://excalidraw.com/) — End-to-end encrypted. Exports to PNG, SVG, clipboard. Self-hostable. License: MIT.
- [**tldraw**](https://www.tldraw.com/) — SDK for building whiteboard experiences. Smart arrows, snapping, sticky notes. Self-hostable. License: seaware (free for most uses).
- [**diagrams.net (Draw.io)**](https://www.diagrams.net/) — Desktop and web versions. Offline mode. Exports to PNG, SVG, PDF, HTML, XML. 50+ shape libraries. License: Apache-2.0.
- [**Lucidchart**](https://www.lucidchart.com/) — Real-time collaboration. Enterprise integrations: Google Workspace, Microsoft 365, Atlassian. License: proprietary.
- [**Miro**](https://miro.com/) — Collaborative whiteboard. REST API, SDKs, 150+ integrations. License: proprietary.
- [**Figma (FigJam)**](https://www.figma.com/figjam/) — Whiteboard within Figma design ecosystem. License: proprietary.
- [**Obsidian Canvas**](https://obsidian.md/canvas) — Visual canvas in Obsidian knowledge base. Local-first. License: proprietary.
- [**Heptabase**](https://heptabase.com/) — Visual note-taking and knowledge management. License: proprietary.

---

## Diagramming SDKs & Frameworks

- [**JointJS+**](https://jointjs.com/) — Commercial extension to JointJS. 200+ stencils, undo/redo, clipboard, cell tools, inspector. License: proprietary.
- [**GoJS**](https://gojs.net/latest/index.html) — Diagram types: flowchart, org chart, BPMN, UML, ER, Gantt, Sankey, force-directed, mind map. License: proprietary.
- [**mxGraph**](https://github.com/jgraph/mxgraph) — Base library for Draw.io. License: Apache-2.0. Repository archived.
- [**diagrams.js**](https://github.com/bpmn-io/diagram-js) — Extensible diagramming toolkit. License: MIT.
- [**Eclipse Sprotty**](https://www.eclipse.org/sprotty/) — Web-based diagramming framework. Client (TypeScript) + server (Java) architecture. License: EPL-2.0.
- [**Eclipse GLSP**](https://www.eclipse.org/glsp/) — Graphical Language Server Platform. Language Server Protocol-based. License: EPL-2.0.

---

## CLI Tools

- [**Mermaid CLI**](https://github.com/mermaid-js/mermaid-cli) — Puppeteer-based rendering. Outputs PNG, SVG, PDF. License: MIT.
- [**D2 CLI**](https://github.com/terrastruct/d2) — Binary releases for Linux, macOS, Windows. Outputs SVG, PNG. Layout engines: D2, ELK, TALA. License: MPL-2.0.
- [**PlantUML CLI**](https://plantuml.com/command-line) — Requires Java. Outputs PNG, SVG, PDF, VDX, XCF. License: GPL/LGPL/EPL.
- [**Graphviz CLI**](https://graphviz.org/download/) — Commands: `dot`, `neato`, `fdp`, `sfdp`, `circo`, `twopi`, `osage`, `patchwork`.
- [**diagram CLI**](https://github.com/esimov/diagram) — ASCII art to hand-drawn style diagrams. Go-based binary. License: MIT.
- [**Vega CLI**](https://vega.github.io/vega/usage/) — Node.js-based rendering. Outputs PNG, SVG, PDF. License: BSD-3-Clause.
- [**Marp CLI**](https://marp.app/) — Markdown presentation to PDF, HTML, PNG. License: MIT.
- [**Slidev**](https://sli.dev/) — Markdown-based slides for developers. Supports Mermaid diagrams. License: MIT.
- [**Nomnoml CLI**](https://github.com/skanaar/nomnoml) — CLI wrapper for Nomnoml UML. License: MIT.

---

## Online Editors & Platforms

- [**Mermaid Live Editor**](https://mermaid.live/) — In-browser rendering. Share via URL. Export PNG, SVG. Open-source.
- [**Draw.io**](https://app.diagrams.net/) — Browser and desktop. Local file storage, Google Drive, GitHub, GitLab. Open-source.
- [**Drawbly**](https://drawbly.com/) — Browser canvas for freehand technical diagrams with editable text; no signup, local drafts, credited PNG export. License: proprietary.
- [**Excalidraw**](https://excalidraw.com/) — Browser-based. Real-time collaboration. Open-source.
- [**D2 Playground**](https://play.d2lang.com/) — In-browser D2 diagram editor.
- [**PlantText**](https://www.planttext.com/) — Browser-based PlantUML editor.
- [**Kroki**](https://kroki.io/) — REST API: `POST /{type}` returns rendered diagram. Self-hostable. Open-source.
- [**Observable**](https://observablehq.com/) — Notebook environment. Reactive dataflow. D3.js integration. Free tier available.
- [**RAWGraphs**](https://rawgraphs.io/) — Drag-and-drop mapping. Exports to SVG. Open-source.
- [**CodePen**](https://codepen.io/) — Front-end playground. D3.js, Chart.js examples.
- [**JSFiddle**](https://jsfiddle.net/) — Online code editor for HTML/CSS/JS.
- [**StackBlitz**](https://stackblitz.com/) — Online VS Code environment. Supports React/Vue/Angular chart projects.
- [**CodeSandbox**](https://codesandbox.io/) — Online development environment. Chart library templates.

---

## Specialized Diagram Types

### UML & Software Design

- [**PlantUML**](https://plantuml.com/) — Diagram types: sequence, use case, class, activity, component, state, object, deployment, timing, network, salt, Gantt, math, mindmap, AsciiMath.
- [**JointJS+**](https://jointjs.com/) — UML class, state, activity, deployment, component diagrams. Commercial.
- [**Web Sequence Diagrams**](https://www.websequencediagrams.com/) — Sequence diagrams from text. Multiple styles. License: proprietary (free tier).
- [**Structurizr**](https://structurizr.com/) — C4 model: Context, Container, Component, Code diagrams. DSL and Java/Python/Go libraries.
- [**Mermaid Class/State/Sequence**](https://mermaid.js.org/) — Text-based UML. Supports class, state, sequence, er diagrams.
- [**ZenUML**](https://zenuml.com/) — Sequence diagrams from code-like syntax. License: proprietary (free tier).

### Neural Network & AI Architectures

- [**NN-SVG**](https://alexlenail.me/NN-SVG/) — Generates SVG of neural network architectures: FCNN, LeNet, AlexNet. D3-based. Open-source.
- [**Netron**](https://netron.app/) — Visualizes models from: ONNX, TensorFlow Lite, Keras, Caffe, PyTorch, Core ML, Darknet. Desktop and web. License: MIT.
- [**PlotNeuralNet**](https://github.com/HarisIqbal88/PlotNeuralNet) — LaTeX/TikZ-based neural network diagrams. License: MIT.
- [**TensorBoard Graphs**](https://www.tensorflow.org/tensorboard/graphs) — Visualizes TensorFlow computation graphs.
- [**Torchviz**](https://github.com/szagoruyko/pytorchviz) — PyTorch execution graph visualization via Graphviz. License: MIT.

### Timelines & Gantt

- [**TimelineJS**](https://timeline.knightlab.com/) — Google Sheets-backed timeline. Media embedding: YouTube, Vimeo, Google Maps, Wikipedia. License: MPL-2.0.
- [**Vis.js Timeline**](https://visjs.github.io/vis-timeline/) — Interactive time series. Grouping, editable, drag-drop. License: Apache-2.0/MIT.
- [**Frappe Gantt**](https://frappe.io/gantt) — SVG Gantt charts. Drag-to-resize, dependency lines. License: MIT.
- [**Mermaid Gantt**](https://mermaid.js.org/syntax/gantt.html) — Gantt from markdown-like text.
- [**Gantt-elastic**](https://github.com/neuronetio/gantt-elastic) — JavaScript Gantt with Vue.js integration. License: MIT.

### Mind Maps & Concept Maps

- [**Markmap**](https://markmap.js.org/) — Markdown to mind map. VS Code extension, CLI, web. License: MIT.
- [**MindElixir**](https://github.com/ssshooter/mind-elixir-core) — Framework-agnostic. Drag-and-drop, keyboard navigation. License: MIT.
- [**jsMind**](https://hizzgdev.github.io/jsmind/) — JSON-based mind map. License: BSD-3-Clause.
- [**KityMinder**](https://github.com/fex-team/kityminder) — Baidu's mind map editor. License: BSD-3-Clause.

### Heatmaps & Calendars

- [**Cal-Heatmap**](https://cal-heatmap.com/) — Time-series calendar. Configurable: daily, weekly, monthly. License: MIT.
- [**d3-calendar**](https://github.com/yuanqing/d3-calendar) — Calendar heatmap via D3. License: MIT.
- [**React Heatmap GitHub**](https://github.com/trekhleb/react-heatmap-github) — GitHub contribution-style heatmap. License: MIT.

### Org Charts & Hierarchical

- [**OrgChart.js**](https://dabeng.github.io/OrgChart/) — HTML/JSON-based org chart. Export to PDF/PNG. License: MIT.
- [**Balkan OrgChart**](https://balkangraph.com/) — JavaScript org chart library. License: proprietary (free tier).
- [**GoJS Org Chart**](https://gojs.net/latest/samples/orgChartEditor.html) — Org chart with GoJS.

### ERD & Database

- [**DBML**](https://www.dbml.org/) — Database markup language. Online editor, CLI, VS Code extension. License: MIT.
- [**SqlDBM**](https://sqldbm.com/) — Browser-based database design. Supports MySQL, PostgreSQL, SQL Server, Snowflake. License: proprietary (free tier).
- [**QuickDBD**](https://www.quickdatabasediagrams.com/) — Text-to-ERD. License: proprietary (free tier).
- [**Mermaid ER**](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) — Entity-relationship diagrams from text.
- [**Nomnoml**](https://www.nomnoml.com/) — UML class diagrams, which can represent database schemas.

### Network Topology

- [**Netbox**](https://netboxlabs.com/) — IP address management and data center infrastructure management. Source of truth for network. License: Apache-2.0.
- [**LibreNMS**](https://www.librenms.org/) — Auto-discovering network monitoring with topology maps. License: GPL-3.0.
- [**Oxidized + Topology**](https://github.com/ytti/oxidized) — Network device configuration backup with topology visualization. License: Apache-2.0.

---

## Data Sources & Formats

- [**JSON**](https://www.json.org/) — Most chart libraries accept JSON arrays/objects as input.
- [**CSV/TSV**](https://tools.ietf.org/html/rfc4180) — Tabular data; D3 provides `d3.csv()` and `d3.tsv()` parsers.
- [**GeoJSON**](https://geojson.org/) — Geographic data structure. Supported by Leaflet, Mapbox, D3-geo, deck.gl.
- [**TopoJSON**](https://github.com/topojson/topojson) — Extension of GeoJSON for topology.
- [**XML/SVG**](https://www.w3.org/TR/SVG/) — Vector graphics format. Fabric.js, Snap.svg, SVG.js manipulate SVG.
- [**YAML**](https://yaml.org/) — Used by D2, Structurizr DSL, Archimatexl for diagram definitions.
- [**DOT**](https://graphviz.org/doc/info/lang.html) — Graphviz graph description language.
- [**Protocol Buffers (Protobuf)**](https://protobuf.dev/) — Used by some visualization backends for data serialization.

---

## Resources

### Learning & Inspiration

- [**Observable**](https://observablehq.com/) — JavaScript notebook platform. D3.js examples. Free tier available.
- [**From Data to Viz**](https://www.data-to-viz.com/) — Decision tree for chart type selection. R code examples.
- [**Data Viz Project**](https://datavizproject.com/) — Catalog of visualization types with names, descriptions, and use cases.
- [**The Data Visualisation Catalogue**](https://datavizcatalogue.com/) — Non-technical guide to chart types and their purposes.
- [**D3 Graph Gallery**](https://www.d3-graph-gallery.com/) — D3.js chart examples with code.
- [**Makeover Monday**](https://makeovermonday.co.uk/) — Weekly community data visualization challenge.
- [**Information is Beautiful**](https://informationisbeautiful.net/) — Data visualization showcase and blog.
- [**FlowingData**](https://flowingdata.com/) — Data visualization blog and tutorials.

### Awesome Lists

- [**Awesome Data Visualization**](https://github.com/JSJenny/awesome-dataviz) — Tools, libraries, and resources.
- [**Awesome Chart.js**](https://github.com/chartjs/awesome) — Plugins, wrappers, tools for Chart.js.
- [**Awesome D3**](https://github.com/wbkd/awesome-d3) — D3.js libraries and tools.
- [**Awesome Vega**](https://github.com/vega/awesome-vega) — Vega and Vega-Lite resources.
- [**Awesome GeoJSON**](https://github.com/tmcw/awesome-geojson) — GeoJSON datasets and tools.
- [**Awesome Visualization**](https://github.com/znarly/awesome-visualization) — Resources for creating data visualizations.
- [**Awesome Three.js**](https://github.com/sindresorhus/awesome-three) — Three.js resources.
- [**Awesome Maps**](https://github.com/mapbox/awesome-maps) — Mapping tools, APIs, data sources.

### Design Guidelines

- [**Google Charts Best Practices**](https://developers.google.com/chart/interactive/docs/gallery) — Chart type selection guidelines.
- [**Nightingale (DVS)**](https://www.nightingale-dvs.com/) — Data visualization society. Journal and community.
- [**Storytelling with Data**](https://www.storytellingwithdata.com/) — Communication strategies for data visualization. Book by Cole Nussbaumer Knaflic.
- [**Financial Times Visual Vocabulary**](https://github.com/Financial-Times/chart-doctor) — Chart selection reference.
- [**IBM Charting Guidelines**](https://carbondesignsystem.com/data-visualization/chart-chooser/) — Part of Carbon Design System.
- [**Salesforce Einstein Visualization Guidelines**](https://www.lightningdesignsystem.com/guidelines/charts/) — Part of Lightning Design System.

---

## Contributing

Contributions are welcome. Please review the guidelines below before submitting.

### Contribution Guidelines

- Add one link per Pull Request
- Format: `- [**name**](url) — description. License: X.`
- Keep descriptions factual: what the tool does, chart/diagram types it supports, rendering method
- Include license type where available
- Search existing entries to avoid duplicates
- Place entries alphabetically within each section
- Remove trailing whitespace

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This work is dedicated to the public domain under CC0 1.0 Universal.
