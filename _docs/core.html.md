# core


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

``` python
df.hvplot()
```

<div id='p1006'>
  <div id="edbe6822-9d0c-4b68-b78c-5033b757555b" data-root-id="p1006" style="display: contents;"></div>
</div>
<script type="application/javascript">(function(root) {
  var docs_json = {"b0c51a7f-1293-4bbf-910c-a00fcfeae197":{"version":"3.5.2","title":"Bokeh Application","roots":[{"type":"object","name":"Row","id":"p1006","attributes":{"name":"Row00922","tags":["embedded"],"stylesheets":["\n:host(.pn-loading):before, .pn-loading:before {\n  background-color: #c3c3c3;\n  mask-size: auto calc(min(50%, 400px));\n  -webkit-mask-size: auto calc(min(50%, 400px));\n}",{"type":"object","name":"ImportedStyleSheet","id":"p1009","attributes":{"url":"https://cdn.holoviz.org/panel/1.5.2/dist/css/loading.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1067","attributes":{"url":"https://cdn.holoviz.org/panel/1.5.2/dist/css/listpanel.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1007","attributes":{"url":"https://cdn.holoviz.org/panel/1.5.2/dist/bundled/theme/default.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1008","attributes":{"url":"https://cdn.holoviz.org/panel/1.5.2/dist/bundled/theme/native.css"}}],"min_width":700,"margin":0,"sizing_mode":"stretch_width","align":"start","children":[{"type":"object","name":"Spacer","id":"p1010","attributes":{"name":"HSpacer00929","stylesheets":["\n:host(.pn-loading):before, .pn-loading:before {\n  background-color: #c3c3c3;\n  mask-size: auto calc(min(50%, 400px));\n  -webkit-mask-size: auto calc(min(50%, 400px));\n}",{"id":"p1009"},{"id":"p1007"},{"id":"p1008"}],"margin":0,"sizing_mode":"stretch_width","align":"start"}},{"type":"object","name":"Figure","id":"p1018","attributes":{"width":700,"height":300,"margin":[5,10],"sizing_mode":"fixed","align":"start","x_range":{"type":"object","name":"Range1d","id":"p1011","attributes":{"tags":[[["index",null]],[]],"end":9.0,"reset_start":0.0,"reset_end":9.0}},"y_range":{"type":"object","name":"Range1d","id":"p1012","attributes":{"tags":[[["a",null]],{"type":"map","entries":[["invert_yaxis",false],["autorange",false]]}],"start":-0.9,"end":9.9,"reset_start":-0.9,"reset_end":9.9}},"x_scale":{"type":"object","name":"LinearScale","id":"p1028"},"y_scale":{"type":"object","name":"LinearScale","id":"p1029"},"title":{"type":"object","name":"Title","id":"p1021","attributes":{"text_color":"black","text_font_size":"12pt"}},"renderers":[{"type":"object","name":"GlyphRenderer","id":"p1060","attributes":{"data_source":{"type":"object","name":"ColumnDataSource","id":"p1051","attributes":{"selected":{"type":"object","name":"Selection","id":"p1052","attributes":{"indices":[],"line_indices":[]}},"selection_policy":{"type":"object","name":"UnionRenderers","id":"p1053"},"data":{"type":"map","entries":[["index",{"type":"ndarray","array":{"type":"bytes","data":"AAAAAAEAAAACAAAAAwAAAAQAAAAFAAAABgAAAAcAAAAIAAAACQAAAA=="},"shape":[10],"dtype":"int32","order":"little"}],["a",{"type":"ndarray","array":{"type":"bytes","data":"AAAAAAEAAAACAAAAAwAAAAQAAAAFAAAABgAAAAcAAAAIAAAACQAAAA=="},"shape":[10],"dtype":"int32","order":"little"}]]}}},"view":{"type":"object","name":"CDSView","id":"p1061","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1062"}}},"glyph":{"type":"object","name":"Line","id":"p1057","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"index"},"y":{"type":"field","field":"a"},"line_color":"#30a2da","line_width":2}},"selection_glyph":{"type":"object","name":"Line","id":"p1063","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"index"},"y":{"type":"field","field":"a"},"line_color":"#30a2da","line_width":2}},"nonselection_glyph":{"type":"object","name":"Line","id":"p1058","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"index"},"y":{"type":"field","field":"a"},"line_color":"#30a2da","line_alpha":0.1,"line_width":2}},"muted_glyph":{"type":"object","name":"Line","id":"p1059","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"index"},"y":{"type":"field","field":"a"},"line_color":"#30a2da","line_alpha":0.2,"line_width":2}}}}],"toolbar":{"type":"object","name":"Toolbar","id":"p1027","attributes":{"tools":[{"type":"object","name":"WheelZoomTool","id":"p1016","attributes":{"tags":["hv_created"],"renderers":"auto","zoom_together":"none"}},{"type":"object","name":"HoverTool","id":"p1017","attributes":{"tags":["hv_created"],"renderers":[{"id":"p1060"}],"tooltips":[["index","@{index}"],["a","@{a}"]]}},{"type":"object","name":"SaveTool","id":"p1040"},{"type":"object","name":"PanTool","id":"p1041"},{"type":"object","name":"BoxZoomTool","id":"p1042","attributes":{"overlay":{"type":"object","name":"BoxAnnotation","id":"p1043","attributes":{"syncable":false,"line_color":"black","line_alpha":1.0,"line_width":2,"line_dash":[4,4],"fill_color":"lightgrey","fill_alpha":0.5,"level":"overlay","visible":false,"left":{"type":"number","value":"nan"},"right":{"type":"number","value":"nan"},"top":{"type":"number","value":"nan"},"bottom":{"type":"number","value":"nan"},"left_units":"canvas","right_units":"canvas","top_units":"canvas","bottom_units":"canvas","handles":{"type":"object","name":"BoxInteractionHandles","id":"p1049","attributes":{"all":{"type":"object","name":"AreaVisuals","id":"p1048","attributes":{"fill_color":"white","hover_fill_color":"lightgray"}}}}}}}},{"type":"object","name":"ResetTool","id":"p1050"}],"active_drag":{"id":"p1041"},"active_scroll":{"id":"p1016"}}},"left":[{"type":"object","name":"LinearAxis","id":"p1035","attributes":{"ticker":{"type":"object","name":"BasicTicker","id":"p1036","attributes":{"mantissas":[1,2,5]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1037"},"axis_label":"a","major_label_policy":{"type":"object","name":"AllLabels","id":"p1038"}}}],"below":[{"type":"object","name":"LinearAxis","id":"p1030","attributes":{"ticker":{"type":"object","name":"BasicTicker","id":"p1031","attributes":{"mantissas":[1,2,5]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1032"},"axis_label":"","major_label_policy":{"type":"object","name":"AllLabels","id":"p1033"}}}],"center":[{"type":"object","name":"Grid","id":"p1034","attributes":{"axis":{"id":"p1030"},"grid_line_color":null}},{"type":"object","name":"Grid","id":"p1039","attributes":{"dimension":1,"axis":{"id":"p1035"},"grid_line_color":null}}],"min_border_top":10,"min_border_bottom":10,"min_border_left":10,"min_border_right":10,"output_backend":"webgl"}},{"type":"object","name":"Spacer","id":"p1065","attributes":{"name":"HSpacer00930","stylesheets":["\n:host(.pn-loading):before, .pn-loading:before {\n  background-color: #c3c3c3;\n  mask-size: auto calc(min(50%, 400px));\n  -webkit-mask-size: auto calc(min(50%, 400px));\n}",{"id":"p1009"},{"id":"p1007"},{"id":"p1008"}],"margin":0,"sizing_mode":"stretch_width","align":"start"}}]}}],"defs":[{"type":"model","name":"ReactiveHTML1"},{"type":"model","name":"FlexBox1","properties":[{"name":"align_content","kind":"Any","default":"flex-start"},{"name":"align_items","kind":"Any","default":"flex-start"},{"name":"flex_direction","kind":"Any","default":"row"},{"name":"flex_wrap","kind":"Any","default":"wrap"},{"name":"gap","kind":"Any","default":""},{"name":"justify_content","kind":"Any","default":"flex-start"}]},{"type":"model","name":"FloatPanel1","properties":[{"name":"config","kind":"Any","default":{"type":"map"}},{"name":"contained","kind":"Any","default":true},{"name":"position","kind":"Any","default":"right-top"},{"name":"offsetx","kind":"Any","default":null},{"name":"offsety","kind":"Any","default":null},{"name":"theme","kind":"Any","default":"primary"},{"name":"status","kind":"Any","default":"normalized"}]},{"type":"model","name":"GridStack1","properties":[{"name":"mode","kind":"Any","default":"warn"},{"name":"ncols","kind":"Any","default":null},{"name":"nrows","kind":"Any","default":null},{"name":"allow_resize","kind":"Any","default":true},{"name":"allow_drag","kind":"Any","default":true},{"name":"state","kind":"Any","default":[]}]},{"type":"model","name":"drag1","properties":[{"name":"slider_width","kind":"Any","default":5},{"name":"slider_color","kind":"Any","default":"black"},{"name":"value","kind":"Any","default":50}]},{"type":"model","name":"click1","properties":[{"name":"terminal_output","kind":"Any","default":""},{"name":"debug_name","kind":"Any","default":""},{"name":"clears","kind":"Any","default":0}]},{"type":"model","name":"FastWrapper1","properties":[{"name":"object","kind":"Any","default":null},{"name":"style","kind":"Any","default":null}]},{"type":"model","name":"NotificationAreaBase1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0}]},{"type":"model","name":"NotificationArea1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"notifications","kind":"Any","default":[]},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0},{"name":"types","kind":"Any","default":[{"type":"map","entries":[["type","warning"],["background","#ffc107"],["icon",{"type":"map","entries":[["className","fas fa-exclamation-triangle"],["tagName","i"],["color","white"]]}]]},{"type":"map","entries":[["type","info"],["background","#007bff"],["icon",{"type":"map","entries":[["className","fas fa-info-circle"],["tagName","i"],["color","white"]]}]]}]}]},{"type":"model","name":"Notification","properties":[{"name":"background","kind":"Any","default":null},{"name":"duration","kind":"Any","default":3000},{"name":"icon","kind":"Any","default":null},{"name":"message","kind":"Any","default":""},{"name":"notification_type","kind":"Any","default":null},{"name":"_destroyed","kind":"Any","default":false}]},{"type":"model","name":"TemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"BootstrapTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"TemplateEditor1","properties":[{"name":"layout","kind":"Any","default":[]}]},{"type":"model","name":"MaterialTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"ReactiveESM1"},{"type":"model","name":"JSComponent1"},{"type":"model","name":"ReactComponent1"},{"type":"model","name":"AnyWidgetComponent1"},{"type":"model","name":"request_value1","properties":[{"name":"fill","kind":"Any","default":"none"},{"name":"_synced","kind":"Any","default":null},{"name":"_request_sync","kind":"Any","default":0}]}]}};
  var render_items = [{"docid":"b0c51a7f-1293-4bbf-910c-a00fcfeae197","roots":{"p1006":"edbe6822-9d0c-4b68-b78c-5033b757555b"},"root_ids":["p1006"]}];
  var docs = Object.values(docs_json)
  if (!docs) {
    return
  }
  const py_version = docs[0].version.replace('rc', '-rc.').replace('.dev', '-dev.')
  async function embed_document(root) {
    var Bokeh = get_bokeh(root)
    await Bokeh.embed.embed_items_notebook(docs_json, render_items);
    for (const render_item of render_items) {
      for (const root_id of render_item.root_ids) {
    const id_el = document.getElementById(root_id)
    if (id_el.children.length && id_el.children[0].hasAttribute('data-root-id')) {
      const root_el = id_el.children[0]
      root_el.id = root_el.id + '-rendered'
      for (const child of root_el.children) {
            // Ensure JupyterLab does not capture keyboard shortcuts
            // see: https://jupyterlab.readthedocs.io/en/4.1.x/extension/notebook.html#keyboard-interaction-model
        child.setAttribute('data-lm-suppress-shortcuts', 'true')
      }
    }
      }
    }
  }
  function get_bokeh(root) {
    if (root.Bokeh === undefined) {
      return null
    } else if (root.Bokeh.version !== py_version) {
      if (root.Bokeh.versions === undefined || !root.Bokeh.versions.has(py_version)) {
    return null
      }
      return root.Bokeh.versions.get(py_version);
    } else if (root.Bokeh.version === py_version) {
      return root.Bokeh
    }
    return null
  }
  function is_loaded(root) {
    var Bokeh = get_bokeh(root)
    return (Bokeh != null && Bokeh.Panel !== undefined)
  }
  if (is_loaded(root)) {
    embed_document(root);
  } else {
    var attempts = 0;
    var timer = setInterval(function(root) {
      if (is_loaded(root)) {
        clearInterval(timer);
        embed_document(root);
      } else if (document.readyState == "complete") {
        attempts++;
        if (attempts > 200) {
          clearInterval(timer);
      var Bokeh = get_bokeh(root)
      if (Bokeh == null || Bokeh.Panel == null) {
            console.warn("Panel: ERROR: Unable to run Panel code because Bokeh or Panel library is missing");
      } else {
        console.warn("Panel: WARNING: Attempting to render but not all required libraries could be resolved.")
        embed_document(root)
      }
        }
      }
    }, 25, root)
  }
})(window);</script>
