<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_e7bef7aa87e92bc65c34b6776536fb7d {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/leaflet.markercluster.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.Default.css"/>
</head>
<body>
    
    
            <div class="folium-map" id="map_e7bef7aa87e92bc65c34b6776536fb7d" ></div>
        
</body>
<script>
    
    
            var map_e7bef7aa87e92bc65c34b6776536fb7d = L.map(
                "map_e7bef7aa87e92bc65c34b6776536fb7d",
                {
                    center: [45.497009, -122.704526],
                    crs: L.CRS.EPSG3857,
                    zoom: 10,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_169c125bc41cb8b26fd1f598799158a1 = L.tileLayer(
                "https://api.mapbox.com/styles/v1/nlandauer/clphqayo7006j01ol8ov94s2r/tiles/256/{z}/{x}/{y}@2x?access_token=pk.eyJ1IjoibmxhbmRhdWVyIiwiYSI6ImNsbzNtaGt1bzIyYWYyaW82eHBzeml2aG8ifQ.PUm_asgwYlN05xkz9Gyz4g",
                {"attribution": "Mapbox", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            );
        
    
                tile_layer_169c125bc41cb8b26fd1f598799158a1.addTo(map_e7bef7aa87e92bc65c34b6776536fb7d);
    
            var marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3 = L.markerClusterGroup(
                {}
            );
        
    
            var marker_42780f45c5f8389f905fcfd95555d86c = L.marker(
                [45.4837097, -122.8538306],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3d7c652c9d62e1267304f16da99000da = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_42780f45c5f8389f905fcfd95555d86c.setIcon(icon_3d7c652c9d62e1267304f16da99000da);
        
    
        var popup_bc12ed85795208239c5f8b238b1418df = L.popup({"maxWidth": "100%"});

        
            
                var html_f453259d297dee74d3d03674b63c44eb = $(`<div id="html_f453259d297dee74d3d03674b63c44eb" style="width: 100.0%; height: 100.0%;">Aloha-Huber Park School</div>`)[0];
                popup_bc12ed85795208239c5f8b238b1418df.setContent(html_f453259d297dee74d3d03674b63c44eb);
            
        

        marker_42780f45c5f8389f905fcfd95555d86c.bindPopup(popup_bc12ed85795208239c5f8b238b1418df)
        ;

        
    
    
            var marker_23e4f35bd197d1f0278041df028fd7fd = L.marker(
                [45.47608945, -122.8185452],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b1182168c62f48f93319e5c14c67f2e9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_23e4f35bd197d1f0278041df028fd7fd.setIcon(icon_b1182168c62f48f93319e5c14c67f2e9);
        
    
        var popup_71c8451ca3a21c71c45f5ec3a8b2ee18 = L.popup({"maxWidth": "100%"});

        
            
                var html_bda4d3aa4e926e24f163f5765e9528ef = $(`<div id="html_bda4d3aa4e926e24f163f5765e9528ef" style="width: 100.0%; height: 100.0%;">Arco Iris Spanish Immersion School</div>`)[0];
                popup_71c8451ca3a21c71c45f5ec3a8b2ee18.setContent(html_bda4d3aa4e926e24f163f5765e9528ef);
            
        

        marker_23e4f35bd197d1f0278041df028fd7fd.bindPopup(popup_71c8451ca3a21c71c45f5ec3a8b2ee18)
        ;

        
    
    
            var marker_33716ffe0c85f55ff4ce21664d077407 = L.marker(
                [45.50622363, -122.8184932],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_15e57320d2dbb198d75a2e52a201c225 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_33716ffe0c85f55ff4ce21664d077407.setIcon(icon_15e57320d2dbb198d75a2e52a201c225);
        
    
        var popup_9f05702dd62c3f413ff3e8dd22e96251 = L.popup({"maxWidth": "100%"});

        
            
                var html_e142224ebba0bb07fe7fbefaca49f72f = $(`<div id="html_e142224ebba0bb07fe7fbefaca49f72f" style="width: 100.0%; height: 100.0%;">Barnes Elementary School</div>`)[0];
                popup_9f05702dd62c3f413ff3e8dd22e96251.setContent(html_e142224ebba0bb07fe7fbefaca49f72f);
            
        

        marker_33716ffe0c85f55ff4ce21664d077407.bindPopup(popup_9f05702dd62c3f413ff3e8dd22e96251)
        ;

        
    
    
            var marker_32565e23abe608c826a02bf4da444a1d = L.marker(
                [45.50446535, -122.8528089],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e39895946e6024cc6bb239eecda106eb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_32565e23abe608c826a02bf4da444a1d.setIcon(icon_e39895946e6024cc6bb239eecda106eb);
        
    
        var popup_cc5a64a54c8cba16b053a089fe7fc308 = L.popup({"maxWidth": "100%"});

        
            
                var html_a6ba34e38ceb71cc09ae2a36246a1eef = $(`<div id="html_a6ba34e38ceb71cc09ae2a36246a1eef" style="width: 100.0%; height: 100.0%;">Beaver Acres Elementary School</div>`)[0];
                popup_cc5a64a54c8cba16b053a089fe7fc308.setContent(html_a6ba34e38ceb71cc09ae2a36246a1eef);
            
        

        marker_32565e23abe608c826a02bf4da444a1d.bindPopup(popup_cc5a64a54c8cba16b053a089fe7fc308)
        ;

        
    
    
            var marker_a358157af3606140e658158afe616c4e = L.marker(
                [45.54316227, -122.8579953],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c944292431cac2e6f2fbd4e6d497634f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a358157af3606140e658158afe616c4e.setIcon(icon_c944292431cac2e6f2fbd4e6d497634f);
        
    
        var popup_3d3717844fd9c359c8b6fc5e71c85ea7 = L.popup({"maxWidth": "100%"});

        
            
                var html_cdaee9fed4fd232af1e995bc4f8186d5 = $(`<div id="html_cdaee9fed4fd232af1e995bc4f8186d5" style="width: 100.0%; height: 100.0%;">Bethany Elementary School</div>`)[0];
                popup_3d3717844fd9c359c8b6fc5e71c85ea7.setContent(html_cdaee9fed4fd232af1e995bc4f8186d5);
            
        

        marker_a358157af3606140e658158afe616c4e.bindPopup(popup_3d3717844fd9c359c8b6fc5e71c85ea7)
        ;

        
    
    
            var marker_3ca2db51468cd39715714ef9d8799c0e = L.marker(
                [45.5394707, -122.7977247],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d35013a167fb87eb1d15e2c8d6e5f6c5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3ca2db51468cd39715714ef9d8799c0e.setIcon(icon_d35013a167fb87eb1d15e2c8d6e5f6c5);
        
    
        var popup_8f348861a0a41f56d65a33f0bca2f6b5 = L.popup({"maxWidth": "100%"});

        
            
                var html_53da538acb044915a9a8322d4a2474b2 = $(`<div id="html_53da538acb044915a9a8322d4a2474b2" style="width: 100.0%; height: 100.0%;">Bonny Slope Elementary School</div>`)[0];
                popup_8f348861a0a41f56d65a33f0bca2f6b5.setContent(html_53da538acb044915a9a8322d4a2474b2);
            
        

        marker_3ca2db51468cd39715714ef9d8799c0e.bindPopup(popup_8f348861a0a41f56d65a33f0bca2f6b5)
        ;

        
    
    
            var marker_f2c3432ae0bb996512dea580a66d9fb2 = L.marker(
                [45.526914, -122.7827052],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_008c7d3739401c298d61c3573d48d957 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f2c3432ae0bb996512dea580a66d9fb2.setIcon(icon_008c7d3739401c298d61c3573d48d957);
        
    
        var popup_7e22de9f148cb4398124b1cec4c374c1 = L.popup({"maxWidth": "100%"});

        
            
                var html_a7cfe05530959f0eace67c75e2d645a1 = $(`<div id="html_a7cfe05530959f0eace67c75e2d645a1" style="width: 100.0%; height: 100.0%;">Cedar Mill Elementary School</div>`)[0];
                popup_7e22de9f148cb4398124b1cec4c374c1.setContent(html_a7cfe05530959f0eace67c75e2d645a1);
            
        

        marker_f2c3432ae0bb996512dea580a66d9fb2.bindPopup(popup_7e22de9f148cb4398124b1cec4c374c1)
        ;

        
    
    
            var marker_6f17e81cb06fa4855c525b895ece7f0b = L.marker(
                [45.47593329, -122.8370645],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7f24fb3dbca44ede83ea71b8f7c17aa4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6f17e81cb06fa4855c525b895ece7f0b.setIcon(icon_7f24fb3dbca44ede83ea71b8f7c17aa4);
        
    
        var popup_b50aae712157d66dcb4802d59851997a = L.popup({"maxWidth": "100%"});

        
            
                var html_48e8f7b46920d172ffe6257d38b8243f = $(`<div id="html_48e8f7b46920d172ffe6257d38b8243f" style="width: 100.0%; height: 100.0%;">Chehalem Elementary School</div>`)[0];
                popup_b50aae712157d66dcb4802d59851997a.setContent(html_48e8f7b46920d172ffe6257d38b8243f);
            
        

        marker_6f17e81cb06fa4855c525b895ece7f0b.bindPopup(popup_b50aae712157d66dcb4802d59851997a)
        ;

        
    
    
            var marker_63f1f2a46c9fbddcea9ae9ac9d24ab77 = L.marker(
                [45.46454222, -122.8507345],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_21ada06bdc27651c2e1661446a506d2d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_63f1f2a46c9fbddcea9ae9ac9d24ab77.setIcon(icon_21ada06bdc27651c2e1661446a506d2d);
        
    
        var popup_7ee1257a79b1cf2b0be7d5cce581d78c = L.popup({"maxWidth": "100%"});

        
            
                var html_5d863ebc44f42a79ae3dcaf9ec5bd436 = $(`<div id="html_5d863ebc44f42a79ae3dcaf9ec5bd436" style="width: 100.0%; height: 100.0%;">Cooper Mountain Elementary School</div>`)[0];
                popup_7ee1257a79b1cf2b0be7d5cce581d78c.setContent(html_5d863ebc44f42a79ae3dcaf9ec5bd436);
            
        

        marker_63f1f2a46c9fbddcea9ae9ac9d24ab77.bindPopup(popup_7ee1257a79b1cf2b0be7d5cce581d78c)
        ;

        
    
    
            var marker_c555fe602990cb7cce60a91a930cdd88 = L.marker(
                [45.5156764, -122.8515109],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_56afd66844224595e83e1dd009bfb5dd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c555fe602990cb7cce60a91a930cdd88.setIcon(icon_56afd66844224595e83e1dd009bfb5dd);
        
    
        var popup_a720bf270a21a89a86e24c5e87ddc740 = L.popup({"maxWidth": "100%"});

        
            
                var html_34706e5d91a505e4a107da22c2d997a6 = $(`<div id="html_34706e5d91a505e4a107da22c2d997a6" style="width: 100.0%; height: 100.0%;">Elmonica Elementary School</div>`)[0];
                popup_a720bf270a21a89a86e24c5e87ddc740.setContent(html_34706e5d91a505e4a107da22c2d997a6);
            
        

        marker_c555fe602990cb7cce60a91a930cdd88.bindPopup(popup_a720bf270a21a89a86e24c5e87ddc740)
        ;

        
    
    
            var marker_86f9181cc4384fc26d3e5453a98d8c4d = L.marker(
                [45.46627183, -122.8631889],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_32ca92c2c3584ebcd7b6db04ab3ed819 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_86f9181cc4384fc26d3e5453a98d8c4d.setIcon(icon_32ca92c2c3584ebcd7b6db04ab3ed819);
        
    
        var popup_45c82df334f6834a81edc5631d91f03f = L.popup({"maxWidth": "100%"});

        
            
                var html_9d0a0880da86c89c1640de1c106dd2f2 = $(`<div id="html_9d0a0880da86c89c1640de1c106dd2f2" style="width: 100.0%; height: 100.0%;">Errol Hassell Elementary School</div>`)[0];
                popup_45c82df334f6834a81edc5631d91f03f.setContent(html_9d0a0880da86c89c1640de1c106dd2f2);
            
        

        marker_86f9181cc4384fc26d3e5453a98d8c4d.bindPopup(popup_45c82df334f6834a81edc5631d91f03f)
        ;

        
    
    
            var marker_d59786a851e4a9cbe6f9b908a2dcb46a = L.marker(
                [45.54979685, -122.8115159],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_becfc60fad1a81280682bb0041e692de = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d59786a851e4a9cbe6f9b908a2dcb46a.setIcon(icon_becfc60fad1a81280682bb0041e692de);
        
    
        var popup_ed121c0f4b105b93234ff441f0accd05 = L.popup({"maxWidth": "100%"});

        
            
                var html_07f78d109ba50c81b704e0c0fe781d87 = $(`<div id="html_07f78d109ba50c81b704e0c0fe781d87" style="width: 100.0%; height: 100.0%;">Findley Elementary</div>`)[0];
                popup_ed121c0f4b105b93234ff441f0accd05.setContent(html_07f78d109ba50c81b704e0c0fe781d87);
            
        

        marker_d59786a851e4a9cbe6f9b908a2dcb46a.bindPopup(popup_ed121c0f4b105b93234ff441f0accd05)
        ;

        
    
    
            var marker_3a33dbb59e58a906d8730c1045535fee = L.marker(
                [45.47376717, -122.8181794],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_9f055f2c4fd8ac5b9eecaef85758aafe = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3a33dbb59e58a906d8730c1045535fee.setIcon(icon_9f055f2c4fd8ac5b9eecaef85758aafe);
        
    
        var popup_6ccadc89fb77eddd4468e0bd0ad309dc = L.popup({"maxWidth": "100%"});

        
            
                var html_9c29467ea39ad7bf51bc228378c667e8 = $(`<div id="html_9c29467ea39ad7bf51bc228378c667e8" style="width: 100.0%; height: 100.0%;">Fir Grove Elementary School</div>`)[0];
                popup_6ccadc89fb77eddd4468e0bd0ad309dc.setContent(html_9c29467ea39ad7bf51bc228378c667e8);
            
        

        marker_3a33dbb59e58a906d8730c1045535fee.bindPopup(popup_6ccadc89fb77eddd4468e0bd0ad309dc)
        ;

        
    
    
            var marker_06cc708557971c1dd4c11d2b142023a9 = L.marker(
                [45.52792831, -122.8200251],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3f456c3449ca2ec4db813d4faf68985a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_06cc708557971c1dd4c11d2b142023a9.setIcon(icon_3f456c3449ca2ec4db813d4faf68985a);
        
    
        var popup_76b1a61dd64fb0c70086235a6c29e98f = L.popup({"maxWidth": "100%"});

        
            
                var html_4a9b226c02d6e47e6b76930a8febd1f7 = $(`<div id="html_4a9b226c02d6e47e6b76930a8febd1f7" style="width: 100.0%; height: 100.0%;">FLEX Online School</div>`)[0];
                popup_76b1a61dd64fb0c70086235a6c29e98f.setContent(html_4a9b226c02d6e47e6b76930a8febd1f7);
            
        

        marker_06cc708557971c1dd4c11d2b142023a9.bindPopup(popup_76b1a61dd64fb0c70086235a6c29e98f)
        ;

        
    
    
            var marker_a896cc084c0d863ea72528864dfc1518 = L.marker(
                [45.45368166, -122.8019862],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_94935e87b0b76005378601fed32f673e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a896cc084c0d863ea72528864dfc1518.setIcon(icon_94935e87b0b76005378601fed32f673e);
        
    
        var popup_8af7b3e9114648323acb01655b838319 = L.popup({"maxWidth": "100%"});

        
            
                var html_007f617e4b8fde9ff97d23969a8bc74f = $(`<div id="html_007f617e4b8fde9ff97d23969a8bc74f" style="width: 100.0%; height: 100.0%;">Greenway Elementary School</div>`)[0];
                popup_8af7b3e9114648323acb01655b838319.setContent(html_007f617e4b8fde9ff97d23969a8bc74f);
            
        

        marker_a896cc084c0d863ea72528864dfc1518.bindPopup(popup_8af7b3e9114648323acb01655b838319)
        ;

        
    
    
            var marker_4e910eaf3a06a212076ec4ab571c14e8 = L.marker(
                [45.46928262, -122.8831561],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_441b14ea1d10fd8ee0e59477095ea27d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4e910eaf3a06a212076ec4ab571c14e8.setIcon(icon_441b14ea1d10fd8ee0e59477095ea27d);
        
    
        var popup_c56e15bdf485ab63400b4862b94673cb = L.popup({"maxWidth": "100%"});

        
            
                var html_303dd14d340eb291265337e895812185 = $(`<div id="html_303dd14d340eb291265337e895812185" style="width: 100.0%; height: 100.0%;">Hazeldale Elementary School</div>`)[0];
                popup_c56e15bdf485ab63400b4862b94673cb.setContent(html_303dd14d340eb291265337e895812185);
            
        

        marker_4e910eaf3a06a212076ec4ab571c14e8.bindPopup(popup_c56e15bdf485ab63400b4862b94673cb)
        ;

        
    
    
            var marker_4f27e1af7e7bca4d0a0b293242bcfd4b = L.marker(
                [45.45398377, -122.8192953],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_4a75269d209d160c4c0f2b7521177d13 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4f27e1af7e7bca4d0a0b293242bcfd4b.setIcon(icon_4a75269d209d160c4c0f2b7521177d13);
        
    
        var popup_0519e9fb0858ac45f39b544ff1dd6d07 = L.popup({"maxWidth": "100%"});

        
            
                var html_f702c9c5c7516f42c46e0c251d8698dd = $(`<div id="html_f702c9c5c7516f42c46e0c251d8698dd" style="width: 100.0%; height: 100.0%;">Hiteon Elementary School</div>`)[0];
                popup_0519e9fb0858ac45f39b544ff1dd6d07.setContent(html_f702c9c5c7516f42c46e0c251d8698dd);
            
        

        marker_4f27e1af7e7bca4d0a0b293242bcfd4b.bindPopup(popup_0519e9fb0858ac45f39b544ff1dd6d07)
        ;

        
    
    
            var marker_c2d209e217e9aa93b0c32569b982d11e = L.marker(
                [45.4946171, -122.7839049],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_9205b12cf1244bfa8f72e3b75aef2611 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c2d209e217e9aa93b0c32569b982d11e.setIcon(icon_9205b12cf1244bfa8f72e3b75aef2611);
        
    
        var popup_b6b4d110fdef762fe20c6848bedd6acb = L.popup({"maxWidth": "100%"});

        
            
                var html_b215e49cb8d35ff79b45e64253082671 = $(`<div id="html_b215e49cb8d35ff79b45e64253082671" style="width: 100.0%; height: 100.0%;">Hope Chinese Charter School</div>`)[0];
                popup_b6b4d110fdef762fe20c6848bedd6acb.setContent(html_b215e49cb8d35ff79b45e64253082671);
            
        

        marker_c2d209e217e9aa93b0c32569b982d11e.bindPopup(popup_b6b4d110fdef762fe20c6848bedd6acb)
        ;

        
    
    
            var marker_e83bb8cd24ed60aee6d9a3260a33871b = L.marker(
                [45.56032035, -122.823217],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a577ddbec98fc12cc3d6e60760ee3e2f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_e83bb8cd24ed60aee6d9a3260a33871b.setIcon(icon_a577ddbec98fc12cc3d6e60760ee3e2f);
        
    
        var popup_8c196d29666fa8234d62b3fb7fa6e07a = L.popup({"maxWidth": "100%"});

        
            
                var html_a71467d8e96d1146549f33472d6da16f = $(`<div id="html_a71467d8e96d1146549f33472d6da16f" style="width: 100.0%; height: 100.0%;">Jacob Wismer Elementary School</div>`)[0];
                popup_8c196d29666fa8234d62b3fb7fa6e07a.setContent(html_a71467d8e96d1146549f33472d6da16f);
            
        

        marker_e83bb8cd24ed60aee6d9a3260a33871b.bindPopup(popup_8c196d29666fa8234d62b3fb7fa6e07a)
        ;

        
    
    
            var marker_a45190b186df1f583ca91cd3e40ef8fd = L.marker(
                [45.48953844, -122.8762955],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3ca01493711e933525959cea37ae13d2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a45190b186df1f583ca91cd3e40ef8fd.setIcon(icon_3ca01493711e933525959cea37ae13d2);
        
    
        var popup_801f4278a7bf6ae4fc20e967a9b81f26 = L.popup({"maxWidth": "100%"});

        
            
                var html_7ca88c61b04ca9b2078ae024cfea95d8 = $(`<div id="html_7ca88c61b04ca9b2078ae024cfea95d8" style="width: 100.0%; height: 100.0%;">Kinnaman Elementary School</div>`)[0];
                popup_801f4278a7bf6ae4fc20e967a9b81f26.setContent(html_7ca88c61b04ca9b2078ae024cfea95d8);
            
        

        marker_a45190b186df1f583ca91cd3e40ef8fd.bindPopup(popup_801f4278a7bf6ae4fc20e967a9b81f26)
        ;

        
    
    
            var marker_afe85604a196b60dc21da2e7f17ce552 = L.marker(
                [45.4653472, -122.7787676],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_615e341b578f9d79c153ba340747e041 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_afe85604a196b60dc21da2e7f17ce552.setIcon(icon_615e341b578f9d79c153ba340747e041);
        
    
        var popup_03f24184216319eaae43abd6c2f49a4b = L.popup({"maxWidth": "100%"});

        
            
                var html_c00778cd36665ea2df9cac1ee3aed771 = $(`<div id="html_c00778cd36665ea2df9cac1ee3aed771" style="width: 100.0%; height: 100.0%;">McKay Elementary School</div>`)[0];
                popup_03f24184216319eaae43abd6c2f49a4b.setContent(html_c00778cd36665ea2df9cac1ee3aed771);
            
        

        marker_afe85604a196b60dc21da2e7f17ce552.bindPopup(popup_03f24184216319eaae43abd6c2f49a4b)
        ;

        
    
    
            var marker_0ade5511b1175343dd0059d1ff224e6b = L.marker(
                [45.53021514, -122.8666829],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d7cabbf44849028cf67edb57b215bdd7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0ade5511b1175343dd0059d1ff224e6b.setIcon(icon_d7cabbf44849028cf67edb57b215bdd7);
        
    
        var popup_4b3e3ae08bb2e74feeb852085e36825b = L.popup({"maxWidth": "100%"});

        
            
                var html_02d3db711710b0d95ca7d5b594981601 = $(`<div id="html_02d3db711710b0d95ca7d5b594981601" style="width: 100.0%; height: 100.0%;">McKinley Elementary School</div>`)[0];
                popup_4b3e3ae08bb2e74feeb852085e36825b.setContent(html_02d3db711710b0d95ca7d5b594981601);
            
        

        marker_0ade5511b1175343dd0059d1ff224e6b.bindPopup(popup_4b3e3ae08bb2e74feeb852085e36825b)
        ;

        
    
    
            var marker_ac22e866bd30064d27300def23509deb = L.marker(
                [45.47609252, -122.7520114],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_118d20fbf589bef87a0b56ff5c75e7d1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ac22e866bd30064d27300def23509deb.setIcon(icon_118d20fbf589bef87a0b56ff5c75e7d1);
        
    
        var popup_cc98a3710c8960271d0a41a1fafb09fa = L.popup({"maxWidth": "100%"});

        
            
                var html_4ce91a9d575a2e6c32ed2593c3ade79c = $(`<div id="html_4ce91a9d575a2e6c32ed2593c3ade79c" style="width: 100.0%; height: 100.0%;">Montclair Elementary School</div>`)[0];
                popup_cc98a3710c8960271d0a41a1fafb09fa.setContent(html_4ce91a9d575a2e6c32ed2593c3ade79c);
            
        

        marker_ac22e866bd30064d27300def23509deb.bindPopup(popup_cc98a3710c8960271d0a41a1fafb09fa)
        ;

        
    
    
            var marker_f039f5dfe39945716a3533b36baf36dc = L.marker(
                [45.44515491, -122.8433931],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_88887c21d6eca66172ec9908adecd956 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f039f5dfe39945716a3533b36baf36dc.setIcon(icon_88887c21d6eca66172ec9908adecd956);
        
    
        var popup_fb361e48624268c7b64d00f77422c38e = L.popup({"maxWidth": "100%"});

        
            
                var html_50c4abfbf8202bb6622d1feca841574c = $(`<div id="html_50c4abfbf8202bb6622d1feca841574c" style="width: 100.0%; height: 100.0%;">Nancy Ryles Elementary School</div>`)[0];
                popup_fb361e48624268c7b64d00f77422c38e.setContent(html_50c4abfbf8202bb6622d1feca841574c);
            
        

        marker_f039f5dfe39945716a3533b36baf36dc.bindPopup(popup_fb361e48624268c7b64d00f77422c38e)
        ;

        
    
    
            var marker_1a2839e33c182f7af1ab9ca03a22650c = L.marker(
                [45.5388029, -122.8359346],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e8e0d98287415762adeef6466d5fd171 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1a2839e33c182f7af1ab9ca03a22650c.setIcon(icon_e8e0d98287415762adeef6466d5fd171);
        
    
        var popup_1bb525b3923eec7ed27787cef52c4da6 = L.popup({"maxWidth": "100%"});

        
            
                var html_02b957c2b7c2dd8f284786339a4fe850 = $(`<div id="html_02b957c2b7c2dd8f284786339a4fe850" style="width: 100.0%; height: 100.0%;">Oak Hills Elementary School</div>`)[0];
                popup_1bb525b3923eec7ed27787cef52c4da6.setContent(html_02b957c2b7c2dd8f284786339a4fe850);
            
        

        marker_1a2839e33c182f7af1ab9ca03a22650c.bindPopup(popup_1bb525b3923eec7ed27787cef52c4da6)
        ;

        
    
    
            var marker_46ed7081b0e7bbf328ab2f7979bf7c72 = L.marker(
                [45.48239756, -122.7583927],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f841de645998a8ee4be374905727b27e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_46ed7081b0e7bbf328ab2f7979bf7c72.setIcon(icon_f841de645998a8ee4be374905727b27e);
        
    
        var popup_020f40891776b8b4b016f5097f081053 = L.popup({"maxWidth": "100%"});

        
            
                var html_ba577faab45f88e242cb1ea19e7f4605 = $(`<div id="html_ba577faab45f88e242cb1ea19e7f4605" style="width: 100.0%; height: 100.0%;">Raleigh Hills Elementary School</div>`)[0];
                popup_020f40891776b8b4b016f5097f081053.setContent(html_ba577faab45f88e242cb1ea19e7f4605);
            
        

        marker_46ed7081b0e7bbf328ab2f7979bf7c72.bindPopup(popup_020f40891776b8b4b016f5097f081053)
        ;

        
    
    
            var marker_6898ff0ecf88731d2f8458d82fe6fb96 = L.marker(
                [45.4934383, -122.7563734],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_2a02ac1e73e5794268c09ec7c4e9d195 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6898ff0ecf88731d2f8458d82fe6fb96.setIcon(icon_2a02ac1e73e5794268c09ec7c4e9d195);
        
    
        var popup_f46b0420a59d09a94f23b21418378655 = L.popup({"maxWidth": "100%"});

        
            
                var html_807b07eae3eedb815f7ad05c14bb2cd4 = $(`<div id="html_807b07eae3eedb815f7ad05c14bb2cd4" style="width: 100.0%; height: 100.0%;">Raleigh Park Elementary School</div>`)[0];
                popup_f46b0420a59d09a94f23b21418378655.setContent(html_807b07eae3eedb815f7ad05c14bb2cd4);
            
        

        marker_6898ff0ecf88731d2f8458d82fe6fb96.bindPopup(popup_f46b0420a59d09a94f23b21418378655)
        ;

        
    
    
            var marker_fd5cb8bf55692b71fd9013e24e937f81 = L.marker(
                [45.50227943, -122.7805992],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0d4b78b900046c59d460d73a7cba2c28 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fd5cb8bf55692b71fd9013e24e937f81.setIcon(icon_0d4b78b900046c59d460d73a7cba2c28);
        
    
        var popup_26f68c63d308e9554b905a95ee1c79d7 = L.popup({"maxWidth": "100%"});

        
            
                var html_22d074a713c8a18b6acb1d09898890c3 = $(`<div id="html_22d074a713c8a18b6acb1d09898890c3" style="width: 100.0%; height: 100.0%;">Ridgewood Elementary School</div>`)[0];
                popup_26f68c63d308e9554b905a95ee1c79d7.setContent(html_22d074a713c8a18b6acb1d09898890c3);
            
        

        marker_fd5cb8bf55692b71fd9013e24e937f81.bindPopup(popup_26f68c63d308e9554b905a95ee1c79d7)
        ;

        
    
    
            var marker_797d2ac44cbbae9ddaa98924758f7756 = L.marker(
                [45.54917251, -122.8686367],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d201d945e832e231ae02b4c1960960f1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_797d2ac44cbbae9ddaa98924758f7756.setIcon(icon_d201d945e832e231ae02b4c1960960f1);
        
    
        var popup_448ff4d1097f1bc24b2add9c37dd7a9c = L.popup({"maxWidth": "100%"});

        
            
                var html_c83a3d887414929ed555a26b45e6d7af = $(`<div id="html_c83a3d887414929ed555a26b45e6d7af" style="width: 100.0%; height: 100.0%;">Rock Creek Elementary School</div>`)[0];
                popup_448ff4d1097f1bc24b2add9c37dd7a9c.setContent(html_c83a3d887414929ed555a26b45e6d7af);
            
        

        marker_797d2ac44cbbae9ddaa98924758f7756.bindPopup(popup_448ff4d1097f1bc24b2add9c37dd7a9c)
        ;

        
    
    
            var marker_bacd460ab04c831f05a34a9f45de96df = L.marker(
                [45.57554175, -122.8377548],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f7328b4c2c6857413da615d0289d15e3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_bacd460ab04c831f05a34a9f45de96df.setIcon(icon_f7328b4c2c6857413da615d0289d15e3);
        
    
        var popup_ceb1b2aadcf5d42ebd2e42aca81e12d3 = L.popup({"maxWidth": "100%"});

        
            
                var html_e7bdda1a179a7875cf656307d03cc28c = $(`<div id="html_e7bdda1a179a7875cf656307d03cc28c" style="width: 100.0%; height: 100.0%;">Sato Elementary School</div>`)[0];
                popup_ceb1b2aadcf5d42ebd2e42aca81e12d3.setContent(html_e7bdda1a179a7875cf656307d03cc28c);
            
        

        marker_bacd460ab04c831f05a34a9f45de96df.bindPopup(popup_ceb1b2aadcf5d42ebd2e42aca81e12d3)
        ;

        
    
    
            var marker_f10abb310611669708e4321bbe0ca42b = L.marker(
                [45.43072386, -122.8451255],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_dd88b84b5602cf00f029b4f234656203 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f10abb310611669708e4321bbe0ca42b.setIcon(icon_dd88b84b5602cf00f029b4f234656203);
        
    
        var popup_5e5926deac376ddded19449d1d02a81a = L.popup({"maxWidth": "100%"});

        
            
                var html_83393057159d99c7b21a6be7b17dfc3c = $(`<div id="html_83393057159d99c7b21a6be7b17dfc3c" style="width: 100.0%; height: 100.0%;">Scholls Heights Elementary School</div>`)[0];
                popup_5e5926deac376ddded19449d1d02a81a.setContent(html_83393057159d99c7b21a6be7b17dfc3c);
            
        

        marker_f10abb310611669708e4321bbe0ca42b.bindPopup(popup_5e5926deac376ddded19449d1d02a81a)
        ;

        
    
    
            var marker_87d49c28d1901b7e1209449da56ce18c = L.marker(
                [45.45929229, -122.8375432],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8580c22aebfc2a843b04c7c1117119ab = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_87d49c28d1901b7e1209449da56ce18c.setIcon(icon_8580c22aebfc2a843b04c7c1117119ab);
        
    
        var popup_2b31da7be3a11e4b9b73d1a421fb4601 = L.popup({"maxWidth": "100%"});

        
            
                var html_1c90aae3b9a34dbe77b9a16702e7b60c = $(`<div id="html_1c90aae3b9a34dbe77b9a16702e7b60c" style="width: 100.0%; height: 100.0%;">Sexton Mountain Elementary School</div>`)[0];
                popup_2b31da7be3a11e4b9b73d1a421fb4601.setContent(html_1c90aae3b9a34dbe77b9a16702e7b60c);
            
        

        marker_87d49c28d1901b7e1209449da56ce18c.bindPopup(popup_2b31da7be3a11e4b9b73d1a421fb4601)
        ;

        
    
    
            var marker_43db5548adb1ddf60d895965036c7ae5 = L.marker(
                [45.56867703, -122.8506701],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c31a03a1a97fe2614bf1da4eb2ce15ca = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_43db5548adb1ddf60d895965036c7ae5.setIcon(icon_c31a03a1a97fe2614bf1da4eb2ce15ca);
        
    
        var popup_82b1329e62355b3f3d589f9e682db686 = L.popup({"maxWidth": "100%"});

        
            
                var html_977470f7f12342643c36a492fe3f9575 = $(`<div id="html_977470f7f12342643c36a492fe3f9575" style="width: 100.0%; height: 100.0%;">Springville K-8 School</div>`)[0];
                popup_82b1329e62355b3f3d589f9e682db686.setContent(html_977470f7f12342643c36a492fe3f9575);
            
        

        marker_43db5548adb1ddf60d895965036c7ae5.bindPopup(popup_82b1329e62355b3f3d589f9e682db686)
        ;

        
    
    
            var marker_dda1adc6a4f948d88f20bdbe72a6d308 = L.marker(
                [45.53322141, -122.8203243],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_fb2c6639b8adbc9abc1748961efd81f9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dda1adc6a4f948d88f20bdbe72a6d308.setIcon(icon_fb2c6639b8adbc9abc1748961efd81f9);
        
    
        var popup_37c9a565e6b5c5ec84f916d90373e784 = L.popup({"maxWidth": "100%"});

        
            
                var html_07b563391367b446621564826e495d59 = $(`<div id="html_07b563391367b446621564826e495d59" style="width: 100.0%; height: 100.0%;">Terra Linda Elementary School</div>`)[0];
                popup_37c9a565e6b5c5ec84f916d90373e784.setContent(html_07b563391367b446621564826e495d59);
            
        

        marker_dda1adc6a4f948d88f20bdbe72a6d308.bindPopup(popup_37c9a565e6b5c5ec84f916d90373e784)
        ;

        
    
    
            var marker_ef399cfaaad684236670863dd177e1a4 = L.marker(
                [45.46866004, -122.7938018],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_42c379f5a3f09533230dc452d350bd0e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ef399cfaaad684236670863dd177e1a4.setIcon(icon_42c379f5a3f09533230dc452d350bd0e);
        
    
        var popup_6c72fdeaa3f1c4a01556d8e446213d3a = L.popup({"maxWidth": "100%"});

        
            
                var html_8560d3aa0cc280d0f68927dd4f7153fe = $(`<div id="html_8560d3aa0cc280d0f68927dd4f7153fe" style="width: 100.0%; height: 100.0%;">Vose Elementary School</div>`)[0];
                popup_6c72fdeaa3f1c4a01556d8e446213d3a.setContent(html_8560d3aa0cc280d0f68927dd4f7153fe);
            
        

        marker_ef399cfaaad684236670863dd177e1a4.bindPopup(popup_6c72fdeaa3f1c4a01556d8e446213d3a)
        ;

        
    
    
            var marker_e79ba20d5ef2a20c059a5769eb4e2c40 = L.marker(
                [45.51528476, -122.7667617],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_725729d18b0471886b242b71103093ec = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_e79ba20d5ef2a20c059a5769eb4e2c40.setIcon(icon_725729d18b0471886b242b71103093ec);
        
    
        var popup_7670f5a17c404170edf296f3fe60aac4 = L.popup({"maxWidth": "100%"});

        
            
                var html_f30470c46bf2c5758640a87d748f3fbc = $(`<div id="html_f30470c46bf2c5758640a87d748f3fbc" style="width: 100.0%; height: 100.0%;">West Tualatin View Elementary School</div>`)[0];
                popup_7670f5a17c404170edf296f3fe60aac4.setContent(html_f30470c46bf2c5758640a87d748f3fbc);
            
        

        marker_e79ba20d5ef2a20c059a5769eb4e2c40.bindPopup(popup_7670f5a17c404170edf296f3fe60aac4)
        ;

        
    
    
            var marker_de4d8ad9516c627713cc0611d34cef6c = L.marker(
                [45.50193741, -122.7998969],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_6b6ce283dba2293a88ecf4c8a81a2dd7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_de4d8ad9516c627713cc0611d34cef6c.setIcon(icon_6b6ce283dba2293a88ecf4c8a81a2dd7);
        
    
        var popup_7aac476a7e7fcbf3921b900f08be4326 = L.popup({"maxWidth": "100%"});

        
            
                var html_c309642a7e0600770783a991bb4563c4 = $(`<div id="html_c309642a7e0600770783a991bb4563c4" style="width: 100.0%; height: 100.0%;">William Walker Elementary School</div>`)[0];
                popup_7aac476a7e7fcbf3921b900f08be4326.setContent(html_c309642a7e0600770783a991bb4563c4);
            
        

        marker_de4d8ad9516c627713cc0611d34cef6c.bindPopup(popup_7aac476a7e7fcbf3921b900f08be4326)
        ;

        
    
    
            var marker_b03987308bc05846ec754aa74a04fc25 = L.marker(
                [45.47283332, -122.4586911],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e067e24011e7f5addb80add56bde5b70 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b03987308bc05846ec754aa74a04fc25.setIcon(icon_e067e24011e7f5addb80add56bde5b70);
        
    
        var popup_91585a7f235e2db35cb897991d6bc68e = L.popup({"maxWidth": "100%"});

        
            
                var html_4673dfe50cb13e28f67866a7ab239e90 = $(`<div id="html_4673dfe50cb13e28f67866a7ab239e90" style="width: 100.0%; height: 100.0%;">Butler Creek Elementary School</div>`)[0];
                popup_91585a7f235e2db35cb897991d6bc68e.setContent(html_4673dfe50cb13e28f67866a7ab239e90);
            
        

        marker_b03987308bc05846ec754aa74a04fc25.bindPopup(popup_91585a7f235e2db35cb897991d6bc68e)
        ;

        
    
    
            var marker_79dc01c887aa276c7c002e433a905894 = L.marker(
                [45.50150489, -122.4775487],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0ae577afa14a0d7dc8df21d11a43c0ec = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_79dc01c887aa276c7c002e433a905894.setIcon(icon_0ae577afa14a0d7dc8df21d11a43c0ec);
        
    
        var popup_0d144a309c9002aaaf54b2adb7f85f45 = L.popup({"maxWidth": "100%"});

        
            
                var html_74a4f838b02f4c62e3833216c7200bf5 = $(`<div id="html_74a4f838b02f4c62e3833216c7200bf5" style="width: 100.0%; height: 100.0%;">Meadows Elementary</div>`)[0];
                popup_0d144a309c9002aaaf54b2adb7f85f45.setContent(html_74a4f838b02f4c62e3833216c7200bf5);
            
        

        marker_79dc01c887aa276c7c002e433a905894.bindPopup(popup_0d144a309c9002aaaf54b2adb7f85f45)
        ;

        
    
    
            var marker_dea8bbe904badfb75180ca76c95ab56d = L.marker(
                [45.51437735, -122.5002849],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_09009d821e037de937c2614b88872e9b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dea8bbe904badfb75180ca76c95ab56d.setIcon(icon_09009d821e037de937c2614b88872e9b);
        
    
        var popup_e562ce0c66c951dc6d05daa386663d86 = L.popup({"maxWidth": "100%"});

        
            
                var html_f3ef0bcd3c12ac6a54c18578d0e848e3 = $(`<div id="html_f3ef0bcd3c12ac6a54c18578d0e848e3" style="width: 100.0%; height: 100.0%;">Parklane Elementary School</div>`)[0];
                popup_e562ce0c66c951dc6d05daa386663d86.setContent(html_f3ef0bcd3c12ac6a54c18578d0e848e3);
            
        

        marker_dea8bbe904badfb75180ca76c95ab56d.bindPopup(popup_e562ce0c66c951dc6d05daa386663d86)
        ;

        
    
    
            var marker_09dc8da8590afb23412071aefb910531 = L.marker(
                [45.51150697, -122.4883045],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_648c4a2d0e9af33a489917c34e756127 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_09dc8da8590afb23412071aefb910531.setIcon(icon_648c4a2d0e9af33a489917c34e756127);
        
    
        var popup_217589e8f56efe014e9fd8d8651a5f79 = L.popup({"maxWidth": "100%"});

        
            
                var html_e7f72af6c26e3ed10d611e38efa847b8 = $(`<div id="html_e7f72af6c26e3ed10d611e38efa847b8" style="width: 100.0%; height: 100.0%;">Patrick Lynch Elementary</div>`)[0];
                popup_217589e8f56efe014e9fd8d8651a5f79.setContent(html_e7f72af6c26e3ed10d611e38efa847b8);
            
        

        marker_09dc8da8590afb23412071aefb910531.bindPopup(popup_217589e8f56efe014e9fd8d8651a5f79)
        ;

        
    
    
            var marker_b8e9430239041a218f0945a803844ba0 = L.marker(
                [45.4645211, -122.4802123],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7c85feb26ead5efefaeb27e552a97daa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b8e9430239041a218f0945a803844ba0.setIcon(icon_7c85feb26ead5efefaeb27e552a97daa);
        
    
        var popup_abbcd2acf62b45640ed985b54e2c8e98 = L.popup({"maxWidth": "100%"});

        
            
                var html_386e8ca1e6329528cf5044633bb39b7b = $(`<div id="html_386e8ca1e6329528cf5044633bb39b7b" style="width: 100.0%; height: 100.0%;">Pleasant Valley Elementary School</div>`)[0];
                popup_abbcd2acf62b45640ed985b54e2c8e98.setContent(html_386e8ca1e6329528cf5044633bb39b7b);
            
        

        marker_b8e9430239041a218f0945a803844ba0.bindPopup(popup_abbcd2acf62b45640ed985b54e2c8e98)
        ;

        
    
    
            var marker_1f943ed17e2d0a0f688df6512d29916c = L.marker(
                [45.49665898, -122.4855879],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c8deaf9faf7d7050cb07407a0dd52903 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1f943ed17e2d0a0f688df6512d29916c.setIcon(icon_c8deaf9faf7d7050cb07407a0dd52903);
        
    
        var popup_c102643d714e9c91754bc8b3adabcc8a = L.popup({"maxWidth": "100%"});

        
            
                var html_8c3d3f4ab550cb4c448157f54e85cacd = $(`<div id="html_8c3d3f4ab550cb4c448157f54e85cacd" style="width: 100.0%; height: 100.0%;">Powell Butte Elementary School</div>`)[0];
                popup_c102643d714e9c91754bc8b3adabcc8a.setContent(html_8c3d3f4ab550cb4c448157f54e85cacd);
            
        

        marker_1f943ed17e2d0a0f688df6512d29916c.bindPopup(popup_c102643d714e9c91754bc8b3adabcc8a)
        ;

        
    
    
            var marker_758e7fd2c2e935f8c102c14d19492f37 = L.marker(
                [45.50440301, -122.5223106],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0e52adc58f2f47fd6895815280efb39a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_758e7fd2c2e935f8c102c14d19492f37.setIcon(icon_0e52adc58f2f47fd6895815280efb39a);
        
    
        var popup_dcb1f5b83f7d4594451ab92c28df6031 = L.popup({"maxWidth": "100%"});

        
            
                var html_4d020309396e325e3eedd29066d609cd = $(`<div id="html_4d020309396e325e3eedd29066d609cd" style="width: 100.0%; height: 100.0%;">Arthur Academy</div>`)[0];
                popup_dcb1f5b83f7d4594451ab92c28df6031.setContent(html_4d020309396e325e3eedd29066d609cd);
            
        

        marker_758e7fd2c2e935f8c102c14d19492f37.bindPopup(popup_dcb1f5b83f7d4594451ab92c28df6031)
        ;

        
    
    
            var marker_a4f82927f91f838fd50b2ccb2b3ed430 = L.marker(
                [45.50859687, -122.5557244],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_01b90ac3524ab97de060ce1d7e82ace2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a4f82927f91f838fd50b2ccb2b3ed430.setIcon(icon_01b90ac3524ab97de060ce1d7e82ace2);
        
    
        var popup_8cac4008295f6a09a3b641fda5e5365c = L.popup({"maxWidth": "100%"});

        
            
                var html_0b545772a32131dd677a099d5348f6dc = $(`<div id="html_0b545772a32131dd677a099d5348f6dc" style="width: 100.0%; height: 100.0%;">Cherry Park Elementary School</div>`)[0];
                popup_8cac4008295f6a09a3b641fda5e5365c.setContent(html_0b545772a32131dd677a099d5348f6dc);
            
        

        marker_a4f82927f91f838fd50b2ccb2b3ed430.bindPopup(popup_8cac4008295f6a09a3b641fda5e5365c)
        ;

        
    
    
            var marker_5c15e5202d7e8291bc5f5c8275abdae9 = L.marker(
                [45.49423236, -122.5514212],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_50f92fd082f96dc0505e31e63a6b1643 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5c15e5202d7e8291bc5f5c8275abdae9.setIcon(icon_50f92fd082f96dc0505e31e63a6b1643);
        
    
        var popup_ac0ab903dec4794feae58412fca2a067 = L.popup({"maxWidth": "100%"});

        
            
                var html_6edd8d3aecccdbb79708f65ddaed7c1b = $(`<div id="html_6edd8d3aecccdbb79708f65ddaed7c1b" style="width: 100.0%; height: 100.0%;">Earl Boyles Elementary</div>`)[0];
                popup_ac0ab903dec4794feae58412fca2a067.setContent(html_6edd8d3aecccdbb79708f65ddaed7c1b);
            
        

        marker_5c15e5202d7e8291bc5f5c8275abdae9.bindPopup(popup_ac0ab903dec4794feae58412fca2a067)
        ;

        
    
    
            var marker_9b7d1b000b1da0dd94c327098cde56e7 = L.marker(
                [45.49061978, -122.531286],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3e1950f0d665a381d019cce5e0a1faa7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9b7d1b000b1da0dd94c327098cde56e7.setIcon(icon_3e1950f0d665a381d019cce5e0a1faa7);
        
    
        var popup_57b4078542d734a31f0ed6256642bb7a = L.popup({"maxWidth": "100%"});

        
            
                var html_aa1f15d489b87f2b506a98d780db0951 = $(`<div id="html_aa1f15d489b87f2b506a98d780db0951" style="width: 100.0%; height: 100.0%;">Gilbert Heights Elementary School</div>`)[0];
                popup_57b4078542d734a31f0ed6256642bb7a.setContent(html_aa1f15d489b87f2b506a98d780db0951);
            
        

        marker_9b7d1b000b1da0dd94c327098cde56e7.bindPopup(popup_57b4078542d734a31f0ed6256642bb7a)
        ;

        
    
    
            var marker_d5f3adb157d72844347d9987d85bea48 = L.marker(
                [45.47954942, -122.5281407],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_61db17766abb30c3e4b4c1766d5eaa2b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d5f3adb157d72844347d9987d85bea48.setIcon(icon_61db17766abb30c3e4b4c1766d5eaa2b);
        
    
        var popup_65986f1c40a18011caed3b17f7540e44 = L.popup({"maxWidth": "100%"});

        
            
                var html_5f953c6c37827122c521e4b4978da408 = $(`<div id="html_5f953c6c37827122c521e4b4978da408" style="width: 100.0%; height: 100.0%;">Gilbert Park Elementary School</div>`)[0];
                popup_65986f1c40a18011caed3b17f7540e44.setContent(html_5f953c6c37827122c521e4b4978da408);
            
        

        marker_d5f3adb157d72844347d9987d85bea48.bindPopup(popup_65986f1c40a18011caed3b17f7540e44)
        ;

        
    
    
            var marker_fb7cd547bff78349fdbccd4738c63989 = L.marker(
                [45.50837155, -122.5258279],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_cc6a7bef8d48c70ddabd638ba34345fd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fb7cd547bff78349fdbccd4738c63989.setIcon(icon_cc6a7bef8d48c70ddabd638ba34345fd);
        
    
        var popup_c5d208956fcb91c0e8bf28002ea922f4 = L.popup({"maxWidth": "100%"});

        
            
                var html_f1f5f6d7aa51b616ef08d254c15f0639 = $(`<div id="html_f1f5f6d7aa51b616ef08d254c15f0639" style="width: 100.0%; height: 100.0%;">Lincoln Park Elementary School</div>`)[0];
                popup_c5d208956fcb91c0e8bf28002ea922f4.setContent(html_f1f5f6d7aa51b616ef08d254c15f0639);
            
        

        marker_fb7cd547bff78349fdbccd4738c63989.bindPopup(popup_c5d208956fcb91c0e8bf28002ea922f4)
        ;

        
    
    
            var marker_c73c90f2fc17a977482a6485303b821e = L.marker(
                [45.52534382, -122.5302495],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8de9d76683d8c47e9b21ad07f0e9d435 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c73c90f2fc17a977482a6485303b821e.setIcon(icon_8de9d76683d8c47e9b21ad07f0e9d435);
        
    
        var popup_efa2523abed158a5bb315b1f5023bf62 = L.popup({"maxWidth": "100%"});

        
            
                var html_a5d4628d3dd9731a248eff95541bb0f0 = $(`<div id="html_a5d4628d3dd9731a248eff95541bb0f0" style="width: 100.0%; height: 100.0%;">Menlo Park Elementary School</div>`)[0];
                popup_efa2523abed158a5bb315b1f5023bf62.setContent(html_a5d4628d3dd9731a248eff95541bb0f0);
            
        

        marker_c73c90f2fc17a977482a6485303b821e.bindPopup(popup_efa2523abed158a5bb315b1f5023bf62)
        ;

        
    
    
            var marker_29ae62400c7fcb333d7f2462f42879cf = L.marker(
                [45.50980354, -122.5417466],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_6a37a296fd4382e6208fd3638e4d1f35 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_29ae62400c7fcb333d7f2462f42879cf.setIcon(icon_6a37a296fd4382e6208fd3638e4d1f35);
        
    
        var popup_07e86016c884229ad70c55e559b3ee47 = L.popup({"maxWidth": "100%"});

        
            
                var html_f5cd58623f678319aa2291a1c44399d4 = $(`<div id="html_f5cd58623f678319aa2291a1c44399d4" style="width: 100.0%; height: 100.0%;">Mill Park Elementary School</div>`)[0];
                popup_07e86016c884229ad70c55e559b3ee47.setContent(html_f5cd58623f678319aa2291a1c44399d4);
            
        

        marker_29ae62400c7fcb333d7f2462f42879cf.bindPopup(popup_07e86016c884229ad70c55e559b3ee47)
        ;

        
    
    
            var marker_f8a30c63531a7b74932de9ad9d1560b0 = L.marker(
                [45.52123013, -122.543837],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1777b9253eee2f3f5e89cfa3f1e62aef = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f8a30c63531a7b74932de9ad9d1560b0.setIcon(icon_1777b9253eee2f3f5e89cfa3f1e62aef);
        
    
        var popup_7d93835e4af7d90de90ab2317c4c6afd = L.popup({"maxWidth": "100%"});

        
            
                var html_8db8a1f34255aa49c95fa86700cc2126 = $(`<div id="html_8db8a1f34255aa49c95fa86700cc2126" style="width: 100.0%; height: 100.0%;">Ventura Park Elementary School</div>`)[0];
                popup_7d93835e4af7d90de90ab2317c4c6afd.setContent(html_8db8a1f34255aa49c95fa86700cc2126);
            
        

        marker_f8a30c63531a7b74932de9ad9d1560b0.bindPopup(popup_7d93835e4af7d90de90ab2317c4c6afd)
        ;

        
    
    
            var marker_aef3d783254f32b25fbab8d8c16cffd6 = L.marker(
                [45.50081765, -122.5437189],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c09f01c635a4baf67639b7d65d19dc63 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_aef3d783254f32b25fbab8d8c16cffd6.setIcon(icon_c09f01c635a4baf67639b7d65d19dc63);
        
    
        var popup_943674668cf206db55e025bc9ce75d63 = L.popup({"maxWidth": "100%"});

        
            
                var html_3231ea2d2a73cd55766df3b87addfa6e = $(`<div id="html_3231ea2d2a73cd55766df3b87addfa6e" style="width: 100.0%; height: 100.0%;">West Powellhurst Elementary School</div>`)[0];
                popup_943674668cf206db55e025bc9ce75d63.setContent(html_3231ea2d2a73cd55766df3b87addfa6e);
            
        

        marker_aef3d783254f32b25fbab8d8c16cffd6.bindPopup(popup_943674668cf206db55e025bc9ce75d63)
        ;

        
    
    
            var marker_473230acf942d40a92bab6289adbf2a6 = L.marker(
                [45.52180001, -123.0541945],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f556976a665d316b154bacf54e6d2c37 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_473230acf942d40a92bab6289adbf2a6.setIcon(icon_f556976a665d316b154bacf54e6d2c37);
        
    
        var popup_908e2c249e5c3964e3c16affe33a8bc5 = L.popup({"maxWidth": "100%"});

        
            
                var html_a9e003ac5d8d05ef734eaf8dcbb325ea = $(`<div id="html_a9e003ac5d8d05ef734eaf8dcbb325ea" style="width: 100.0%; height: 100.0%;">Cornelius Elementary School</div>`)[0];
                popup_908e2c249e5c3964e3c16affe33a8bc5.setContent(html_a9e003ac5d8d05ef734eaf8dcbb325ea);
            
        

        marker_473230acf942d40a92bab6289adbf2a6.bindPopup(popup_908e2c249e5c3964e3c16affe33a8bc5)
        ;

        
    
    
            var marker_3cd7fec90db51140a8f884f1de308c70 = L.marker(
                [45.49040655, -123.1272844],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b9ba1d36b6ef12160402f7336ffa3d0c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3cd7fec90db51140a8f884f1de308c70.setIcon(icon_b9ba1d36b6ef12160402f7336ffa3d0c);
        
    
        var popup_16c80fe49f89465fdc51a9c548bda3e8 = L.popup({"maxWidth": "100%"});

        
            
                var html_b38965d07fbbfe42f6175b6f026e1f80 = $(`<div id="html_b38965d07fbbfe42f6175b6f026e1f80" style="width: 100.0%; height: 100.0%;">Dilley Elementary School</div>`)[0];
                popup_16c80fe49f89465fdc51a9c548bda3e8.setContent(html_b38965d07fbbfe42f6175b6f026e1f80);
            
        

        marker_3cd7fec90db51140a8f884f1de308c70.bindPopup(popup_16c80fe49f89465fdc51a9c548bda3e8)
        ;

        
    
    
            var marker_c8a749f62a8083c076d7785568485f53 = L.marker(
                [45.51200218, -123.0618842],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_14f4eeb2c09518987f3a5a7e7d2f4497 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c8a749f62a8083c076d7785568485f53.setIcon(icon_14f4eeb2c09518987f3a5a7e7d2f4497);
        
    
        var popup_95c1af7e2067ccff75ea6489bb8b5034 = L.popup({"maxWidth": "100%"});

        
            
                var html_7e4353f0d3412c004d437e6b12a68f38 = $(`<div id="html_7e4353f0d3412c004d437e6b12a68f38" style="width: 100.0%; height: 100.0%;">Echo Shaw Elementary School</div>`)[0];
                popup_95c1af7e2067ccff75ea6489bb8b5034.setContent(html_7e4353f0d3412c004d437e6b12a68f38);
            
        

        marker_c8a749f62a8083c076d7785568485f53.bindPopup(popup_95c1af7e2067ccff75ea6489bb8b5034)
        ;

        
    
    
            var marker_a3f0ad17b7f5fb000f84b1ae457bf0cd = L.marker(
                [45.51453933, -123.0717767],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_bfcfd9e77fb811dceddf08dd4470e68a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a3f0ad17b7f5fb000f84b1ae457bf0cd.setIcon(icon_bfcfd9e77fb811dceddf08dd4470e68a);
        
    
        var popup_f8c064a5e3f756c2bd604a2000407648 = L.popup({"maxWidth": "100%"});

        
            
                var html_67667d5472ce9e3170483cbc923253cb = $(`<div id="html_67667d5472ce9e3170483cbc923253cb" style="width: 100.0%; height: 100.0%;">Fern Hill Elementary School</div>`)[0];
                popup_f8c064a5e3f756c2bd604a2000407648.setContent(html_67667d5472ce9e3170483cbc923253cb);
            
        

        marker_a3f0ad17b7f5fb000f84b1ae457bf0cd.bindPopup(popup_f8c064a5e3f756c2bd604a2000407648)
        ;

        
    
    
            var marker_013d0463533b52ae476106a8ca8ce589 = L.marker(
                [45.51944286, -123.113275],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_608daf397b2ddd1abe82e0223fdd90f4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_013d0463533b52ae476106a8ca8ce589.setIcon(icon_608daf397b2ddd1abe82e0223fdd90f4);
        
    
        var popup_7be2c5ffc93243f204bc8f186a2f2025 = L.popup({"maxWidth": "100%"});

        
            
                var html_1e77f34f15717e3dcd96ce1d04d583a7 = $(`<div id="html_1e77f34f15717e3dcd96ce1d04d583a7" style="width: 100.0%; height: 100.0%;">Forest Grove Community School</div>`)[0];
                popup_7be2c5ffc93243f204bc8f186a2f2025.setContent(html_1e77f34f15717e3dcd96ce1d04d583a7);
            
        

        marker_013d0463533b52ae476106a8ca8ce589.bindPopup(popup_7be2c5ffc93243f204bc8f186a2f2025)
        ;

        
    
    
            var marker_7aea5f168b1a2f853f105182cf1cce7a = L.marker(
                [45.52685989, -123.1161734],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_6a2e246711ad61e32ee0c22ed8191260 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7aea5f168b1a2f853f105182cf1cce7a.setIcon(icon_6a2e246711ad61e32ee0c22ed8191260);
        
    
        var popup_0ed4f641dc6cabf1ab978555ff7026b5 = L.popup({"maxWidth": "100%"});

        
            
                var html_ae145364d0bdf59f0145379409446f92 = $(`<div id="html_ae145364d0bdf59f0145379409446f92" style="width: 100.0%; height: 100.0%;">Harvey Clarke Elementary School</div>`)[0];
                popup_0ed4f641dc6cabf1ab978555ff7026b5.setContent(html_ae145364d0bdf59f0145379409446f92);
            
        

        marker_7aea5f168b1a2f853f105182cf1cce7a.bindPopup(popup_0ed4f641dc6cabf1ab978555ff7026b5)
        ;

        
    
    
            var marker_df930391036da5d4f81a84a0948d1e3f = L.marker(
                [45.51599973, -123.0927512],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_85bf81b29148fc276046c57061c9cf1a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_df930391036da5d4f81a84a0948d1e3f.setIcon(icon_85bf81b29148fc276046c57061c9cf1a);
        
    
        var popup_6d66a6576bd0906d0536da3d96514b19 = L.popup({"maxWidth": "100%"});

        
            
                var html_76e0c98bb8832e3d860908e3bf02e750 = $(`<div id="html_76e0c98bb8832e3d860908e3bf02e750" style="width: 100.0%; height: 100.0%;">Joseph Gale Elementary School</div>`)[0];
                popup_6d66a6576bd0906d0536da3d96514b19.setContent(html_76e0c98bb8832e3d860908e3bf02e750);
            
        

        marker_df930391036da5d4f81a84a0948d1e3f.bindPopup(popup_6d66a6576bd0906d0536da3d96514b19)
        ;

        
    
    
            var marker_85fdc21e764da9cf53e314561f649e21 = L.marker(
                [45.38225343, -122.593185],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0c14f890f7b4185220873f91a54e8b30 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_85fdc21e764da9cf53e314561f649e21.setIcon(icon_0c14f890f7b4185220873f91a54e8b30);
        
    
        var popup_4b13f9a33428db6dd8c9efeb2df06eab = L.popup({"maxWidth": "100%"});

        
            
                var html_db77b466c6576048fc142b5fdbe14f1f = $(`<div id="html_db77b466c6576048fc142b5fdbe14f1f" style="width: 100.0%; height: 100.0%;">John Wetten Elementary School</div>`)[0];
                popup_4b13f9a33428db6dd8c9efeb2df06eab.setContent(html_db77b466c6576048fc142b5fdbe14f1f);
            
        

        marker_85fdc21e764da9cf53e314561f649e21.bindPopup(popup_4b13f9a33428db6dd8c9efeb2df06eab)
        ;

        
    
    
            var marker_fbe3ae65ca8d1d91bfdc5c475928f6cf = L.marker(
                [45.4205957, -122.414377],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c1d387813ff359ed6e8ae5516b683aab = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fbe3ae65ca8d1d91bfdc5c475928f6cf.setIcon(icon_c1d387813ff359ed6e8ae5516b683aab);
        
    
        var popup_c0eb60bd0162e1c0b58a62aa66c7b82c = L.popup({"maxWidth": "100%"});

        
            
                var html_0e11d7fc2732b8b67a57a7db604d5b7c = $(`<div id="html_0e11d7fc2732b8b67a57a7db604d5b7c" style="width: 100.0%; height: 100.0%;">Deep Creek – Damascus K-8 School</div>`)[0];
                popup_c0eb60bd0162e1c0b58a62aa66c7b82c.setContent(html_0e11d7fc2732b8b67a57a7db604d5b7c);
            
        

        marker_fbe3ae65ca8d1d91bfdc5c475928f6cf.bindPopup(popup_c0eb60bd0162e1c0b58a62aa66c7b82c)
        ;

        
    
    
            var marker_ddf8a90f60200096ce46b57f305e2c5d = L.marker(
                [45.49318728, -122.4208695],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_540c95a32639e05490629e1ee5bb86fa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ddf8a90f60200096ce46b57f305e2c5d.setIcon(icon_540c95a32639e05490629e1ee5bb86fa);
        
    
        var popup_f48debdb7bed01f8c82c586554c2694f = L.popup({"maxWidth": "100%"});

        
            
                var html_10f51ee0d67386ed8ad070b7a4f39a88 = $(`<div id="html_10f51ee0d67386ed8ad070b7a4f39a88" style="width: 100.0%; height: 100.0%;">East Gresham Elementary School</div>`)[0];
                popup_f48debdb7bed01f8c82c586554c2694f.setContent(html_10f51ee0d67386ed8ad070b7a4f39a88);
            
        

        marker_ddf8a90f60200096ce46b57f305e2c5d.bindPopup(popup_f48debdb7bed01f8c82c586554c2694f)
        ;

        
    
    
            var marker_d99b47cfcd8868b453466b77ebff0471 = L.marker(
                [45.46855727, -122.3529909],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1e27b4fecfcf5e1bd9de11d655957ca7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d99b47cfcd8868b453466b77ebff0471.setIcon(icon_1e27b4fecfcf5e1bd9de11d655957ca7);
        
    
        var popup_0a21dc31dfebce8c132246fa51f5b718 = L.popup({"maxWidth": "100%"});

        
            
                var html_0f12c24a4ff587071e37c35c5bf44693 = $(`<div id="html_0f12c24a4ff587071e37c35c5bf44693" style="width: 100.0%; height: 100.0%;">East Orient Elementary School</div>`)[0];
                popup_0a21dc31dfebce8c132246fa51f5b718.setContent(html_0f12c24a4ff587071e37c35c5bf44693);
            
        

        marker_d99b47cfcd8868b453466b77ebff0471.bindPopup(popup_0a21dc31dfebce8c132246fa51f5b718)
        ;

        
    
    
            var marker_db8cb01e27e35009c38183fbe3a88cdd = L.marker(
                [45.51070251, -122.4197941],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_77a8834bf89622e80fefe0b417a68e97 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_db8cb01e27e35009c38183fbe3a88cdd.setIcon(icon_77a8834bf89622e80fefe0b417a68e97);
        
    
        var popup_0032d85b38bce69f538727dcca6ec03a = L.popup({"maxWidth": "100%"});

        
            
                var html_12348d84235c9ddefc58e2eeaee490be = $(`<div id="html_12348d84235c9ddefc58e2eeaee490be" style="width: 100.0%; height: 100.0%;">Gresham Arthur Academy</div>`)[0];
                popup_0032d85b38bce69f538727dcca6ec03a.setContent(html_12348d84235c9ddefc58e2eeaee490be);
            
        

        marker_db8cb01e27e35009c38183fbe3a88cdd.bindPopup(popup_0032d85b38bce69f538727dcca6ec03a)
        ;

        
    
    
            var marker_7ec78273326796b4d48fde7106ac6240 = L.marker(
                [45.51457411, -122.4065623],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_58956a8d54f4a0a53234277e60571d57 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7ec78273326796b4d48fde7106ac6240.setIcon(icon_58956a8d54f4a0a53234277e60571d57);
        
    
        var popup_64293624ccb901da5a6a184a71ad72a5 = L.popup({"maxWidth": "100%"});

        
            
                var html_ea0c3bbfd80d9d29a63e3820f22f50e6 = $(`<div id="html_ea0c3bbfd80d9d29a63e3820f22f50e6" style="width: 100.0%; height: 100.0%;">Hall Elementary School</div>`)[0];
                popup_64293624ccb901da5a6a184a71ad72a5.setContent(html_ea0c3bbfd80d9d29a63e3820f22f50e6);
            
        

        marker_7ec78273326796b4d48fde7106ac6240.bindPopup(popup_64293624ccb901da5a6a184a71ad72a5)
        ;

        
    
    
            var marker_da0aef2a0b97b575e613037c5bf6c855 = L.marker(
                [45.51407438, -122.4275729],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_636f03b3dbaed5ce18e090ee46891702 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_da0aef2a0b97b575e613037c5bf6c855.setIcon(icon_636f03b3dbaed5ce18e090ee46891702);
        
    
        var popup_3bdc43bb0370ea3fe58b2e76c427a41d = L.popup({"maxWidth": "100%"});

        
            
                var html_1786f17ed22f6a6a764d0ef8056b2ee5 = $(`<div id="html_1786f17ed22f6a6a764d0ef8056b2ee5" style="width: 100.0%; height: 100.0%;">Highland Elementary School</div>`)[0];
                popup_3bdc43bb0370ea3fe58b2e76c427a41d.setContent(html_1786f17ed22f6a6a764d0ef8056b2ee5);
            
        

        marker_da0aef2a0b97b575e613037c5bf6c855.bindPopup(popup_3bdc43bb0370ea3fe58b2e76c427a41d)
        ;

        
    
    
            var marker_57f855101762e22b20216818e7212b57 = L.marker(
                [45.48472188, -122.407355],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a7ec52391bb495da340b833309e4978b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_57f855101762e22b20216818e7212b57.setIcon(icon_a7ec52391bb495da340b833309e4978b);
        
    
        var popup_e531104f947bc44d4871e7122f52fe34 = L.popup({"maxWidth": "100%"});

        
            
                var html_a6629f6e1df9eed4eafdbbf0c9f76ef2 = $(`<div id="html_a6629f6e1df9eed4eafdbbf0c9f76ef2" style="width: 100.0%; height: 100.0%;">Hogan Cedars Elementary School</div>`)[0];
                popup_e531104f947bc44d4871e7122f52fe34.setContent(html_a6629f6e1df9eed4eafdbbf0c9f76ef2);
            
        

        marker_57f855101762e22b20216818e7212b57.bindPopup(popup_e531104f947bc44d4871e7122f52fe34)
        ;

        
    
    
            var marker_238c898bee1de6afb2ca5ca8e98bceec = L.marker(
                [45.49263973, -122.4547203],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3b7b4226da28a8ad597c07c144e20e7e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_238c898bee1de6afb2ca5ca8e98bceec.setIcon(icon_3b7b4226da28a8ad597c07c144e20e7e);
        
    
        var popup_1fb8c981b8ae38a265370a8c978bc7bc = L.popup({"maxWidth": "100%"});

        
            
                var html_6ebfeba6c82f59904d260721641d2775 = $(`<div id="html_6ebfeba6c82f59904d260721641d2775" style="width: 100.0%; height: 100.0%;">Hollydale Elementary School</div>`)[0];
                popup_1fb8c981b8ae38a265370a8c978bc7bc.setContent(html_6ebfeba6c82f59904d260721641d2775);
            
        

        marker_238c898bee1de6afb2ca5ca8e98bceec.bindPopup(popup_1fb8c981b8ae38a265370a8c978bc7bc)
        ;

        
    
    
            var marker_c53d8eea7d51a0df021c18f865f1d2e2 = L.marker(
                [45.48014285, -122.3848233],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a7e48eded39e35ffcafcbe2b43ce7200 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c53d8eea7d51a0df021c18f865f1d2e2.setIcon(icon_a7e48eded39e35ffcafcbe2b43ce7200);
        
    
        var popup_ee8afb1551f6c93a8aab9cafba573de7 = L.popup({"maxWidth": "100%"});

        
            
                var html_e258a784da50f9e995afed7f3fa3ec8b = $(`<div id="html_e258a784da50f9e995afed7f3fa3ec8b" style="width: 100.0%; height: 100.0%;">Kelly Creek Elementary School</div>`)[0];
                popup_ee8afb1551f6c93a8aab9cafba573de7.setContent(html_e258a784da50f9e995afed7f3fa3ec8b);
            
        

        marker_c53d8eea7d51a0df021c18f865f1d2e2.bindPopup(popup_ee8afb1551f6c93a8aab9cafba573de7)
        ;

        
    
    
            var marker_d8fb0a61da2e430050760c61b79a617c = L.marker(
                [45.40957329, -122.4227459],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c0592b78720edc9c585c2c88b74ba556 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d8fb0a61da2e430050760c61b79a617c.setIcon(icon_c0592b78720edc9c585c2c88b74ba556);
        
    
        var popup_87ded072decc40343cbc0b050a566432 = L.popup({"maxWidth": "100%"});

        
            
                var html_6d36335243b2835e55271efb29d7baa0 = $(`<div id="html_6d36335243b2835e55271efb29d7baa0" style="width: 100.0%; height: 100.0%;">Lewis and Clark Montessori Charter School</div>`)[0];
                popup_87ded072decc40343cbc0b050a566432.setContent(html_6d36335243b2835e55271efb29d7baa0);
            
        

        marker_d8fb0a61da2e430050760c61b79a617c.bindPopup(popup_87ded072decc40343cbc0b050a566432)
        ;

        
    
    
            var marker_4beb95b4adaab1a61e8d0163b93d04be = L.marker(
                [45.5075811, -122.4408022],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5ea2fbe37822ea95f8d22930467563f0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4beb95b4adaab1a61e8d0163b93d04be.setIcon(icon_5ea2fbe37822ea95f8d22930467563f0);
        
    
        var popup_88f69c6d622dd9e63d06306bd9f0b110 = L.popup({"maxWidth": "100%"});

        
            
                var html_5dc56594edcde52f35057ff28f7f0f3b = $(`<div id="html_5dc56594edcde52f35057ff28f7f0f3b" style="width: 100.0%; height: 100.0%;">Metro East Web Academy</div>`)[0];
                popup_88f69c6d622dd9e63d06306bd9f0b110.setContent(html_5dc56594edcde52f35057ff28f7f0f3b);
            
        

        marker_4beb95b4adaab1a61e8d0163b93d04be.bindPopup(popup_88f69c6d622dd9e63d06306bd9f0b110)
        ;

        
    
    
            var marker_8b70bea0629c2cb3fa72e08b46abd99f = L.marker(
                [45.51549962, -122.4393987],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_148fc07873443c196311e3b6fbe68bd8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8b70bea0629c2cb3fa72e08b46abd99f.setIcon(icon_148fc07873443c196311e3b6fbe68bd8);
        
    
        var popup_c044724ba837de3eaa355e2e2df8454e = L.popup({"maxWidth": "100%"});

        
            
                var html_d67cb70ffc6783b376ad88e9dd60654c = $(`<div id="html_d67cb70ffc6783b376ad88e9dd60654c" style="width: 100.0%; height: 100.0%;">North Gresham Elementary School</div>`)[0];
                popup_c044724ba837de3eaa355e2e2df8454e.setContent(html_d67cb70ffc6783b376ad88e9dd60654c);
            
        

        marker_8b70bea0629c2cb3fa72e08b46abd99f.bindPopup(popup_c044724ba837de3eaa355e2e2df8454e)
        ;

        
    
    
            var marker_8fcbee8cb5dda148deb79d0b1390ef59 = L.marker(
                [45.49110005, -122.3837687],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_315fe145c7884826eaba56141bf2bb93 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8fcbee8cb5dda148deb79d0b1390ef59.setIcon(icon_315fe145c7884826eaba56141bf2bb93);
        
    
        var popup_d288d31937040dff554be1fc475c3ea4 = L.popup({"maxWidth": "100%"});

        
            
                var html_6a1adf77a8d9190b958bd4f7bf004c3f = $(`<div id="html_6a1adf77a8d9190b958bd4f7bf004c3f" style="width: 100.0%; height: 100.0%;">Powell Valley Elementary School</div>`)[0];
                popup_d288d31937040dff554be1fc475c3ea4.setContent(html_6a1adf77a8d9190b958bd4f7bf004c3f);
            
        

        marker_8fcbee8cb5dda148deb79d0b1390ef59.bindPopup(popup_d288d31937040dff554be1fc475c3ea4)
        ;

        
    
    
            var marker_51f4bfb8e5ca12dd535a357aa644b089 = L.marker(
                [45.51516991, -122.9417743],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a3c35188c4544678c69212682f797473 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_51f4bfb8e5ca12dd535a357aa644b089.setIcon(icon_a3c35188c4544678c69212682f797473);
        
    
        var popup_44c9e947cbb994ab8de0c74d466c02da = L.popup({"maxWidth": "100%"});

        
            
                var html_6f87ccf77175d65c0dca53ec0b66eb54 = $(`<div id="html_6f87ccf77175d65c0dca53ec0b66eb54" style="width: 100.0%; height: 100.0%;">Brookwood Elementary School</div>`)[0];
                popup_44c9e947cbb994ab8de0c74d466c02da.setContent(html_6f87ccf77175d65c0dca53ec0b66eb54);
            
        

        marker_51f4bfb8e5ca12dd535a357aa644b089.bindPopup(popup_44c9e947cbb994ab8de0c74d466c02da)
        ;

        
    
    
            var marker_c339ab2a50f2cade538655282ff8965c = L.marker(
                [45.48709098, -122.8867422],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0f8723e46726fd3a926526fa7f8bd971 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c339ab2a50f2cade538655282ff8965c.setIcon(icon_0f8723e46726fd3a926526fa7f8bd971);
        
    
        var popup_9734bf5ab544a41133ce8b98342ebf2d = L.popup({"maxWidth": "100%"});

        
            
                var html_dfda04c2438d60303d1085c26cca0e4b = $(`<div id="html_dfda04c2438d60303d1085c26cca0e4b" style="width: 100.0%; height: 100.0%;">Butternut Creek Elementary School</div>`)[0];
                popup_9734bf5ab544a41133ce8b98342ebf2d.setContent(html_dfda04c2438d60303d1085c26cca0e4b);
            
        

        marker_c339ab2a50f2cade538655282ff8965c.bindPopup(popup_9734bf5ab544a41133ce8b98342ebf2d)
        ;

        
    
    
            var marker_9fc9b7f02a601962aaadf16d5a459a6a = L.marker(
                [45.51155151, -122.9394671],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e76065de1312bcff838415b0121088bd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9fc9b7f02a601962aaadf16d5a459a6a.setIcon(icon_e76065de1312bcff838415b0121088bd);
        
    
        var popup_e2b62b9e4b09162be746590257a6d848 = L.popup({"maxWidth": "100%"});

        
            
                var html_b877147aafa9870a2019639554c5c039 = $(`<div id="html_b877147aafa9870a2019639554c5c039" style="width: 100.0%; height: 100.0%;">City View Charter School</div>`)[0];
                popup_e2b62b9e4b09162be746590257a6d848.setContent(html_b877147aafa9870a2019639554c5c039);
            
        

        marker_9fc9b7f02a601962aaadf16d5a459a6a.bindPopup(popup_e2b62b9e4b09162be746590257a6d848)
        ;

        
    
    
            var marker_86db7512fb3a3f42125ef70a5773c55e = L.marker(
                [45.5236076, -122.9597678],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_193cd252d20cb15bab527024819bc739 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_86db7512fb3a3f42125ef70a5773c55e.setIcon(icon_193cd252d20cb15bab527024819bc739);
        
    
        var popup_fac69ff57612b7a23cbe051205d20a44 = L.popup({"maxWidth": "100%"});

        
            
                var html_e1d92f013895238fedfb87a76fa58a37 = $(`<div id="html_e1d92f013895238fedfb87a76fa58a37" style="width: 100.0%; height: 100.0%;">Eastwood Elementary School</div>`)[0];
                popup_fac69ff57612b7a23cbe051205d20a44.setContent(html_e1d92f013895238fedfb87a76fa58a37);
            
        

        marker_86db7512fb3a3f42125ef70a5773c55e.bindPopup(popup_fac69ff57612b7a23cbe051205d20a44)
        ;

        
    
    
            var marker_3bd2252b4ea8efc3d2b86edb0102cb07 = L.marker(
                [45.46030351, -122.991385],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_244976ac3ba20b8a80478e5fed0d7041 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3bd2252b4ea8efc3d2b86edb0102cb07.setIcon(icon_244976ac3ba20b8a80478e5fed0d7041);
        
    
        var popup_bdc0e83ebc45534b3e5da8dfdc58c8a3 = L.popup({"maxWidth": "100%"});

        
            
                var html_a2eebd9e86feb5edaf4a49f1deb5bc6f = $(`<div id="html_a2eebd9e86feb5edaf4a49f1deb5bc6f" style="width: 100.0%; height: 100.0%;">Farmington View Elementary School</div>`)[0];
                popup_bdc0e83ebc45534b3e5da8dfdc58c8a3.setContent(html_a2eebd9e86feb5edaf4a49f1deb5bc6f);
            
        

        marker_3bd2252b4ea8efc3d2b86edb0102cb07.bindPopup(popup_bdc0e83ebc45534b3e5da8dfdc58c8a3)
        ;

        
    
    
            var marker_0d790d0568490e25d52d051c8fe304ab = L.marker(
                [45.5174434, -123.0414732],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d4e9c133edb971393bc85fc5223fab52 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0d790d0568490e25d52d051c8fe304ab.setIcon(icon_d4e9c133edb971393bc85fc5223fab52);
        
    
        var popup_ae2b7ad2dceefa5f52d4dc6a3579b3f3 = L.popup({"maxWidth": "100%"});

        
            
                var html_01a4b447825dce39c11a735847f099ef = $(`<div id="html_01a4b447825dce39c11a735847f099ef" style="width: 100.0%; height: 100.0%;">Free Orchards Elementary School</div>`)[0];
                popup_ae2b7ad2dceefa5f52d4dc6a3579b3f3.setContent(html_01a4b447825dce39c11a735847f099ef);
            
        

        marker_0d790d0568490e25d52d051c8fe304ab.bindPopup(popup_ae2b7ad2dceefa5f52d4dc6a3579b3f3)
        ;

        
    
    
            var marker_9365f32ed1c0fc91a136f358a75ca81e = L.marker(
                [45.41782625, -122.9201329],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_93794bb373c5bd011d58f137c181f08a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9365f32ed1c0fc91a136f358a75ca81e.setIcon(icon_93794bb373c5bd011d58f137c181f08a);
        
    
        var popup_8fa424b7d350207451a30653eab8c02f = L.popup({"maxWidth": "100%"});

        
            
                var html_f76533b90af90cbcb789b9e8d9af160f = $(`<div id="html_f76533b90af90cbcb789b9e8d9af160f" style="width: 100.0%; height: 100.0%;">Groner K-8</div>`)[0];
                popup_8fa424b7d350207451a30653eab8c02f.setContent(html_f76533b90af90cbcb789b9e8d9af160f);
            
        

        marker_9365f32ed1c0fc91a136f358a75ca81e.bindPopup(popup_8fa424b7d350207451a30653eab8c02f)
        ;

        
    
    
            var marker_5c76e708d16485e18e2cda985df49b0d = L.marker(
                [45.52777543, -122.9854995],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1f02e3b4e19d05a9bcc93b074ebc51e6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5c76e708d16485e18e2cda985df49b0d.setIcon(icon_1f02e3b4e19d05a9bcc93b074ebc51e6);
        
    
        var popup_591221c57132eb6c402add24b73abbd2 = L.popup({"maxWidth": "100%"});

        
            
                var html_76d11dd06e3d45d0615d9de5e5f9a951 = $(`<div id="html_76d11dd06e3d45d0615d9de5e5f9a951" style="width: 100.0%; height: 100.0%;">Hillsboro Online Academy</div>`)[0];
                popup_591221c57132eb6c402add24b73abbd2.setContent(html_76d11dd06e3d45d0615d9de5e5f9a951);
            
        

        marker_5c76e708d16485e18e2cda985df49b0d.bindPopup(popup_591221c57132eb6c402add24b73abbd2)
        ;

        
    
    
            var marker_3e6b0bbbdf3529b22d9c5f7c7e151879 = L.marker(
                [45.51191849, -122.9208748],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_6bcf9332869b4dc5c4cfb97440a02a6f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3e6b0bbbdf3529b22d9c5f7c7e151879.setIcon(icon_6bcf9332869b4dc5c4cfb97440a02a6f);
        
    
        var popup_e68ea58242d90ff5e2c6da74ec330a2f = L.popup({"maxWidth": "100%"});

        
            
                var html_cdb52adfc11d692f29440da44cdec5b0 = $(`<div id="html_cdb52adfc11d692f29440da44cdec5b0" style="width: 100.0%; height: 100.0%;">Imlay Elementary School</div>`)[0];
                popup_e68ea58242d90ff5e2c6da74ec330a2f.setContent(html_cdb52adfc11d692f29440da44cdec5b0);
            
        

        marker_3e6b0bbbdf3529b22d9c5f7c7e151879.bindPopup(popup_e68ea58242d90ff5e2c6da74ec330a2f)
        ;

        
    
    
            var marker_05056f824bd8ba916f40a7c248731ea0 = L.marker(
                [45.50694109, -122.8952784],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0f024f891637954cf2c2bdefaab8c207 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_05056f824bd8ba916f40a7c248731ea0.setIcon(icon_0f024f891637954cf2c2bdefaab8c207);
        
    
        var popup_60d4798d7a62d72bdd5f4ffe95ac4070 = L.popup({"maxWidth": "100%"});

        
            
                var html_2b0500e6a49f8ecabd2378e7d40cd17b = $(`<div id="html_2b0500e6a49f8ecabd2378e7d40cd17b" style="width: 100.0%; height: 100.0%;">Indian Hills Elementary School</div>`)[0];
                popup_60d4798d7a62d72bdd5f4ffe95ac4070.setContent(html_2b0500e6a49f8ecabd2378e7d40cd17b);
            
        

        marker_05056f824bd8ba916f40a7c248731ea0.bindPopup(popup_60d4798d7a62d72bdd5f4ffe95ac4070)
        ;

        
    
    
            var marker_056bb90f8c347b96b2029eb90ff7209a = L.marker(
                [45.54380475, -122.9815486],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1492fec5d1f74cc66971132a45989198 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_056bb90f8c347b96b2029eb90ff7209a.setIcon(icon_1492fec5d1f74cc66971132a45989198);
        
    
        var popup_35cbd7bf101494fc88801d3aedbc3034 = L.popup({"maxWidth": "100%"});

        
            
                var html_b1d8e5b41a7a2c61e63c23833760d28f = $(`<div id="html_b1d8e5b41a7a2c61e63c23833760d28f" style="width: 100.0%; height: 100.0%;">Jackson Elementary School</div>`)[0];
                popup_35cbd7bf101494fc88801d3aedbc3034.setContent(html_b1d8e5b41a7a2c61e63c23833760d28f);
            
        

        marker_056bb90f8c347b96b2029eb90ff7209a.bindPopup(popup_35cbd7bf101494fc88801d3aedbc3034)
        ;

        
    
    
            var marker_13a1fa95dd64003a26c38d7adca24ee4 = L.marker(
                [45.50223209, -122.903353],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_052da50eca4a46db166ae6ec0893efa9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_13a1fa95dd64003a26c38d7adca24ee4.setIcon(icon_052da50eca4a46db166ae6ec0893efa9);
        
    
        var popup_12f2f3088a60040d5e9fb95ba17427f9 = L.popup({"maxWidth": "100%"});

        
            
                var html_b7948b452783f89e2c36120699d93230 = $(`<div id="html_b7948b452783f89e2c36120699d93230" style="width: 100.0%; height: 100.0%;">Ladd Acres Elementary School</div>`)[0];
                popup_12f2f3088a60040d5e9fb95ba17427f9.setContent(html_b7948b452783f89e2c36120699d93230);
            
        

        marker_13a1fa95dd64003a26c38d7adca24ee4.bindPopup(popup_12f2f3088a60040d5e9fb95ba17427f9)
        ;

        
    
    
            var marker_9d2f671d4d21edf872b69bfa7d71579f = L.marker(
                [45.55809266, -122.8940071],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f3f689c3efde1c6aa1577b635029eb6e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9d2f671d4d21edf872b69bfa7d71579f.setIcon(icon_f3f689c3efde1c6aa1577b635029eb6e);
        
    
        var popup_3272cfe31f3d3f292265f64a4a2618dd = L.popup({"maxWidth": "100%"});

        
            
                var html_6dcb22ef5dcb949183279463faad0b44 = $(`<div id="html_6dcb22ef5dcb949183279463faad0b44" style="width: 100.0%; height: 100.0%;">Lenox Elementary School</div>`)[0];
                popup_3272cfe31f3d3f292265f64a4a2618dd.setContent(html_6dcb22ef5dcb949183279463faad0b44);
            
        

        marker_9d2f671d4d21edf872b69bfa7d71579f.bindPopup(popup_3272cfe31f3d3f292265f64a4a2618dd)
        ;

        
    
    
            var marker_2097d21053843af769230dbaca553620 = L.marker(
                [45.52429065, -122.9773053],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_88125389386bedbf9759c9c3c414eb38 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2097d21053843af769230dbaca553620.setIcon(icon_88125389386bedbf9759c9c3c414eb38);
        
    
        var popup_ccd1e168fd27ed15b7e2ac8c262fc274 = L.popup({"maxWidth": "100%"});

        
            
                var html_b6a64ece19c07f295b71ea7f46ab006f = $(`<div id="html_b6a64ece19c07f295b71ea7f46ab006f" style="width: 100.0%; height: 100.0%;">Lincoln Street Elementary School</div>`)[0];
                popup_ccd1e168fd27ed15b7e2ac8c262fc274.setContent(html_b6a64ece19c07f295b71ea7f46ab006f);
            
        

        marker_2097d21053843af769230dbaca553620.bindPopup(popup_ccd1e168fd27ed15b7e2ac8c262fc274)
        ;

        
    
    
            var marker_027524904b37c29c7339e15c48bf47d6 = L.marker(
                [45.49713971, -122.9633544],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_84f99f0a9091087a6bdff450c68fddb9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_027524904b37c29c7339e15c48bf47d6.setIcon(icon_84f99f0a9091087a6bdff450c68fddb9);
        
    
        var popup_4649ac68648aae1c6bc94a38514b40d6 = L.popup({"maxWidth": "100%"});

        
            
                var html_f59148521490a8ae8691be2c598638ed = $(`<div id="html_f59148521490a8ae8691be2c598638ed" style="width: 100.0%; height: 100.0%;">Minter Bridge Elementary School</div>`)[0];
                popup_4649ac68648aae1c6bc94a38514b40d6.setContent(html_f59148521490a8ae8691be2c598638ed);
            
        

        marker_027524904b37c29c7339e15c48bf47d6.bindPopup(popup_4649ac68648aae1c6bc94a38514b40d6)
        ;

        
    
    
            var marker_92fd71ad8a72fcb6b468b948e3ad3417 = L.marker(
                [45.53384192, -122.9717777],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_ae96781102d9cebdb6d69228998e5f6e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_92fd71ad8a72fcb6b468b948e3ad3417.setIcon(icon_ae96781102d9cebdb6d69228998e5f6e);
        
    
        var popup_25e34bd149fb92e3a7a134d5b1ccdb02 = L.popup({"maxWidth": "100%"});

        
            
                var html_aea8fa3d48aba3cf9a5cc25414eba047 = $(`<div id="html_aea8fa3d48aba3cf9a5cc25414eba047" style="width: 100.0%; height: 100.0%;">Mooberry Elementary School</div>`)[0];
                popup_25e34bd149fb92e3a7a134d5b1ccdb02.setContent(html_aea8fa3d48aba3cf9a5cc25414eba047);
            
        

        marker_92fd71ad8a72fcb6b468b948e3ad3417.bindPopup(popup_25e34bd149fb92e3a7a134d5b1ccdb02)
        ;

        
    
    
            var marker_a0e50a76e3f081a37ea9c9fd06fbd838 = L.marker(
                [45.60175268, -123.0066816],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7670b80e7ba5e900661b0f99b54c76d2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a0e50a76e3f081a37ea9c9fd06fbd838.setIcon(icon_7670b80e7ba5e900661b0f99b54c76d2);
        
    
        var popup_b5041eef16902a3ba8ad910e0889b102 = L.popup({"maxWidth": "100%"});

        
            
                var html_76d752fc0a5bc140056eb3e2e82954c0 = $(`<div id="html_76d752fc0a5bc140056eb3e2e82954c0" style="width: 100.0%; height: 100.0%;">North Plains Elementary School</div>`)[0];
                popup_b5041eef16902a3ba8ad910e0889b102.setContent(html_76d752fc0a5bc140056eb3e2e82954c0);
            
        

        marker_a0e50a76e3f081a37ea9c9fd06fbd838.bindPopup(popup_b5041eef16902a3ba8ad910e0889b102)
        ;

        
    
    
            var marker_b583966809c91c0e9bdbaf0784b7a868 = L.marker(
                [45.5283789, -122.9074744],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_64e14d7e11f0bd5990c39d61a7bbbb5a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b583966809c91c0e9bdbaf0784b7a868.setIcon(icon_64e14d7e11f0bd5990c39d61a7bbbb5a);
        
    
        var popup_14906bba3eb8e595cab8a2d286c95ff3 = L.popup({"maxWidth": "100%"});

        
            
                var html_1cb2e9044f78e080cedbbb1b2e3a28e7 = $(`<div id="html_1cb2e9044f78e080cedbbb1b2e3a28e7" style="width: 100.0%; height: 100.0%;">Orenco Elementary School</div>`)[0];
                popup_14906bba3eb8e595cab8a2d286c95ff3.setContent(html_1cb2e9044f78e080cedbbb1b2e3a28e7);
            
        

        marker_b583966809c91c0e9bdbaf0784b7a868.bindPopup(popup_14906bba3eb8e595cab8a2d286c95ff3)
        ;

        
    
    
            var marker_b6998b8aff4eeb401338417eb0cfd81e = L.marker(
                [45.54607692, -122.9923193],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b62071c7130b1fbd0be5db818aa32e4e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b6998b8aff4eeb401338417eb0cfd81e.setIcon(icon_b62071c7130b1fbd0be5db818aa32e4e);
        
    
        var popup_c96751e8f71644eb064cad8b5d8f3732 = L.popup({"maxWidth": "100%"});

        
            
                var html_5a13489dfcd676dfa0f8091e03d994e4 = $(`<div id="html_5a13489dfcd676dfa0f8091e03d994e4" style="width: 100.0%; height: 100.0%;">Paul L Patterson Elementary School</div>`)[0];
                popup_c96751e8f71644eb064cad8b5d8f3732.setContent(html_5a13489dfcd676dfa0f8091e03d994e4);
            
        

        marker_b6998b8aff4eeb401338417eb0cfd81e.bindPopup(popup_c96751e8f71644eb064cad8b5d8f3732)
        ;

        
    
    
            var marker_227c75a918a8e8e637daa274710079aa = L.marker(
                [45.53287573, -122.9087663],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_ce034914359603f58c55987b74f8c7fa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_227c75a918a8e8e637daa274710079aa.setIcon(icon_ce034914359603f58c55987b74f8c7fa);
        
    
        var popup_477f46441ed9be917d33fd0a6c19e00b = L.popup({"maxWidth": "100%"});

        
            
                var html_33b78686069877203c2b87b4fdf55e6a = $(`<div id="html_33b78686069877203c2b87b4fdf55e6a" style="width: 100.0%; height: 100.0%;">Quatama Elementary School</div>`)[0];
                popup_477f46441ed9be917d33fd0a6c19e00b.setContent(html_33b78686069877203c2b87b4fdf55e6a);
            
        

        marker_227c75a918a8e8e637daa274710079aa.bindPopup(popup_477f46441ed9be917d33fd0a6c19e00b)
        ;

        
    
    
            var marker_4d6e62f60039f04217ec85d0e533377d = L.marker(
                [45.50016699, -122.8919151],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_01cd920e7213c83c9179ba5e1c80ff16 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4d6e62f60039f04217ec85d0e533377d.setIcon(icon_01cd920e7213c83c9179ba5e1c80ff16);
        
    
        var popup_e18f4d0c29ae6d350d88022a97e354bf = L.popup({"maxWidth": "100%"});

        
            
                var html_c90caf687710df54f218c98ea7948051 = $(`<div id="html_c90caf687710df54f218c98ea7948051" style="width: 100.0%; height: 100.0%;">Reedville Elementary School</div>`)[0];
                popup_e18f4d0c29ae6d350d88022a97e354bf.setContent(html_c90caf687710df54f218c98ea7948051);
            
        

        marker_4d6e62f60039f04217ec85d0e533377d.bindPopup(popup_e18f4d0c29ae6d350d88022a97e354bf)
        ;

        
    
    
            var marker_c5a0067ba0fbd43864fb84017f78138d = L.marker(
                [45.49156985, -122.9142855],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_ae9b1a8eabe0c493141d8e538e8a37c5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c5a0067ba0fbd43864fb84017f78138d.setIcon(icon_ae9b1a8eabe0c493141d8e538e8a37c5);
        
    
        var popup_ea37f36d412bf82efc325651b41e007a = L.popup({"maxWidth": "100%"});

        
            
                var html_b4c48233841c2d5b8a5e26bf9fafdcce = $(`<div id="html_b4c48233841c2d5b8a5e26bf9fafdcce" style="width: 100.0%; height: 100.0%;">Rosedale Elementary School</div>`)[0];
                popup_ea37f36d412bf82efc325651b41e007a.setContent(html_b4c48233841c2d5b8a5e26bf9fafdcce);
            
        

        marker_c5a0067ba0fbd43864fb84017f78138d.bindPopup(popup_ea37f36d412bf82efc325651b41e007a)
        ;

        
    
    
            var marker_379f68a0116d3881bfffdcea3a0a75f9 = L.marker(
                [45.51217461, -122.8908262],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a0dbedd4bc658eb98de652df977a062f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_379f68a0116d3881bfffdcea3a0a75f9.setIcon(icon_a0dbedd4bc658eb98de652df977a062f);
        
    
        var popup_6ece4930555d7d0b44da6a3b4954fdc4 = L.popup({"maxWidth": "100%"});

        
            
                var html_705cfe197b683229e761609698fe8bd6 = $(`<div id="html_705cfe197b683229e761609698fe8bd6" style="width: 100.0%; height: 100.0%;">Tobias Elementary School</div>`)[0];
                popup_6ece4930555d7d0b44da6a3b4954fdc4.setContent(html_705cfe197b683229e761609698fe8bd6);
            
        

        marker_379f68a0116d3881bfffdcea3a0a75f9.bindPopup(popup_6ece4930555d7d0b44da6a3b4954fdc4)
        ;

        
    
    
            var marker_ce4569e6b26e18ba2a0e35964d2df072 = L.marker(
                [45.51206022, -122.9566646],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_03073c7a95d1eb1b23ad2b7fc91c05d4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ce4569e6b26e18ba2a0e35964d2df072.setIcon(icon_03073c7a95d1eb1b23ad2b7fc91c05d4);
        
    
        var popup_28a841465262373a54172034cd4c8f69 = L.popup({"maxWidth": "100%"});

        
            
                var html_f77895b0853ecb94f11be21fb9a38b67 = $(`<div id="html_f77895b0853ecb94f11be21fb9a38b67" style="width: 100.0%; height: 100.0%;">W L Henry Elementary School</div>`)[0];
                popup_28a841465262373a54172034cd4c8f69.setContent(html_f77895b0853ecb94f11be21fb9a38b67);
            
        

        marker_ce4569e6b26e18ba2a0e35964d2df072.bindPopup(popup_28a841465262373a54172034cd4c8f69)
        ;

        
    
    
            var marker_9a774bf7419e38cb4525f33107a892b7 = L.marker(
                [45.53052439, -122.9955627],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f631950648f459f8b9681c2f4119dbe1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9a774bf7419e38cb4525f33107a892b7.setIcon(icon_f631950648f459f8b9681c2f4119dbe1);
        
    
        var popup_720cba90a9907c2592cea3396ea534c5 = L.popup({"maxWidth": "100%"});

        
            
                var html_a7dc662e974f1ffb634d8e3069740106 = $(`<div id="html_a7dc662e974f1ffb634d8e3069740106" style="width: 100.0%; height: 100.0%;">W Verne McKinney Elementary School</div>`)[0];
                popup_720cba90a9907c2592cea3396ea534c5.setContent(html_a7dc662e974f1ffb634d8e3069740106);
            
        

        marker_9a774bf7419e38cb4525f33107a892b7.bindPopup(popup_720cba90a9907c2592cea3396ea534c5)
        ;

        
    
    
            var marker_b033ce9899fd1640d6db64bd86213551 = L.marker(
                [45.57698073, -122.9234732],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_254076254aa02714510185ff951bcf25 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b033ce9899fd1640d6db64bd86213551.setIcon(icon_254076254aa02714510185ff951bcf25);
        
    
        var popup_e700cb65173eee5e9e24fc0c5e40c5f3 = L.popup({"maxWidth": "100%"});

        
            
                var html_7f30487fc6d748be9dd005278112dfac = $(`<div id="html_7f30487fc6d748be9dd005278112dfac" style="width: 100.0%; height: 100.0%;">West Union Elementary School</div>`)[0];
                popup_e700cb65173eee5e9e24fc0c5e40c5f3.setContent(html_7f30487fc6d748be9dd005278112dfac);
            
        

        marker_b033ce9899fd1640d6db64bd86213551.bindPopup(popup_e700cb65173eee5e9e24fc0c5e40c5f3)
        ;

        
    
    
            var marker_2d02941909e2cb3d824706095683007f = L.marker(
                [45.49364133, -122.9326909],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_56d8b3185bf6de9b675efb290950f05c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2d02941909e2cb3d824706095683007f.setIcon(icon_56d8b3185bf6de9b675efb290950f05c);
        
    
        var popup_ea7ec623563695aab740ed81207e56ad = L.popup({"maxWidth": "100%"});

        
            
                var html_3a68d154c81d30cd8eb347eb5225b55c = $(`<div id="html_3a68d154c81d30cd8eb347eb5225b55c" style="width: 100.0%; height: 100.0%;">Witch Hazel Elementary School</div>`)[0];
                popup_ea7ec623563695aab740ed81207e56ad.setContent(html_3a68d154c81d30cd8eb347eb5225b55c);
            
        

        marker_2d02941909e2cb3d824706095683007f.bindPopup(popup_ea7ec623563695aab740ed81207e56ad)
        ;

        
    
    
            var marker_93a4ade32f87564d3fca66b5cdf81bc9 = L.marker(
                [45.42595085, -122.6768595],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7dc69e28a99b20353b90b5a9d9872883 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_93a4ade32f87564d3fca66b5cdf81bc9.setIcon(icon_7dc69e28a99b20353b90b5a9d9872883);
        
    
        var popup_38f378cd3ccba3395792b298e9edd8e7 = L.popup({"maxWidth": "100%"});

        
            
                var html_c40efc343966b625d6eeada2147a8840 = $(`<div id="html_c40efc343966b625d6eeada2147a8840" style="width: 100.0%; height: 100.0%;">Forest Hills Elementary School</div>`)[0];
                popup_38f378cd3ccba3395792b298e9edd8e7.setContent(html_c40efc343966b625d6eeada2147a8840);
            
        

        marker_93a4ade32f87564d3fca66b5cdf81bc9.bindPopup(popup_38f378cd3ccba3395792b298e9edd8e7)
        ;

        
    
    
            var marker_37d13767556501ce50d7ed4a7d8b2e5f = L.marker(
                [45.4043899, -122.6644748],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_da23607a198ccc8f59781610ac48b3d2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_37d13767556501ce50d7ed4a7d8b2e5f.setIcon(icon_da23607a198ccc8f59781610ac48b3d2);
        
    
        var popup_1253322a271e64a4f2ffcb885c9dda23 = L.popup({"maxWidth": "100%"});

        
            
                var html_8edac621c76cf46306002a35a257fa36 = $(`<div id="html_8edac621c76cf46306002a35a257fa36" style="width: 100.0%; height: 100.0%;">Hallinan Elementary School</div>`)[0];
                popup_1253322a271e64a4f2ffcb885c9dda23.setContent(html_8edac621c76cf46306002a35a257fa36);
            
        

        marker_37d13767556501ce50d7ed4a7d8b2e5f.bindPopup(popup_1253322a271e64a4f2ffcb885c9dda23)
        ;

        
    
    
            var marker_bdb9459e5ff04df6d8f70fe3a23931ef = L.marker(
                [45.41234137, -122.7192773],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a7ab22fa0f756b33d19a279c565cf411 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_bdb9459e5ff04df6d8f70fe3a23931ef.setIcon(icon_a7ab22fa0f756b33d19a279c565cf411);
        
    
        var popup_83521e4b6ac6ef8b920bb58ab8f887f7 = L.popup({"maxWidth": "100%"});

        
            
                var html_47a446a57ff1039f9623f405ce99e5cf = $(`<div id="html_47a446a57ff1039f9623f405ce99e5cf" style="width: 100.0%; height: 100.0%;">Lake Grove Elementary School</div>`)[0];
                popup_83521e4b6ac6ef8b920bb58ab8f887f7.setContent(html_47a446a57ff1039f9623f405ce99e5cf);
            
        

        marker_bdb9459e5ff04df6d8f70fe3a23931ef.bindPopup(popup_83521e4b6ac6ef8b920bb58ab8f887f7)
        ;

        
    
    
            var marker_a3bebd5d4068e39b1c4d94511fe7e0cd = L.marker(
                [45.42716983, -122.7295115],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f7ba7ab67d4e0d4a39affca305b21d27 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a3bebd5d4068e39b1c4d94511fe7e0cd.setIcon(icon_f7ba7ab67d4e0d4a39affca305b21d27);
        
    
        var popup_e5b32eb3588a89617f01fcc5d34e5d11 = L.popup({"maxWidth": "100%"});

        
            
                var html_62e8e36e6a5bcea884f75be103a14e14 = $(`<div id="html_62e8e36e6a5bcea884f75be103a14e14" style="width: 100.0%; height: 100.0%;">Oak Creek Elementary School</div>`)[0];
                popup_e5b32eb3588a89617f01fcc5d34e5d11.setContent(html_62e8e36e6a5bcea884f75be103a14e14);
            
        

        marker_a3bebd5d4068e39b1c4d94511fe7e0cd.bindPopup(popup_e5b32eb3588a89617f01fcc5d34e5d11)
        ;

        
    
    
            var marker_3eae350d63f143a7801d1d4bb5493149 = L.marker(
                [45.38905796, -122.7364681],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_598d9adc4f7d5e5816485a849aa6e249 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3eae350d63f143a7801d1d4bb5493149.setIcon(icon_598d9adc4f7d5e5816485a849aa6e249);
        
    
        var popup_1db00b5dc98c766aa19c2d54828d5fb8 = L.popup({"maxWidth": "100%"});

        
            
                var html_bcdfbd98eabc7fd19a0d97513598eb98 = $(`<div id="html_bcdfbd98eabc7fd19a0d97513598eb98" style="width: 100.0%; height: 100.0%;">River Grove Elementary School</div>`)[0];
                popup_1db00b5dc98c766aa19c2d54828d5fb8.setContent(html_bcdfbd98eabc7fd19a0d97513598eb98);
            
        

        marker_3eae350d63f143a7801d1d4bb5493149.bindPopup(popup_1db00b5dc98c766aa19c2d54828d5fb8)
        ;

        
    
    
            var marker_685c087d5227f25bf571fbfd4f3f7dfa = L.marker(
                [45.39512253, -122.7120196],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f82f18053ae951fec01d702523c81335 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_685c087d5227f25bf571fbfd4f3f7dfa.setIcon(icon_f82f18053ae951fec01d702523c81335);
        
    
        var popup_8f60c05da798a8935ecc857e44d76c52 = L.popup({"maxWidth": "100%"});

        
            
                var html_7a217159ee20d35d4588189e1aed55d5 = $(`<div id="html_7a217159ee20d35d4588189e1aed55d5" style="width: 100.0%; height: 100.0%;">Westridge Elementary School</div>`)[0];
                popup_8f60c05da798a8935ecc857e44d76c52.setContent(html_7a217159ee20d35d4588189e1aed55d5);
            
        

        marker_685c087d5227f25bf571fbfd4f3f7dfa.bindPopup(popup_8f60c05da798a8935ecc857e44d76c52)
        ;

        
    
    
            var marker_63c0e2323d7729705caaa87761923d1c = L.marker(
                [45.45800813, -122.6244528],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3cccfa812befa1e249a217e63ebb29bf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_63c0e2323d7729705caaa87761923d1c.setIcon(icon_3cccfa812befa1e249a217e63ebb29bf);
        
    
        var popup_aecc8c0c23015281a08822afa3ed6464 = L.popup({"maxWidth": "100%"});

        
            
                var html_143bc2ad6f331d47da6e77b8e055d69b = $(`<div id="html_143bc2ad6f331d47da6e77b8e055d69b" style="width: 100.0%; height: 100.0%;">Ardenwald Elementary School</div>`)[0];
                popup_aecc8c0c23015281a08822afa3ed6464.setContent(html_143bc2ad6f331d47da6e77b8e055d69b);
            
        

        marker_63c0e2323d7729705caaa87761923d1c.bindPopup(popup_aecc8c0c23015281a08822afa3ed6464)
        ;

        
    
    
            var marker_57fc3184a93adea2e4d24c917c560d62 = L.marker(
                [45.430375, -122.476961],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_ddd83d5c9f2bc659d104d3bb79dd1f9a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_57fc3184a93adea2e4d24c917c560d62.setIcon(icon_ddd83d5c9f2bc659d104d3bb79dd1f9a);
        
    
        var popup_5ce21c1e1ab3c314fe7702896cde1c27 = L.popup({"maxWidth": "100%"});

        
            
                var html_f8e77ca16cbfc7832d2f29af70814c2e = $(`<div id="html_f8e77ca16cbfc7832d2f29af70814c2e" style="width: 100.0%; height: 100.0%;">Beatrice Morrow Cannady Elementary</div>`)[0];
                popup_5ce21c1e1ab3c314fe7702896cde1c27.setContent(html_f8e77ca16cbfc7832d2f29af70814c2e);
            
        

        marker_57fc3184a93adea2e4d24c917c560d62.bindPopup(popup_5ce21c1e1ab3c314fe7702896cde1c27)
        ;

        
    
    
            var marker_e04d3721b8759c36b4c3ab3e5ef42641 = L.marker(
                [45.40944349, -122.5888862],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5406b242a799389a15c638c62277403b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_e04d3721b8759c36b4c3ab3e5ef42641.setIcon(icon_5406b242a799389a15c638c62277403b);
        
    
        var popup_1d05515a727e281415b3a147d8e27fd8 = L.popup({"maxWidth": "100%"});

        
            
                var html_6560db2f439efa9ebc3ae6cc31efcb7a = $(`<div id="html_6560db2f439efa9ebc3ae6cc31efcb7a" style="width: 100.0%; height: 100.0%;">Bilquist Elementary School</div>`)[0];
                popup_1d05515a727e281415b3a147d8e27fd8.setContent(html_6560db2f439efa9ebc3ae6cc31efcb7a);
            
        

        marker_e04d3721b8759c36b4c3ab3e5ef42641.bindPopup(popup_1d05515a727e281415b3a147d8e27fd8)
        ;

        
    
    
            var marker_3a69c73019a29701c2f457960731189a = L.marker(
                [45.41206499, -122.5696787],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7270c3fe0c22968a15ea51f789f42b65 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3a69c73019a29701c2f457960731189a.setIcon(icon_7270c3fe0c22968a15ea51f789f42b65);
        
    
        var popup_8917ad5f26d902814768505f336cc748 = L.popup({"maxWidth": "100%"});

        
            
                var html_5759edffc83f6b4901de052323f7dfd2 = $(`<div id="html_5759edffc83f6b4901de052323f7dfd2" style="width: 100.0%; height: 100.0%;">Cascade Heights Public Charter School</div>`)[0];
                popup_8917ad5f26d902814768505f336cc748.setContent(html_5759edffc83f6b4901de052323f7dfd2);
            
        

        marker_3a69c73019a29701c2f457960731189a.bindPopup(popup_8917ad5f26d902814768505f336cc748)
        ;

        
    
    
            var marker_79de0acd38aa80aae65098ac428f9276 = L.marker(
                [45.42956568, -122.5729435],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_03fc3b1d4de6d8ed7ac13c2662b5dd02 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_79de0acd38aa80aae65098ac428f9276.setIcon(icon_03fc3b1d4de6d8ed7ac13c2662b5dd02);
        
    
        var popup_f5f8521438071f73c86562f35e26cb7d = L.popup({"maxWidth": "100%"});

        
            
                var html_b232873d3662eea3c3ca393dd9dc4305 = $(`<div id="html_b232873d3662eea3c3ca393dd9dc4305" style="width: 100.0%; height: 100.0%;">Clackamas Web Academy</div>`)[0];
                popup_f5f8521438071f73c86562f35e26cb7d.setContent(html_b232873d3662eea3c3ca393dd9dc4305);
            
        

        marker_79de0acd38aa80aae65098ac428f9276.bindPopup(popup_f5f8521438071f73c86562f35e26cb7d)
        ;

        
    
    
            var marker_33b63dba9bac716c6587210214873fda = L.marker(
                [45.44167864, -122.6335575],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_623194bf10c7ebe70c7d071fd71f3181 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_33b63dba9bac716c6587210214873fda.setIcon(icon_623194bf10c7ebe70c7d071fd71f3181);
        
    
        var popup_52da9bdc42a4038faf93cc1a0d5a58ef = L.popup({"maxWidth": "100%"});

        
            
                var html_b1e29cc8773b2e1bd9f2587fd7949893 = $(`<div id="html_b1e29cc8773b2e1bd9f2587fd7949893" style="width: 100.0%; height: 100.0%;">El Puente</div>`)[0];
                popup_52da9bdc42a4038faf93cc1a0d5a58ef.setContent(html_b1e29cc8773b2e1bd9f2587fd7949893);
            
        

        marker_33b63dba9bac716c6587210214873fda.bindPopup(popup_52da9bdc42a4038faf93cc1a0d5a58ef)
        ;

        
    
    
            var marker_63e66ba0741088d592aa7b23fe273fa1 = L.marker(
                [45.44757115, -122.5173146],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_636504d7d17a6fa594e0761a484de816 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_63e66ba0741088d592aa7b23fe273fa1.setIcon(icon_636504d7d17a6fa594e0761a484de816);
        
    
        var popup_218fee7da4bdd94d425c0a20adb318a2 = L.popup({"maxWidth": "100%"});

        
            
                var html_ada59b8d052fa0d2cc0049604d1e01bb = $(`<div id="html_ada59b8d052fa0d2cc0049604d1e01bb" style="width: 100.0%; height: 100.0%;">Happy Valley Elementary School</div>`)[0];
                popup_218fee7da4bdd94d425c0a20adb318a2.setContent(html_ada59b8d052fa0d2cc0049604d1e01bb);
            
        

        marker_63e66ba0741088d592aa7b23fe273fa1.bindPopup(popup_218fee7da4bdd94d425c0a20adb318a2)
        ;

        
    
    
            var marker_22215e4635e4c0bf0ec3373d9a6d31b7 = L.marker(
                [45.45103622, -122.6077888],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_eabc73b7be3104b0fcd134b27ad4af91 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_22215e4635e4c0bf0ec3373d9a6d31b7.setIcon(icon_eabc73b7be3104b0fcd134b27ad4af91);
        
    
        var popup_f2c9b8391fe8a3f1650edf00be3ecf7b = L.popup({"maxWidth": "100%"});

        
            
                var html_34f2c494e43f0e56d29862a0079ba076 = $(`<div id="html_34f2c494e43f0e56d29862a0079ba076" style="width: 100.0%; height: 100.0%;">Lewelling Elementary School</div>`)[0];
                popup_f2c9b8391fe8a3f1650edf00be3ecf7b.setContent(html_34f2c494e43f0e56d29862a0079ba076);
            
        

        marker_22215e4635e4c0bf0ec3373d9a6d31b7.bindPopup(popup_f2c9b8391fe8a3f1650edf00be3ecf7b)
        ;

        
    
    
            var marker_fc91a3600bb4f74417aa06042520ba9e = L.marker(
                [45.43653488, -122.599958],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_4f66bd5319b263f34881053901cd7694 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fc91a3600bb4f74417aa06042520ba9e.setIcon(icon_4f66bd5319b263f34881053901cd7694);
        
    
        var popup_f792cb95d0d46cb59c63d5d298c25df1 = L.popup({"maxWidth": "100%"});

        
            
                var html_f8000483c3fa1edbafe1f9fad2c27772 = $(`<div id="html_f8000483c3fa1edbafe1f9fad2c27772" style="width: 100.0%; height: 100.0%;">Linwood Elementary School</div>`)[0];
                popup_f792cb95d0d46cb59c63d5d298c25df1.setContent(html_f8000483c3fa1edbafe1f9fad2c27772);
            
        

        marker_fc91a3600bb4f74417aa06042520ba9e.bindPopup(popup_f792cb95d0d46cb59c63d5d298c25df1)
        ;

        
    
    
            var marker_20e6df7dafc3f8fe7527792856228a6c = L.marker(
                [45.44249389, -122.5646856],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8b729553e4e67fdf5f717220cd7e1d91 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_20e6df7dafc3f8fe7527792856228a6c.setIcon(icon_8b729553e4e67fdf5f717220cd7e1d91);
        
    
        var popup_ad747aa45374fe5d5245601ac10c4141 = L.popup({"maxWidth": "100%"});

        
            
                var html_68c3e1d1df154e532193286f5ca4699e = $(`<div id="html_68c3e1d1df154e532193286f5ca4699e" style="width: 100.0%; height: 100.0%;">Mount Scott Elementary School</div>`)[0];
                popup_ad747aa45374fe5d5245601ac10c4141.setContent(html_68c3e1d1df154e532193286f5ca4699e);
            
        

        marker_20e6df7dafc3f8fe7527792856228a6c.bindPopup(popup_ad747aa45374fe5d5245601ac10c4141)
        ;

        
    
    
            var marker_330ec04eff65053f7eaed974e7dd4ed6 = L.marker(
                [45.42453478, -122.6421743],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5686ebf7fd077e9651a951334862e22e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_330ec04eff65053f7eaed974e7dd4ed6.setIcon(icon_5686ebf7fd077e9651a951334862e22e);
        
    
        var popup_c13dc6251c285f1925350439136b25e4 = L.popup({"maxWidth": "100%"});

        
            
                var html_cf852afe54e25ccfd6b7b1adaff37da2 = $(`<div id="html_cf852afe54e25ccfd6b7b1adaff37da2" style="width: 100.0%; height: 100.0%;">Oak Grove Elementary</div>`)[0];
                popup_c13dc6251c285f1925350439136b25e4.setContent(html_cf852afe54e25ccfd6b7b1adaff37da2);
            
        

        marker_330ec04eff65053f7eaed974e7dd4ed6.bindPopup(popup_c13dc6251c285f1925350439136b25e4)
        ;

        
    
    
            var marker_ee6c90fddd9a0e39e9bc907c3d382236 = L.marker(
                [45.42197232, -122.5080515],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f7d2849e15ae96beb1c8a6773bec198f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ee6c90fddd9a0e39e9bc907c3d382236.setIcon(icon_f7d2849e15ae96beb1c8a6773bec198f);
        
    
        var popup_a939fd6feaf6955473894c92bea533f4 = L.popup({"maxWidth": "100%"});

        
            
                var html_e31101bc4c560407e99d855d261a5e5a = $(`<div id="html_e31101bc4c560407e99d855d261a5e5a" style="width: 100.0%; height: 100.0%;">Oregon Trail Elementary School</div>`)[0];
                popup_a939fd6feaf6955473894c92bea533f4.setContent(html_e31101bc4c560407e99d855d261a5e5a);
            
        

        marker_ee6c90fddd9a0e39e9bc907c3d382236.bindPopup(popup_a939fd6feaf6955473894c92bea533f4)
        ;

        
    
    
            var marker_8827e231197b10b117484a0e7f631922 = L.marker(
                [45.40439763, -122.6393815],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_bfdcce001ef5f0aeadcfcc06149f3226 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8827e231197b10b117484a0e7f631922.setIcon(icon_bfdcce001ef5f0aeadcfcc06149f3226);
        
    
        var popup_9c85f9f133ae29f2f4eca598e8e1563e = L.popup({"maxWidth": "100%"});

        
            
                var html_33881cbde47130201f4d58a4d76f5c08 = $(`<div id="html_33881cbde47130201f4d58a4d76f5c08" style="width: 100.0%; height: 100.0%;">Riverside Elementary School</div>`)[0];
                popup_9c85f9f133ae29f2f4eca598e8e1563e.setContent(html_33881cbde47130201f4d58a4d76f5c08);
            
        

        marker_8827e231197b10b117484a0e7f631922.bindPopup(popup_9c85f9f133ae29f2f4eca598e8e1563e)
        ;

        
    
    
            var marker_dc855eb15b97298c24c4e9c216fb8dca = L.marker(
                [45.44373908, -122.48804],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3364066017565a9e25d1bf179323b641 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dc855eb15b97298c24c4e9c216fb8dca.setIcon(icon_3364066017565a9e25d1bf179323b641);
        
    
        var popup_81bc2cd5e93fbeb99269c5d19ef51e9f = L.popup({"maxWidth": "100%"});

        
            
                var html_a250101c6db1e67868f767b2da05529c = $(`<div id="html_a250101c6db1e67868f767b2da05529c" style="width: 100.0%; height: 100.0%;">Scouters Mountain Elementary</div>`)[0];
                popup_81bc2cd5e93fbeb99269c5d19ef51e9f.setContent(html_a250101c6db1e67868f767b2da05529c);
            
        

        marker_dc855eb15b97298c24c4e9c216fb8dca.bindPopup(popup_81bc2cd5e93fbeb99269c5d19ef51e9f)
        ;

        
    
    
            var marker_c54a0a091800781b35d84fa56b4b829f = L.marker(
                [45.43653488, -122.599958],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a6a8b1319d99f076bdd80a01ce1fc98d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c54a0a091800781b35d84fa56b4b829f.setIcon(icon_a6a8b1319d99f076bdd80a01ce1fc98d);
        
    
        var popup_7cc958834d6074097783db5cc4aa2f2d = L.popup({"maxWidth": "100%"});

        
            
                var html_093dd37099914b678f8b26250423ba4e = $(`<div id="html_093dd37099914b678f8b26250423ba4e" style="width: 100.0%; height: 100.0%;">Sojourner School</div>`)[0];
                popup_7cc958834d6074097783db5cc4aa2f2d.setContent(html_093dd37099914b678f8b26250423ba4e);
            
        

        marker_c54a0a091800781b35d84fa56b4b829f.bindPopup(popup_7cc958834d6074097783db5cc4aa2f2d)
        ;

        
    
    
            var marker_21a8414765672974c3013417b14a2b80 = L.marker(
                [45.437366, -122.5348232],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a8887ed9cdfc170f34235d37463b27f1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_21a8414765672974c3013417b14a2b80.setIcon(icon_a8887ed9cdfc170f34235d37463b27f1);
        
    
        var popup_2c86cc9a1d8ad411f003af5a76a14f37 = L.popup({"maxWidth": "100%"});

        
            
                var html_a8a5400eef76a6bbcbd599e0ce420149 = $(`<div id="html_a8a5400eef76a6bbcbd599e0ce420149" style="width: 100.0%; height: 100.0%;">Spring Mountain Elementary School</div>`)[0];
                popup_2c86cc9a1d8ad411f003af5a76a14f37.setContent(html_a8a5400eef76a6bbcbd599e0ce420149);
            
        

        marker_21a8414765672974c3013417b14a2b80.bindPopup(popup_2c86cc9a1d8ad411f003af5a76a14f37)
        ;

        
    
    
            var marker_4c6d30f7b0e8f75e6aed21d336efdb75 = L.marker(
                [45.42539136, -122.5289692],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d7e192c478b53ee5033759a9016972e1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4c6d30f7b0e8f75e6aed21d336efdb75.setIcon(icon_d7e192c478b53ee5033759a9016972e1);
        
    
        var popup_e7dcd058fcb0f507c688f388c19d6031 = L.popup({"maxWidth": "100%"});

        
            
                var html_89c7f4bca486ea42f5f9a741a25d4c07 = $(`<div id="html_89c7f4bca486ea42f5f9a741a25d4c07" style="width: 100.0%; height: 100.0%;">Sunnyside Elementary School</div>`)[0];
                popup_e7dcd058fcb0f507c688f388c19d6031.setContent(html_89c7f4bca486ea42f5f9a741a25d4c07);
            
        

        marker_4c6d30f7b0e8f75e6aed21d336efdb75.bindPopup(popup_e7dcd058fcb0f507c688f388c19d6031)
        ;

        
    
    
            var marker_160ef855f0dca194424a1a2d44ab82a0 = L.marker(
                [45.41521208, -122.4875051],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_df97adf2630c17a114216dc368eab8d3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_160ef855f0dca194424a1a2d44ab82a0.setIcon(icon_df97adf2630c17a114216dc368eab8d3);
        
    
        var popup_cd1224c82087c5aa519b68a52f47a431 = L.popup({"maxWidth": "100%"});

        
            
                var html_2ac206f9431b461241432bb75e2bd5c0 = $(`<div id="html_2ac206f9431b461241432bb75e2bd5c0" style="width: 100.0%; height: 100.0%;">Verne A Duncan Elementary School</div>`)[0];
                popup_cd1224c82087c5aa519b68a52f47a431.setContent(html_2ac206f9431b461241432bb75e2bd5c0);
            
        

        marker_160ef855f0dca194424a1a2d44ab82a0.bindPopup(popup_cd1224c82087c5aa519b68a52f47a431)
        ;

        
    
    
            var marker_9e82b2613e76e740cc26914b709217b2 = L.marker(
                [45.41742187, -122.6130971],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d0dd7625413741abac82b65ce5a8df55 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9e82b2613e76e740cc26914b709217b2.setIcon(icon_d0dd7625413741abac82b65ce5a8df55);
        
    
        var popup_14fe41644e3e1daa63162ac6789afa80 = L.popup({"maxWidth": "100%"});

        
            
                var html_152855c03e4da41f58e67445d32077d7 = $(`<div id="html_152855c03e4da41f58e67445d32077d7" style="width: 100.0%; height: 100.0%;">View Acres Elementary School</div>`)[0];
                popup_14fe41644e3e1daa63162ac6789afa80.setContent(html_152855c03e4da41f58e67445d32077d7);
            
        

        marker_9e82b2613e76e740cc26914b709217b2.bindPopup(popup_14fe41644e3e1daa63162ac6789afa80)
        ;

        
    
    
            var marker_1563dd6c32e5be0a84082eb9ed19188d = L.marker(
                [45.44282649, -122.5871937],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_63acdc7fa9f0d3a700b559082d698f3e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1563dd6c32e5be0a84082eb9ed19188d.setIcon(icon_63acdc7fa9f0d3a700b559082d698f3e);
        
    
        var popup_1a343fef83ab27b1bec616c1ffda74e3 = L.popup({"maxWidth": "100%"});

        
            
                var html_056ad9dbfe0eb60d01e99b1d741c60e2 = $(`<div id="html_056ad9dbfe0eb60d01e99b1d741c60e2" style="width: 100.0%; height: 100.0%;">Whitcomb Elementary School</div>`)[0];
                popup_1a343fef83ab27b1bec616c1ffda74e3.setContent(html_056ad9dbfe0eb60d01e99b1d741c60e2);
            
        

        marker_1563dd6c32e5be0a84082eb9ed19188d.bindPopup(popup_1a343fef83ab27b1bec616c1ffda74e3)
        ;

        
    
    
            var marker_2f4aa9a6982577a59825e9db17c00bb3 = L.marker(
                [45.3736649, -122.5791922],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5b94f6d2318b79912d02509ca5d73586 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2f4aa9a6982577a59825e9db17c00bb3.setIcon(icon_5b94f6d2318b79912d02509ca5d73586);
        
    
        var popup_1f17cda3bb65424b9fc8188d42b3f61c = L.popup({"maxWidth": "100%"});

        
            
                var html_f681a8dfad436d92ca4fe3be4960f871 = $(`<div id="html_f681a8dfad436d92ca4fe3be4960f871" style="width: 100.0%; height: 100.0%;">Alliance Charter Academy</div>`)[0];
                popup_1f17cda3bb65424b9fc8188d42b3f61c.setContent(html_f681a8dfad436d92ca4fe3be4960f871);
            
        

        marker_2f4aa9a6982577a59825e9db17c00bb3.bindPopup(popup_1f17cda3bb65424b9fc8188d42b3f61c)
        ;

        
    
    
            var marker_fb631ef3fbe6b331815b74e333598b99 = L.marker(
                [45.28871804, -122.5172648],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_019739bda666cd1f16bf0576c7a9a519 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fb631ef3fbe6b331815b74e333598b99.setIcon(icon_019739bda666cd1f16bf0576c7a9a519);
        
    
        var popup_368564f7fa3b4b4573cddf0488cfd711 = L.popup({"maxWidth": "100%"});

        
            
                var html_46cf9efa5271dfc392f2e5e2fe9c69c3 = $(`<div id="html_46cf9efa5271dfc392f2e5e2fe9c69c3" style="width: 100.0%; height: 100.0%;">Beavercreek Elementary School</div>`)[0];
                popup_368564f7fa3b4b4573cddf0488cfd711.setContent(html_46cf9efa5271dfc392f2e5e2fe9c69c3);
            
        

        marker_fb631ef3fbe6b331815b74e333598b99.bindPopup(popup_368564f7fa3b4b4573cddf0488cfd711)
        ;

        
    
    
            var marker_4bdf03de6ee046407639e2cc278c4318 = L.marker(
                [45.39290613, -122.6026235],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_793569253496745c4296b29920af0ac3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4bdf03de6ee046407639e2cc278c4318.setIcon(icon_793569253496745c4296b29920af0ac3);
        
    
        var popup_9bac84de152308b0448b322dd3a7be23 = L.popup({"maxWidth": "100%"});

        
            
                var html_f56e1c143b8d55fff261f4e9c1e9b1f8 = $(`<div id="html_f56e1c143b8d55fff261f4e9c1e9b1f8" style="width: 100.0%; height: 100.0%;">Candy Lane Elementary School</div>`)[0];
                popup_9bac84de152308b0448b322dd3a7be23.setContent(html_f56e1c143b8d55fff261f4e9c1e9b1f8);
            
        

        marker_4bdf03de6ee046407639e2cc278c4318.bindPopup(popup_9bac84de152308b0448b322dd3a7be23)
        ;

        
    
    
            var marker_99e81a2332054c9c8460bf61df9bfb7c = L.marker(
                [45.32520881, -122.5904601],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_65a857be4bbe7dc381c5537143d188d9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_99e81a2332054c9c8460bf61df9bfb7c.setIcon(icon_65a857be4bbe7dc381c5537143d188d9);
        
    
        var popup_7667ab1e030a6a6f5a325de4b359118a = L.popup({"maxWidth": "100%"});

        
            
                var html_fd2b873a5c20bbdbfa992c26c3721935 = $(`<div id="html_fd2b873a5c20bbdbfa992c26c3721935" style="width: 100.0%; height: 100.0%;">Gaffney Lane Elementary School</div>`)[0];
                popup_7667ab1e030a6a6f5a325de4b359118a.setContent(html_fd2b873a5c20bbdbfa992c26c3721935);
            
        

        marker_99e81a2332054c9c8460bf61df9bfb7c.bindPopup(popup_7667ab1e030a6a6f5a325de4b359118a)
        ;

        
    
    
            var marker_dd4f656f98149319010bc702538f1a14 = L.marker(
                [45.37426431, -122.5650697],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0f75ee6d555c246850373e0a09e90d2d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dd4f656f98149319010bc702538f1a14.setIcon(icon_0f75ee6d555c246850373e0a09e90d2d);
        
    
        var popup_b3b0ce6323964b208449ff9f6f7d77a4 = L.popup({"maxWidth": "100%"});

        
            
                var html_8bea90b7753949f28d24ca9ab3acb58e = $(`<div id="html_8bea90b7753949f28d24ca9ab3acb58e" style="width: 100.0%; height: 100.0%;">Holcomb Elementary School</div>`)[0];
                popup_b3b0ce6323964b208449ff9f6f7d77a4.setContent(html_8bea90b7753949f28d24ca9ab3acb58e);
            
        

        marker_dd4f656f98149319010bc702538f1a14.bindPopup(popup_b3b0ce6323964b208449ff9f6f7d77a4)
        ;

        
    
    
            var marker_701a5ffe2b3304a319e4a59afbb2786a = L.marker(
                [45.32800675, -122.6291192],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_edc0601d8aeaf86555dc133133999b35 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_701a5ffe2b3304a319e4a59afbb2786a.setIcon(icon_edc0601d8aeaf86555dc133133999b35);
        
    
        var popup_a31b338d43fa955751c3a97ab9646f26 = L.popup({"maxWidth": "100%"});

        
            
                var html_c8e5fc334aaaeb1577c49a28b5544166 = $(`<div id="html_c8e5fc334aaaeb1577c49a28b5544166" style="width: 100.0%; height: 100.0%;">John McLoughlin Elementary School</div>`)[0];
                popup_a31b338d43fa955751c3a97ab9646f26.setContent(html_c8e5fc334aaaeb1577c49a28b5544166);
            
        

        marker_701a5ffe2b3304a319e4a59afbb2786a.bindPopup(popup_a31b338d43fa955751c3a97ab9646f26)
        ;

        
    
    
            var marker_54022283d85c21f045997609dafa3c1f = L.marker(
                [45.34579662, -122.4926483],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c9f4643a9b5e80ac28dad887cb45d07b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_54022283d85c21f045997609dafa3c1f.setIcon(icon_c9f4643a9b5e80ac28dad887cb45d07b);
        
    
        var popup_dc7fd2ee0510cdf75e6fd48b90bff842 = L.popup({"maxWidth": "100%"});

        
            
                var html_b5f32d97202d049da37d1f3ca7a81e4a = $(`<div id="html_b5f32d97202d049da37d1f3ca7a81e4a" style="width: 100.0%; height: 100.0%;">Redland Elementary School</div>`)[0];
                popup_dc7fd2ee0510cdf75e6fd48b90bff842.setContent(html_b5f32d97202d049da37d1f3ca7a81e4a);
            
        

        marker_54022283d85c21f045997609dafa3c1f.bindPopup(popup_dc7fd2ee0510cdf75e6fd48b90bff842)
        ;

        
    
    
            var marker_48b267c856cd8a4a9f1721090ac1d0c2 = L.marker(
                [45.366795, -122.4667886],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e41d8bbf65a56dcc93fd86a5fef1dccb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_48b267c856cd8a4a9f1721090ac1d0c2.setIcon(icon_e41d8bbf65a56dcc93fd86a5fef1dccb);
        
    
        var popup_ebd875168709cb7c9c02e837e1c611bb = L.popup({"maxWidth": "100%"});

        
            
                var html_a379a7f399813b95492f533b6c97c335 = $(`<div id="html_a379a7f399813b95492f533b6c97c335" style="width: 100.0%; height: 100.0%;">Springwater Environmental Sciences School</div>`)[0];
                popup_ebd875168709cb7c9c02e837e1c611bb.setContent(html_a379a7f399813b95492f533b6c97c335);
            
        

        marker_48b267c856cd8a4a9f1721090ac1d0c2.bindPopup(popup_ebd875168709cb7c9c02e837e1c611bb)
        ;

        
    
    
            var marker_dfe19d7981f40b7b563de0cf51c40bc0 = L.marker(
                [45.55509049, -122.5556919],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a1ec111ec15b68ebca8a34bd2845dda9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dfe19d7981f40b7b563de0cf51c40bc0.setIcon(icon_a1ec111ec15b68ebca8a34bd2845dda9);
        
    
        var popup_89d19d20d4f5800f5cc01bb0ac6c6657 = L.popup({"maxWidth": "100%"});

        
            
                var html_02c3cb83ab8faa013a034430deae6be2 = $(`<div id="html_02c3cb83ab8faa013a034430deae6be2" style="width: 100.0%; height: 100.0%;">Prescott Elementary School</div>`)[0];
                popup_89d19d20d4f5800f5cc01bb0ac6c6657.setContent(html_02c3cb83ab8faa013a034430deae6be2);
            
        

        marker_dfe19d7981f40b7b563de0cf51c40bc0.bindPopup(popup_89d19d20d4f5800f5cc01bb0ac6c6657)
        ;

        
    
    
            var marker_803c6995f234d20ed4711f44f0ab3fea = L.marker(
                [45.54156148, -122.5312506],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_0160b3617387dcda54b22793e924b693 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_803c6995f234d20ed4711f44f0ab3fea.setIcon(icon_0160b3617387dcda54b22793e924b693);
        
    
        var popup_21f281c38a7ca01c274c14184a609e33 = L.popup({"maxWidth": "100%"});

        
            
                var html_78d762513ef6ee786f0413438b40a4e5 = $(`<div id="html_78d762513ef6ee786f0413438b40a4e5" style="width: 100.0%; height: 100.0%;">Russell Elementary</div>`)[0];
                popup_21f281c38a7ca01c274c14184a609e33.setContent(html_78d762513ef6ee786f0413438b40a4e5);
            
        

        marker_803c6995f234d20ed4711f44f0ab3fea.bindPopup(popup_21f281c38a7ca01c274c14184a609e33)
        ;

        
    
    
            var marker_c4e344e05c132940acb8a78c0324ebc7 = L.marker(
                [45.53906429, -122.545038],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_4f93efafa15769702290dcb8d210fe1c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c4e344e05c132940acb8a78c0324ebc7.setIcon(icon_4f93efafa15769702290dcb8d210fe1c);
        
    
        var popup_1bb660cf92a01cb8ca32263f308a4213 = L.popup({"maxWidth": "100%"});

        
            
                var html_af40d46ce397c657fcbc0ea46792a723 = $(`<div id="html_af40d46ce397c657fcbc0ea46792a723" style="width: 100.0%; height: 100.0%;">Sacramento Elementary School</div>`)[0];
                popup_1bb660cf92a01cb8ca32263f308a4213.setContent(html_af40d46ce397c657fcbc0ea46792a723);
            
        

        marker_c4e344e05c132940acb8a78c0324ebc7.bindPopup(popup_1bb660cf92a01cb8ca32263f308a4213)
        ;

        
    
    
            var marker_2f8690924162f94df512413dde865acb = L.marker(
                [45.54948038, -122.5284678],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_95ed94cbb5ae30a60e788865ac5f8a13 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2f8690924162f94df512413dde865acb.setIcon(icon_95ed94cbb5ae30a60e788865ac5f8a13);
        
    
        var popup_0cc7e1066ef0698759113f5049013496 = L.popup({"maxWidth": "100%"});

        
            
                var html_c4a6d3e67707539e11a03fff3c916947 = $(`<div id="html_c4a6d3e67707539e11a03fff3c916947" style="width: 100.0%; height: 100.0%;">Shaver Elementary School</div>`)[0];
                popup_0cc7e1066ef0698759113f5049013496.setContent(html_c4a6d3e67707539e11a03fff3c916947);
            
        

        marker_2f8690924162f94df512413dde865acb.bindPopup(popup_0cc7e1066ef0698759113f5049013496)
        ;

        
    
    
            var marker_0bad41ff76184235eb4bb6a723333734 = L.marker(
                [45.50585959, -122.651415],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1c4fa2d2ef1e32005d5fd3c5e82812ef = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0bad41ff76184235eb4bb6a723333734.setIcon(icon_1c4fa2d2ef1e32005d5fd3c5e82812ef);
        
    
        var popup_5df19f0dcaf8aa2ccd93d74c40b3f4bf = L.popup({"maxWidth": "100%"});

        
            
                var html_74709d3692d92561cbcb4461c6267c4c = $(`<div id="html_74709d3692d92561cbcb4461c6267c4c" style="width: 100.0%; height: 100.0%;">Abernethy Elementary School</div>`)[0];
                popup_5df19f0dcaf8aa2ccd93d74c40b3f4bf.setContent(html_74709d3692d92561cbcb4461c6267c4c);
            
        

        marker_0bad41ff76184235eb4bb6a723333734.bindPopup(popup_5df19f0dcaf8aa2ccd93d74c40b3f4bf)
        ;

        
    
    
            var marker_6627f0cd5d828ea90124f387ffc2ed51 = L.marker(
                [45.50977832, -122.6996227],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7ae2f7abe61c4f1cb3acfe8c37664a89 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6627f0cd5d828ea90124f387ffc2ed51.setIcon(icon_7ae2f7abe61c4f1cb3acfe8c37664a89);
        
    
        var popup_7a7bc58d6b103892a6133a352dd74687 = L.popup({"maxWidth": "100%"});

        
            
                var html_de499de72aeb9f050bae4c02bd9217bc = $(`<div id="html_de499de72aeb9f050bae4c02bd9217bc" style="width: 100.0%; height: 100.0%;">Ainsworth Elementary School</div>`)[0];
                popup_7a7bc58d6b103892a6133a352dd74687.setContent(html_de499de72aeb9f050bae4c02bd9217bc);
            
        

        marker_6627f0cd5d828ea90124f387ffc2ed51.bindPopup(popup_7a7bc58d6b103892a6133a352dd74687)
        ;

        
    
    
            var marker_46ad5a8260d047423d8af60ec36a6529 = L.marker(
                [45.54784453, -122.6373535],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_814326321cb1ba35d9c3348832fb3e1f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_46ad5a8260d047423d8af60ec36a6529.setIcon(icon_814326321cb1ba35d9c3348832fb3e1f);
        
    
        var popup_74260df9fe4d728dee69c212b92cd8de = L.popup({"maxWidth": "100%"});

        
            
                var html_f94d3d2ede6a1b2ce63c1389001278bd = $(`<div id="html_f94d3d2ede6a1b2ce63c1389001278bd" style="width: 100.0%; height: 100.0%;">Alameda Elementary School</div>`)[0];
                popup_74260df9fe4d728dee69c212b92cd8de.setContent(html_f94d3d2ede6a1b2ce63c1389001278bd);
            
        

        marker_46ad5a8260d047423d8af60ec36a6529.bindPopup(popup_74260df9fe4d728dee69c212b92cd8de)
        ;

        
    
    
            var marker_68b55049761f6f8fde91cdc8265b4e27 = L.marker(
                [45.48623431, -122.5962865],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_57671ec99a800ccb78330130de4a6196 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_68b55049761f6f8fde91cdc8265b4e27.setIcon(icon_57671ec99a800ccb78330130de4a6196);
        
    
        var popup_9650ee78840479c259dc1d46cb8a4340 = L.popup({"maxWidth": "100%"});

        
            
                var html_5fe18ef86393a19633c1488b3322ed33 = $(`<div id="html_5fe18ef86393a19633c1488b3322ed33" style="width: 100.0%; height: 100.0%;">Arleta Elementary School</div>`)[0];
                popup_9650ee78840479c259dc1d46cb8a4340.setContent(html_5fe18ef86393a19633c1488b3322ed33);
            
        

        marker_68b55049761f6f8fde91cdc8265b4e27.bindPopup(popup_9650ee78840479c259dc1d46cb8a4340)
        ;

        
    
    
            var marker_7d16775b3fb2dffca4177dc77faf503f = L.marker(
                [45.57868395, -122.7297055],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_85eb3bdb6f86755f4fcd85475fb0f490 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7d16775b3fb2dffca4177dc77faf503f.setIcon(icon_85eb3bdb6f86755f4fcd85475fb0f490);
        
    
        var popup_22c174cece8aebc9c80e4e6276eb362f = L.popup({"maxWidth": "100%"});

        
            
                var html_2e8d676988e9e50de0bd8e5704eb607f = $(`<div id="html_2e8d676988e9e50de0bd8e5704eb607f" style="width: 100.0%; height: 100.0%;">Astor Elementary School</div>`)[0];
                popup_22c174cece8aebc9c80e4e6276eb362f.setContent(html_2e8d676988e9e50de0bd8e5704eb607f);
            
        

        marker_7d16775b3fb2dffca4177dc77faf503f.bindPopup(popup_22c174cece8aebc9c80e4e6276eb362f)
        ;

        
    
    
            var marker_bfc2dd3f176fb8025f789a3249bdb956 = L.marker(
                [45.50504853, -122.6046734],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_ef131a49c12b39b49b4abdf7215b6030 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_bfc2dd3f176fb8025f789a3249bdb956.setIcon(icon_ef131a49c12b39b49b4abdf7215b6030);
        
    
        var popup_f02c0607ee11f4efeb572e7ca9011c78 = L.popup({"maxWidth": "100%"});

        
            
                var html_100a3c952c454244296e0759bc2d4b67 = $(`<div id="html_100a3c952c454244296e0759bc2d4b67" style="width: 100.0%; height: 100.0%;">Atkinson Elementary School</div>`)[0];
                popup_f02c0607ee11f4efeb572e7ca9011c78.setContent(html_100a3c952c454244296e0759bc2d4b67);
            
        

        marker_bfc2dd3f176fb8025f789a3249bdb956.bindPopup(popup_f02c0607ee11f4efeb572e7ca9011c78)
        ;

        
    
    
            var marker_2fc51c13343299637588ccec375d5a54 = L.marker(
                [45.55814909, -122.6855778],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_466941f65a0641eb0ed85a415cccbd0d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2fc51c13343299637588ccec375d5a54.setIcon(icon_466941f65a0641eb0ed85a415cccbd0d);
        
    
        var popup_ff19cf9b2515ff1f23f04ef9d9808249 = L.popup({"maxWidth": "100%"});

        
            
                var html_0a507b283b7cec3bbd95c053abf0ddc9 = $(`<div id="html_0a507b283b7cec3bbd95c053abf0ddc9" style="width: 100.0%; height: 100.0%;">Beach Elementary School</div>`)[0];
                popup_ff19cf9b2515ff1f23f04ef9d9808249.setContent(html_0a507b283b7cec3bbd95c053abf0ddc9);
            
        

        marker_2fc51c13343299637588ccec375d5a54.bindPopup(popup_ff19cf9b2515ff1f23f04ef9d9808249)
        ;

        
    
    
            var marker_80e9f6d63b245dfd692b4f27c01ebb16 = L.marker(
                [45.53697597, -122.6311032],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_56eb8ca47b5ab8676121d07f40fb0bc1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_80e9f6d63b245dfd692b4f27c01ebb16.setIcon(icon_56eb8ca47b5ab8676121d07f40fb0bc1);
        
    
        var popup_ed18410b7c95348e739efda29844545d = L.popup({"maxWidth": "100%"});

        
            
                var html_903b35904a1c678654cb551e81e849c0 = $(`<div id="html_903b35904a1c678654cb551e81e849c0" style="width: 100.0%; height: 100.0%;">Beverly Cleary School - Fernwood Campus</div>`)[0];
                popup_ed18410b7c95348e739efda29844545d.setContent(html_903b35904a1c678654cb551e81e849c0);
            
        

        marker_80e9f6d63b245dfd692b4f27c01ebb16.bindPopup(popup_ed18410b7c95348e739efda29844545d)
        ;

        
    
    
            var marker_402ebb3fef21a1821093db52b8ed5121 = L.marker(
                [45.54120712, -122.6270411],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b500e4e849709e715f6fa1445ab044b9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_402ebb3fef21a1821093db52b8ed5121.setIcon(icon_b500e4e849709e715f6fa1445ab044b9);
        
    
        var popup_d5f872c0c3ad91d11c965117884f030c = L.popup({"maxWidth": "100%"});

        
            
                var html_71a715694d2656f7fec4473be57f5386 = $(`<div id="html_71a715694d2656f7fec4473be57f5386" style="width: 100.0%; height: 100.0%;">Beverly Cleary School - Hollyrood Campus</div>`)[0];
                popup_d5f872c0c3ad91d11c965117884f030c.setContent(html_71a715694d2656f7fec4473be57f5386);
            
        

        marker_402ebb3fef21a1821093db52b8ed5121.bindPopup(popup_d5f872c0c3ad91d11c965117884f030c)
        ;

        
    
    
            var marker_5d4af0c48016c5165f5474b9da492dde = L.marker(
                [45.54787053, -122.6728242],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1d8a3eb5f475f0d54ae1b775281aa4ac = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5d4af0c48016c5165f5474b9da492dde.setIcon(icon_1d8a3eb5f475f0d54ae1b775281aa4ac);
        
    
        var popup_fa2c09a7bbaf444345f1452934dadac0 = L.popup({"maxWidth": "100%"});

        
            
                var html_02282f43f3bf2c990ea81d956ade586c = $(`<div id="html_02282f43f3bf2c990ea81d956ade586c" style="width: 100.0%; height: 100.0%;">Boise-Eliot Elementary School</div>`)[0];
                popup_fa2c09a7bbaf444345f1452934dadac0.setContent(html_02282f43f3bf2c990ea81d956ade586c);
            
        

        marker_5d4af0c48016c5165f5474b9da492dde.bindPopup(popup_fa2c09a7bbaf444345f1452934dadac0)
        ;

        
    
    
            var marker_e8834358ddd95de17479fe84c7f783cb = L.marker(
                [45.51058304, -122.5821348],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5b01e076c703e3c94610d89b86c58e92 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_e8834358ddd95de17479fe84c7f783cb.setIcon(icon_5b01e076c703e3c94610d89b86c58e92);
        
    
        var popup_9fe0a9bc8e1e1e7c96a6244bc039ed8d = L.popup({"maxWidth": "100%"});

        
            
                var html_c702294b9ae00a07f9e92f4f1f83ca8b = $(`<div id="html_c702294b9ae00a07f9e92f4f1f83ca8b" style="width: 100.0%; height: 100.0%;">Bridger Elementary School</div>`)[0];
                popup_9fe0a9bc8e1e1e7c96a6244bc039ed8d.setContent(html_c702294b9ae00a07f9e92f4f1f83ca8b);
            
        

        marker_e8834358ddd95de17479fe84c7f783cb.bindPopup(popup_9fe0a9bc8e1e1e7c96a6244bc039ed8d)
        ;

        
    
    
            var marker_52d31bcd503b354b5fccd6363409a4fb = L.marker(
                [45.49192405, -122.7243893],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7a9a510b6fc77480f56395c1b3b11dae = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_52d31bcd503b354b5fccd6363409a4fb.setIcon(icon_7a9a510b6fc77480f56395c1b3b11dae);
        
    
        var popup_396c2494197f9b95e30f2ca02f03c9b0 = L.popup({"maxWidth": "100%"});

        
            
                var html_bc96c1c7cc7a79d8df3a9d344f541023 = $(`<div id="html_bc96c1c7cc7a79d8df3a9d344f541023" style="width: 100.0%; height: 100.0%;">Bridlemile Elementary School</div>`)[0];
                popup_396c2494197f9b95e30f2ca02f03c9b0.setContent(html_bc96c1c7cc7a79d8df3a9d344f541023);
            
        

        marker_52d31bcd503b354b5fccd6363409a4fb.bindPopup(popup_396c2494197f9b95e30f2ca02f03c9b0)
        ;

        
    
    
            var marker_432a0bc5569f6bf571648f2f871b6784 = L.marker(
                [45.52045329, -122.648732],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3b7a32f43be8f3d269577f7aa4445de9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_432a0bc5569f6bf571648f2f871b6784.setIcon(icon_3b7a32f43be8f3d269577f7aa4445de9);
        
    
        var popup_0d74b3ca45212202a00bb8c3f5bb9a93 = L.popup({"maxWidth": "100%"});

        
            
                var html_cfd7ec85ecf0c29a6117795c00b1442a = $(`<div id="html_cfd7ec85ecf0c29a6117795c00b1442a" style="width: 100.0%; height: 100.0%;">Buckman Elementary School</div>`)[0];
                popup_0d74b3ca45212202a00bb8c3f5bb9a93.setContent(html_cfd7ec85ecf0c29a6117795c00b1442a);
            
        

        marker_432a0bc5569f6bf571648f2f871b6784.bindPopup(popup_0d74b3ca45212202a00bb8c3f5bb9a93)
        ;

        
    
    
            var marker_7dd9293469e8d1e327f96e5f7ef2d9e0 = L.marker(
                [45.46431146, -122.6955237],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_35bfc0997ceea1cd8c8db220d9ea4138 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7dd9293469e8d1e327f96e5f7ef2d9e0.setIcon(icon_35bfc0997ceea1cd8c8db220d9ea4138);
        
    
        var popup_92bffedad2fbcf1e76c491bd90a90508 = L.popup({"maxWidth": "100%"});

        
            
                var html_5f0fa930794122305c9791fae3929ac8 = $(`<div id="html_5f0fa930794122305c9791fae3929ac8" style="width: 100.0%; height: 100.0%;">Capitol Hill Elementary School</div>`)[0];
                popup_92bffedad2fbcf1e76c491bd90a90508.setContent(html_5f0fa930794122305c9791fae3929ac8);
            
        

        marker_7dd9293469e8d1e327f96e5f7ef2d9e0.bindPopup(popup_92bffedad2fbcf1e76c491bd90a90508)
        ;

        
    
    
            var marker_7564faf1153e88f17112381787b6ea98 = L.marker(
                [45.58452159, -122.7194393],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b3fc43edb9293624d5afaebc1eabebbd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7564faf1153e88f17112381787b6ea98.setIcon(icon_b3fc43edb9293624d5afaebc1eabebbd);
        
    
        var popup_831ee38a746635033ead2a424049e431 = L.popup({"maxWidth": "100%"});

        
            
                var html_167235daed7ec314f5ce6c34934d347c = $(`<div id="html_167235daed7ec314f5ce6c34934d347c" style="width: 100.0%; height: 100.0%;">Cesar Chavez K-8 School</div>`)[0];
                popup_831ee38a746635033ead2a424049e431.setContent(html_167235daed7ec314f5ce6c34934d347c);
            
        

        marker_7564faf1153e88f17112381787b6ea98.bindPopup(popup_831ee38a746635033ead2a424049e431)
        ;

        
    
    
            var marker_85183ff76e3c9a02496d1bb6af546bbe = L.marker(
                [45.53321866, -122.7055948],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d4c5889467ba600d4bcde6212654a802 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_85183ff76e3c9a02496d1bb6af546bbe.setIcon(icon_d4c5889467ba600d4bcde6212654a802);
        
    
        var popup_e597b845590ab2843441e3fb8a36151a = L.popup({"maxWidth": "100%"});

        
            
                var html_e31e7f8566cdf8f53124d9b57c6f2f31 = $(`<div id="html_e31e7f8566cdf8f53124d9b57c6f2f31" style="width: 100.0%; height: 100.0%;">Chapman Elementary School</div>`)[0];
                popup_e597b845590ab2843441e3fb8a36151a.setContent(html_e31e7f8566cdf8f53124d9b57c6f2f31);
            
        

        marker_85183ff76e3c9a02496d1bb6af546bbe.bindPopup(popup_e597b845590ab2843441e3fb8a36151a)
        ;

        
    
    
            var marker_9e1c501f6cc8eb76cac3394056fcc9cf = L.marker(
                [45.57292305, -122.6913712],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_98171300af322df9648f9fcf5b2339ea = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9e1c501f6cc8eb76cac3394056fcc9cf.setIcon(icon_98171300af322df9648f9fcf5b2339ea);
        
    
        var popup_f3074c9bd304a45a5d7bb98fffc80349 = L.popup({"maxWidth": "100%"});

        
            
                var html_602dfae259b7595ad1b9ba06ec023055 = $(`<div id="html_602dfae259b7595ad1b9ba06ec023055" style="width: 100.0%; height: 100.0%;">Chief Joseph Elementary School</div>`)[0];
                popup_f3074c9bd304a45a5d7bb98fffc80349.setContent(html_602dfae259b7595ad1b9ba06ec023055);
            
        

        marker_9e1c501f6cc8eb76cac3394056fcc9cf.bindPopup(popup_f3074c9bd304a45a5d7bb98fffc80349)
        ;

        
    
    
            var marker_3b359f6d8b492d3c3f748de5228534d9 = L.marker(
                [45.49544972, -122.6138523],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3c0159bd67af0af7d6c7e8c450e9accf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_3b359f6d8b492d3c3f748de5228534d9.setIcon(icon_3c0159bd67af0af7d6c7e8c450e9accf);
        
    
        var popup_2b011563601bdf25f50507ba5306705c = L.popup({"maxWidth": "100%"});

        
            
                var html_db40a9c69009c6a54c1f4f846ed03af2 = $(`<div id="html_db40a9c69009c6a54c1f4f846ed03af2" style="width: 100.0%; height: 100.0%;">Creston Elementary School</div>`)[0];
                popup_2b011563601bdf25f50507ba5306705c.setContent(html_db40a9c69009c6a54c1f4f846ed03af2);
            
        

        marker_3b359f6d8b492d3c3f748de5228534d9.bindPopup(popup_2b011563601bdf25f50507ba5306705c)
        ;

        
    
    
            var marker_defc2ebd5a4b51c5eba3b2c2a9103c3a = L.marker(
                [45.46850676, -122.6289892],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e615ec607bc0f88b4eae4cf83c069ec9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_defc2ebd5a4b51c5eba3b2c2a9103c3a.setIcon(icon_e615ec607bc0f88b4eae4cf83c069ec9);
        
    
        var popup_3415ccc011df678b66c4f7255bf6da3a = L.popup({"maxWidth": "100%"});

        
            
                var html_a6810166808568f7782f278daa2cbc43 = $(`<div id="html_a6810166808568f7782f278daa2cbc43" style="width: 100.0%; height: 100.0%;">Duniway Elementary School</div>`)[0];
                popup_3415ccc011df678b66c4f7255bf6da3a.setContent(html_a6810166808568f7782f278daa2cbc43);
            
        

        marker_defc2ebd5a4b51c5eba3b2c2a9103c3a.bindPopup(popup_3415ccc011df678b66c4f7255bf6da3a)
        ;

        
    
    
            var marker_45c600778291528ca0cd92c5c0db32cc = L.marker(
                [45.5239598, -122.6794341],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5ac5d90c60c24b31bae2baa442c28e3e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_45c600778291528ca0cd92c5c0db32cc.setIcon(icon_5ac5d90c60c24b31bae2baa442c28e3e);
        
    
        var popup_b6b916b4b4adb166df7fc4a9cd93891d = L.popup({"maxWidth": "100%"});

        
            
                var html_d868ad71180e98af4eeb1a4543822a2b = $(`<div id="html_d868ad71180e98af4eeb1a4543822a2b" style="width: 100.0%; height: 100.0%;">Emerson School</div>`)[0];
                popup_b6b916b4b4adb166df7fc4a9cd93891d.setContent(html_d868ad71180e98af4eeb1a4543822a2b);
            
        

        marker_45c600778291528ca0cd92c5c0db32cc.bindPopup(popup_b6b916b4b4adb166df7fc4a9cd93891d)
        ;

        
    
    
            var marker_1e987bdae342baac73e74aa3e32afc42 = L.marker(
                [45.57067045, -122.6344628],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_104fff30694c8b77eca05199159b882c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1e987bdae342baac73e74aa3e32afc42.setIcon(icon_104fff30694c8b77eca05199159b882c);
        
    
        var popup_36abdba8019f692acdb87f5da1a7c8b1 = L.popup({"maxWidth": "100%"});

        
            
                var html_afb9980a1f7967f5537e17e920a30cff = $(`<div id="html_afb9980a1f7967f5537e17e920a30cff" style="width: 100.0%; height: 100.0%;">Faubion Elementary School</div>`)[0];
                popup_36abdba8019f692acdb87f5da1a7c8b1.setContent(html_afb9980a1f7967f5537e17e920a30cff);
            
        

        marker_1e987bdae342baac73e74aa3e32afc42.bindPopup(popup_36abdba8019f692acdb87f5da1a7c8b1)
        ;

        
    
    
            var marker_f3c13bdf9acf3ea0fd290669c40b07a5 = L.marker(
                [45.54250677, -122.7777667],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d9b11d50362ef126306289dede8e8968 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f3c13bdf9acf3ea0fd290669c40b07a5.setIcon(icon_d9b11d50362ef126306289dede8e8968);
        
    
        var popup_021ccedc969017807cab09a259d8d0bc = L.popup({"maxWidth": "100%"});

        
            
                var html_2c95dfae75eea9acf2e11027e03a6ace = $(`<div id="html_2c95dfae75eea9acf2e11027e03a6ace" style="width: 100.0%; height: 100.0%;">Forest Park Elementary School</div>`)[0];
                popup_021ccedc969017807cab09a259d8d0bc.setContent(html_2c95dfae75eea9acf2e11027e03a6ace);
            
        

        marker_f3c13bdf9acf3ea0fd290669c40b07a5.bindPopup(popup_021ccedc969017807cab09a259d8d0bc)
        ;

        
    
    
            var marker_1b3e6e1f00012647ee19bb2ddd596daf = L.marker(
                [45.5171951, -122.6107926],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7be938df1ac6849f45673d4c2676a758 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1b3e6e1f00012647ee19bb2ddd596daf.setIcon(icon_7be938df1ac6849f45673d4c2676a758);
        
    
        var popup_069a2e1f3a2a914de53970f5b31c547c = L.popup({"maxWidth": "100%"});

        
            
                var html_edc620b1ad9f8e8bd641e34f574b2b3f = $(`<div id="html_edc620b1ad9f8e8bd641e34f574b2b3f" style="width: 100.0%; height: 100.0%;">Glencoe Elementary School</div>`)[0];
                popup_069a2e1f3a2a914de53970f5b31c547c.setContent(html_edc620b1ad9f8e8bd641e34f574b2b3f);
            
        

        marker_1b3e6e1f00012647ee19bb2ddd596daf.bindPopup(popup_069a2e1f3a2a914de53970f5b31c547c)
        ;

        
    
    
            var marker_670ef97f0eb667cd16059aabbceb599f = L.marker(
                [45.4908968, -122.6332967],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e1ed3b792401d40fe8c11a75eb8b8bf8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_670ef97f0eb667cd16059aabbceb599f.setIcon(icon_e1ed3b792401d40fe8c11a75eb8b8bf8);
        
    
        var popup_c389c59417a92542db89534c7a5b54b0 = L.popup({"maxWidth": "100%"});

        
            
                var html_98f90d79a9f4912753b0888110964f8a = $(`<div id="html_98f90d79a9f4912753b0888110964f8a" style="width: 100.0%; height: 100.0%;">Grout Elementary School</div>`)[0];
                popup_c389c59417a92542db89534c7a5b54b0.setContent(html_98f90d79a9f4912753b0888110964f8a);
            
        

        marker_670ef97f0eb667cd16059aabbceb599f.bindPopup(popup_c389c59417a92542db89534c7a5b54b0)
        ;

        
    
    
            var marker_f9e6bd9df0e99949dcb0880230935825 = L.marker(
                [45.50679641, -122.5749987],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_50919418e230ad524655663f9dd6dfc9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f9e6bd9df0e99949dcb0880230935825.setIcon(icon_50919418e230ad524655663f9dd6dfc9);
        
    
        var popup_b1de30d58f6d626371cbec5cab5bfbe9 = L.popup({"maxWidth": "100%"});

        
            
                var html_47a291e229ddecba29125e200973a7ef = $(`<div id="html_47a291e229ddecba29125e200973a7ef" style="width: 100.0%; height: 100.0%;">Harrison Park School</div>`)[0];
                popup_b1de30d58f6d626371cbec5cab5bfbe9.setContent(html_47a291e229ddecba29125e200973a7ef);
            
        

        marker_f9e6bd9df0e99949dcb0880230935825.bindPopup(popup_b1de30d58f6d626371cbec5cab5bfbe9)
        ;

        
    
    
            var marker_2ef8ec705c3d0142289a94133be10e02 = L.marker(
                [45.48032605, -122.7290127],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_9b455cac1f20696453e849e7f7fb9f89 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2ef8ec705c3d0142289a94133be10e02.setIcon(icon_9b455cac1f20696453e849e7f7fb9f89);
        
    
        var popup_09efcf270b1072b9bcdc94d8e0a05621 = L.popup({"maxWidth": "100%"});

        
            
                var html_4b9bb1e59b833ebe967f04f0e52fdb1a = $(`<div id="html_4b9bb1e59b833ebe967f04f0e52fdb1a" style="width: 100.0%; height: 100.0%;">Hayhurst Elementary School</div>`)[0];
                popup_09efcf270b1072b9bcdc94d8e0a05621.setContent(html_4b9bb1e59b833ebe967f04f0e52fdb1a);
            
        

        marker_2ef8ec705c3d0142289a94133be10e02.bindPopup(popup_09efcf270b1072b9bcdc94d8e0a05621)
        ;

        
    
    
            var marker_4d9f0a0a36a0730c6a10017d32771f6f = L.marker(
                [45.54021375, -122.6520852],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_2bc8eb1123b99985844923aaf02baad3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4d9f0a0a36a0730c6a10017d32771f6f.setIcon(icon_2bc8eb1123b99985844923aaf02baad3);
        
    
        var popup_4545d8d360ba02439a3cc269af200bad = L.popup({"maxWidth": "100%"});

        
            
                var html_c07458fb3239124190926adcd05366d4 = $(`<div id="html_c07458fb3239124190926adcd05366d4" style="width: 100.0%; height: 100.0%;">Irvington Elementary School</div>`)[0];
                popup_4545d8d360ba02439a3cc269af200bad.setContent(html_c07458fb3239124190926adcd05366d4);
            
        

        marker_4d9f0a0a36a0730c6a10017d32771f6f.bindPopup(popup_4545d8d360ba02439a3cc269af200bad)
        ;

        
    
    
            var marker_478c4ffb907bfc780f6a6c791bfea8b0 = L.marker(
                [45.59043174, -122.7519522],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_57259b4b2aee515d4209bdb21225a9b9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_478c4ffb907bfc780f6a6c791bfea8b0.setIcon(icon_57259b4b2aee515d4209bdb21225a9b9);
        
    
        var popup_c88f7dfdfe04edad32cda69b6028f3c2 = L.popup({"maxWidth": "100%"});

        
            
                var html_b5a1f2e980a45d759c240c2e5ad30752 = $(`<div id="html_b5a1f2e980a45d759c240c2e5ad30752" style="width: 100.0%; height: 100.0%;">James John Elementary School</div>`)[0];
                popup_c88f7dfdfe04edad32cda69b6028f3c2.setContent(html_b5a1f2e980a45d759c240c2e5ad30752);
            
        

        marker_478c4ffb907bfc780f6a6c791bfea8b0.bindPopup(popup_c88f7dfdfe04edad32cda69b6028f3c2)
        ;

        
    
    
            var marker_5e5564dbf8940d0ad5bc0e0b42f8a9d4 = L.marker(
                [45.54927547, -122.6672984],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_dde37ff105c2812ecbf491af05ae52a7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5e5564dbf8940d0ad5bc0e0b42f8a9d4.setIcon(icon_dde37ff105c2812ecbf491af05ae52a7);
        
    
        var popup_d084c41b4f325c5ee555dfe3d4258082 = L.popup({"maxWidth": "100%"});

        
            
                var html_d208976f3c682ebe711e5118399a6f9d = $(`<div id="html_d208976f3c682ebe711e5118399a6f9d" style="width: 100.0%; height: 100.0%;">Kairos PDX</div>`)[0];
                popup_d084c41b4f325c5ee555dfe3d4258082.setContent(html_d208976f3c682ebe711e5118399a6f9d);
            
        

        marker_5e5564dbf8940d0ad5bc0e0b42f8a9d4.bindPopup(popup_d084c41b4f325c5ee555dfe3d4258082)
        ;

        
    
    
            var marker_7b71d5e877ea81363187d88dd41ecc63 = L.marker(
                [45.47294097, -122.570384],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_fe80377f06898ba16df78223b2fe3590 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_7b71d5e877ea81363187d88dd41ecc63.setIcon(icon_fe80377f06898ba16df78223b2fe3590);
        
    
        var popup_2dd50808d5ee89b266be471c0730bfa5 = L.popup({"maxWidth": "100%"});

        
            
                var html_83d311a0b9122c0b2cd678bbd31d83f0 = $(`<div id="html_83d311a0b9122c0b2cd678bbd31d83f0" style="width: 100.0%; height: 100.0%;">Kelly Elementary School</div>`)[0];
                popup_2dd50808d5ee89b266be471c0730bfa5.setContent(html_83d311a0b9122c0b2cd678bbd31d83f0);
            
        

        marker_7b71d5e877ea81363187d88dd41ecc63.bindPopup(popup_2dd50808d5ee89b266be471c0730bfa5)
        ;

        
    
    
            var marker_d652d361453910cfa6bdcaf30120f8a2 = L.marker(
                [45.52913741, -122.6198661],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_9f3f217e85a2184995a0fa11e4755e8f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d652d361453910cfa6bdcaf30120f8a2.setIcon(icon_9f3f217e85a2184995a0fa11e4755e8f);
        
    
        var popup_cc661b78ab67c05d47132d458158851c = L.popup({"maxWidth": "100%"});

        
            
                var html_bd3e33f9cee73a7a6b4fe54e8580a062 = $(`<div id="html_bd3e33f9cee73a7a6b4fe54e8580a062" style="width: 100.0%; height: 100.0%;">Laurelhurst Elementary School</div>`)[0];
                popup_cc661b78ab67c05d47132d458158851c.setContent(html_bd3e33f9cee73a7a6b4fe54e8580a062);
            
        

        marker_d652d361453910cfa6bdcaf30120f8a2.bindPopup(popup_cc661b78ab67c05d47132d458158851c)
        ;

        
    
    
            var marker_c8429c6204dd08687255fc29ba1f6401 = L.marker(
                [45.5225865, -122.6446072],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d1d48ba6e7e1a4cfb31f50a5612396f8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c8429c6204dd08687255fc29ba1f6401.setIcon(icon_d1d48ba6e7e1a4cfb31f50a5612396f8);
        
    
        var popup_2028576396763c65fe70e70b5067435e = L.popup({"maxWidth": "100%"});

        
            
                var html_06184dcf7fed62a60d8b94b3c6e89f13 = $(`<div id="html_06184dcf7fed62a60d8b94b3c6e89f13" style="width: 100.0%; height: 100.0%;">Le Monde French Immersion Public Charter School</div>`)[0];
                popup_2028576396763c65fe70e70b5067435e.setContent(html_06184dcf7fed62a60d8b94b3c6e89f13);
            
        

        marker_c8429c6204dd08687255fc29ba1f6401.bindPopup(popup_2028576396763c65fe70e70b5067435e)
        ;

        
    
    
            var marker_0aa18b1fa440cc32aeefd2b18afd3e14 = L.marker(
                [45.53812869, -122.5676603],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_868872adb6b4c8eb94be28b205782ff5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0aa18b1fa440cc32aeefd2b18afd3e14.setIcon(icon_868872adb6b4c8eb94be28b205782ff5);
        
    
        var popup_28ffe61f3b71da79d47d12646fe359a7 = L.popup({"maxWidth": "100%"});

        
            
                var html_2db2b9739eb84dd6733ae02bc299a46f = $(`<div id="html_2db2b9739eb84dd6733ae02bc299a46f" style="width: 100.0%; height: 100.0%;">Lee Elementary School</div>`)[0];
                popup_28ffe61f3b71da79d47d12646fe359a7.setContent(html_2db2b9739eb84dd6733ae02bc299a46f);
            
        

        marker_0aa18b1fa440cc32aeefd2b18afd3e14.bindPopup(popup_28ffe61f3b71da79d47d12646fe359a7)
        ;

        
    
    
            var marker_fdd51f2d361c91e9b0d3bd8c71dc1dd8 = L.marker(
                [45.48532513, -122.5641959],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_843d034b6e2e42d443a06b14570bcfd4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_fdd51f2d361c91e9b0d3bd8c71dc1dd8.setIcon(icon_843d034b6e2e42d443a06b14570bcfd4);
        
    
        var popup_a28ef9336455c6362c85c585ea1c8bd4 = L.popup({"maxWidth": "100%"});

        
            
                var html_c34fdb2b2d32319692dce3f38bb26eee = $(`<div id="html_c34fdb2b2d32319692dce3f38bb26eee" style="width: 100.0%; height: 100.0%;">Lent Elementary School</div>`)[0];
                popup_a28ef9336455c6362c85c585ea1c8bd4.setContent(html_c34fdb2b2d32319692dce3f38bb26eee);
            
        

        marker_fdd51f2d361c91e9b0d3bd8c71dc1dd8.bindPopup(popup_a28ef9336455c6362c85c585ea1c8bd4)
        ;

        
    
    
            var marker_db93ff24728c6fc6b9fb4a85afdfde84 = L.marker(
                [45.47370035, -122.6179662],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_12fbb6734ab74ad0e2e11d887ef4a883 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_db93ff24728c6fc6b9fb4a85afdfde84.setIcon(icon_12fbb6734ab74ad0e2e11d887ef4a883);
        
    
        var popup_93462f049653a662219805d96ff4a787 = L.popup({"maxWidth": "100%"});

        
            
                var html_5194135f0c74605c73b5339db26ea59b = $(`<div id="html_5194135f0c74605c73b5339db26ea59b" style="width: 100.0%; height: 100.0%;">Lewis Elementary School</div>`)[0];
                popup_93462f049653a662219805d96ff4a787.setContent(html_5194135f0c74605c73b5339db26ea59b);
            
        

        marker_db93ff24728c6fc6b9fb4a85afdfde84.bindPopup(popup_93462f049653a662219805d96ff4a787)
        ;

        
    
    
            var marker_35dcb6ab6792642e4aa9007a35c57126 = L.marker(
                [45.47715941, -122.6522122],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b021af3b6623bc273440924e1ed31962 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_35dcb6ab6792642e4aa9007a35c57126.setIcon(icon_b021af3b6623bc273440924e1ed31962);
        
    
        var popup_d17c13443b944a7c9b4662c25d49bab6 = L.popup({"maxWidth": "100%"});

        
            
                var html_0c5041c5b6b5927e0fa74cdc602adeb0 = $(`<div id="html_0c5041c5b6b5927e0fa74cdc602adeb0" style="width: 100.0%; height: 100.0%;">Llewellyn Elementary School</div>`)[0];
                popup_d17c13443b944a7c9b4662c25d49bab6.setContent(html_0c5041c5b6b5927e0fa74cdc602adeb0);
            
        

        marker_35dcb6ab6792642e4aa9007a35c57126.bindPopup(popup_d17c13443b944a7c9b4662c25d49bab6)
        ;

        
    
    
            var marker_ddc2051847f7eb6b4317704bbc6d4b5a = L.marker(
                [45.47090446, -122.729892],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_eae72e111a3a87ffb0f160087c1cc30f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ddc2051847f7eb6b4317704bbc6d4b5a.setIcon(icon_eae72e111a3a87ffb0f160087c1cc30f);
        
    
        var popup_50ddbb08ef44b4412fded11e7db3b300 = L.popup({"maxWidth": "100%"});

        
            
                var html_9144fd016748a5fa2388cbd27fb83a31 = $(`<div id="html_9144fd016748a5fa2388cbd27fb83a31" style="width: 100.0%; height: 100.0%;">Maplewood Elementary School</div>`)[0];
                popup_50ddbb08ef44b4412fded11e7db3b300.setContent(html_9144fd016748a5fa2388cbd27fb83a31);
            
        

        marker_ddc2051847f7eb6b4317704bbc6d4b5a.bindPopup(popup_50ddbb08ef44b4412fded11e7db3b300)
        ;

        
    
    
            var marker_670f2f331337cb1dc9f81ffe412a2ea9 = L.marker(
                [45.44921594, -122.7255058],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_eb1d96bd3024ab755b38343640c29dc4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_670f2f331337cb1dc9f81ffe412a2ea9.setIcon(icon_eb1d96bd3024ab755b38343640c29dc4);
        
    
        var popup_abf39dc49127b001ca8689d1950dc57c = L.popup({"maxWidth": "100%"});

        
            
                var html_43d7023e00eca66c263ba07abb019443 = $(`<div id="html_43d7023e00eca66c263ba07abb019443" style="width: 100.0%; height: 100.0%;">Markham Elementary School</div>`)[0];
                popup_abf39dc49127b001ca8689d1950dc57c.setContent(html_43d7023e00eca66c263ba07abb019443);
            
        

        marker_670f2f331337cb1dc9f81ffe412a2ea9.bindPopup(popup_abf39dc49127b001ca8689d1950dc57c)
        ;

        
    
    
            var marker_8291757e60a3287e3d771e6714240f3c = L.marker(
                [45.55808001, -122.6590959],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e2ea03f2cb8b5ef366fe60fb2928db39 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8291757e60a3287e3d771e6714240f3c.setIcon(icon_e2ea03f2cb8b5ef366fe60fb2928db39);
        
    
        var popup_f47af2e9d656909d03b4f181c403e8d6 = L.popup({"maxWidth": "100%"});

        
            
                var html_16ad386009fc54e65897f18a7da6e34d = $(`<div id="html_16ad386009fc54e65897f18a7da6e34d" style="width: 100.0%; height: 100.0%;">Martin Luther King Jr. School</div>`)[0];
                popup_f47af2e9d656909d03b4f181c403e8d6.setContent(html_16ad386009fc54e65897f18a7da6e34d);
            
        

        marker_8291757e60a3287e3d771e6714240f3c.bindPopup(popup_f47af2e9d656909d03b4f181c403e8d6)
        ;

        
    
    
            var marker_1ab967528c818ca858800ec8a17de799 = L.marker(
                [45.48691673, -122.5835546],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8f7fbc27808ce3d6e5b4e80741f1ee37 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1ab967528c818ca858800ec8a17de799.setIcon(icon_8f7fbc27808ce3d6e5b4e80741f1ee37);
        
    
        var popup_ea105fc0afeaaa6d3607a29406820016 = L.popup({"maxWidth": "100%"});

        
            
                var html_4ce349529f419a50654ad9f8902d30c2 = $(`<div id="html_4ce349529f419a50654ad9f8902d30c2" style="width: 100.0%; height: 100.0%;">Marysville Elementary School</div>`)[0];
                popup_ea105fc0afeaaa6d3607a29406820016.setContent(html_4ce349529f419a50654ad9f8902d30c2);
            
        

        marker_1ab967528c818ca858800ec8a17de799.bindPopup(popup_ea105fc0afeaaa6d3607a29406820016)
        ;

        
    
    
            var marker_2f654f344b16401fbd1b519552f4051e = L.marker(
                [45.58218512, -122.700306],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d7e9b1d0701059a6049c6dcc08115a4d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2f654f344b16401fbd1b519552f4051e.setIcon(icon_d7e9b1d0701059a6049c6dcc08115a4d);
        
    
        var popup_6b36aaea580170c4ff58a5599cffec34 = L.popup({"maxWidth": "100%"});

        
            
                var html_2d714fa81c5448078a8952567d637b04 = $(`<div id="html_2d714fa81c5448078a8952567d637b04" style="width: 100.0%; height: 100.0%;">Peninsula Elementary School</div>`)[0];
                popup_6b36aaea580170c4ff58a5599cffec34.setContent(html_2d714fa81c5448078a8952567d637b04);
            
        

        marker_2f654f344b16401fbd1b519552f4051e.bindPopup(popup_6b36aaea580170c4ff58a5599cffec34)
        ;

        
    
    
            var marker_0cb7c93930e614d9b98b4967e10a33c1 = L.marker(
                [45.51652398, -122.5858098],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_4c5e3eacb0aaa7acb3edda3274d1bf1c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_0cb7c93930e614d9b98b4967e10a33c1.setIcon(icon_4c5e3eacb0aaa7acb3edda3274d1bf1c);
        
    
        var popup_37991d02d35b794ea3f6ecce172176f0 = L.popup({"maxWidth": "100%"});

        
            
                var html_88a98f020db2ad36ebb12295bfa59333 = $(`<div id="html_88a98f020db2ad36ebb12295bfa59333" style="width: 100.0%; height: 100.0%;">Portland Arthur Academy Charter School</div>`)[0];
                popup_37991d02d35b794ea3f6ecce172176f0.setContent(html_88a98f020db2ad36ebb12295bfa59333);
            
        

        marker_0cb7c93930e614d9b98b4967e10a33c1.bindPopup(popup_37991d02d35b794ea3f6ecce172176f0)
        ;

        
    
    
            var marker_c1de667b0f1299b2e66926a9da42eb7d = L.marker(
                [45.57865804, -122.6919532],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d11acbf72b3bf8cb3977cbcf6fdb3b62 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c1de667b0f1299b2e66926a9da42eb7d.setIcon(icon_d11acbf72b3bf8cb3977cbcf6fdb3b62);
        
    
        var popup_186c83f7f9aec9faeee8d47a0fd0744f = L.popup({"maxWidth": "100%"});

        
            
                var html_cc28d00f9b345d710d928c1fe8bb1ac2 = $(`<div id="html_cc28d00f9b345d710d928c1fe8bb1ac2" style="width: 100.0%; height: 100.0%;">Portland Village School</div>`)[0];
                popup_186c83f7f9aec9faeee8d47a0fd0744f.setContent(html_cc28d00f9b345d710d928c1fe8bb1ac2);
            
        

        marker_c1de667b0f1299b2e66926a9da42eb7d.bindPopup(popup_186c83f7f9aec9faeee8d47a0fd0744f)
        ;

        
    
    
            var marker_ea8f8c51b846f350e6ecf3cf88d12783 = L.marker(
                [45.50643688, -122.6199052],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_79ec3b7487600ecad39716165cae3790 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ea8f8c51b846f350e6ecf3cf88d12783.setIcon(icon_79ec3b7487600ecad39716165cae3790);
        
    
        var popup_e4c8df927d73fb06d99970fe5755a9fe = L.popup({"maxWidth": "100%"});

        
            
                var html_ba3f0c3b5088e0f927cc027835b3d9d5 = $(`<div id="html_ba3f0c3b5088e0f927cc027835b3d9d5" style="width: 100.0%; height: 100.0%;">Richmond Elementary School</div>`)[0];
                popup_e4c8df927d73fb06d99970fe5755a9fe.setContent(html_ba3f0c3b5088e0f927cc027835b3d9d5);
            
        

        marker_ea8f8c51b846f350e6ecf3cf88d12783.bindPopup(popup_e4c8df927d73fb06d99970fe5755a9fe)
        ;

        
    
    
            var marker_26c696ad1ee47517e380e24953e857b5 = L.marker(
                [45.4764889, -122.6949689],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_367b577e99e3a72442ae069883718cdc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_26c696ad1ee47517e380e24953e857b5.setIcon(icon_367b577e99e3a72442ae069883718cdc);
        
    
        var popup_4c93f806f7cb05c0c82cee7cf29ed42e = L.popup({"maxWidth": "100%"});

        
            
                var html_999780158a73934b2374b886dad382dd = $(`<div id="html_999780158a73934b2374b886dad382dd" style="width: 100.0%; height: 100.0%;">Rieke Elementary School</div>`)[0];
                popup_4c93f806f7cb05c0c82cee7cf29ed42e.setContent(html_999780158a73934b2374b886dad382dd);
            
        

        marker_26c696ad1ee47517e380e24953e857b5.bindPopup(popup_4c93f806f7cb05c0c82cee7cf29ed42e)
        ;

        
    
    
            var marker_5392fde72c1d277c123bed7e010de484 = L.marker(
                [45.55596101, -122.6078129],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_61d6ae88e9272c553baf4e4f6a17538e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5392fde72c1d277c123bed7e010de484.setIcon(icon_61d6ae88e9272c553baf4e4f6a17538e);
        
    
        var popup_338d0a0472c901394dcc31f6da911cc7 = L.popup({"maxWidth": "100%"});

        
            
                var html_2d8884c5b4555ec4321d45e165aba284 = $(`<div id="html_2d8884c5b4555ec4321d45e165aba284" style="width: 100.0%; height: 100.0%;">Rigler Elementary School</div>`)[0];
                popup_338d0a0472c901394dcc31f6da911cc7.setContent(html_2d8884c5b4555ec4321d45e165aba284);
            
        

        marker_5392fde72c1d277c123bed7e010de484.bindPopup(popup_338d0a0472c901394dcc31f6da911cc7)
        ;

        
    
    
            var marker_59ff6d22a02aa31a13f51b6dd788877e = L.marker(
                [45.58782773, -122.7130237],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a542828c403be3b371e441454f39ccb2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_59ff6d22a02aa31a13f51b6dd788877e.setIcon(icon_a542828c403be3b371e441454f39ccb2);
        
    
        var popup_6be0e4ad4db928ef1d0708f6187d7352 = L.popup({"maxWidth": "100%"});

        
            
                var html_63f1b0a469008348acad5c02f0df15e1 = $(`<div id="html_63f1b0a469008348acad5c02f0df15e1" style="width: 100.0%; height: 100.0%;">Rosa Parks Elementary School</div>`)[0];
                popup_6be0e4ad4db928ef1d0708f6187d7352.setContent(html_63f1b0a469008348acad5c02f0df15e1);
            
        

        marker_59ff6d22a02aa31a13f51b6dd788877e.bindPopup(popup_6be0e4ad4db928ef1d0708f6187d7352)
        ;

        
    
    
            var marker_188ea6bf0ea4962d8e2cf3e94f3bf98f = L.marker(
                [45.53936715, -122.6041121],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_14b3d895c9d042337a48673dd4d6603e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_188ea6bf0ea4962d8e2cf3e94f3bf98f.setIcon(icon_14b3d895c9d042337a48673dd4d6603e);
        
    
        var popup_2c6814e32792e88c451b2d3c8c73cb65 = L.popup({"maxWidth": "100%"});

        
            
                var html_2ab9fd010344a60e8e93d449cc797954 = $(`<div id="html_2ab9fd010344a60e8e93d449cc797954" style="width: 100.0%; height: 100.0%;">Rose City Park</div>`)[0];
                popup_2c6814e32792e88c451b2d3c8c73cb65.setContent(html_2ab9fd010344a60e8e93d449cc797954);
            
        

        marker_188ea6bf0ea4962d8e2cf3e94f3bf98f.bindPopup(popup_2c6814e32792e88c451b2d3c8c73cb65)
        ;

        
    
    
            var marker_35dcd93d358ed66406c10da01971a867 = L.marker(
                [45.55217942, -122.6478574],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1c29d7e4e2e72632ccba52b33cf74482 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_35dcd93d358ed66406c10da01971a867.setIcon(icon_1c29d7e4e2e72632ccba52b33cf74482);
        
    
        var popup_a3f2bf809738f5b44a0e78da4aeea66b = L.popup({"maxWidth": "100%"});

        
            
                var html_ed5ba20159945018eabbea517d7f3e81 = $(`<div id="html_ed5ba20159945018eabbea517d7f3e81" style="width: 100.0%; height: 100.0%;">Sabin Elementary School</div>`)[0];
                popup_a3f2bf809738f5b44a0e78da4aeea66b.setContent(html_ed5ba20159945018eabbea517d7f3e81);
            
        

        marker_35dcd93d358ed66406c10da01971a867.bindPopup(popup_a3f2bf809738f5b44a0e78da4aeea66b)
        ;

        
    
    
            var marker_dd0aaa66170dd9c59a348f22f7d58952 = L.marker(
                [45.55519246, -122.5943055],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_45e9b3c4a708d326f99bb3db09da463c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dd0aaa66170dd9c59a348f22f7d58952.setIcon(icon_45e9b3c4a708d326f99bb3db09da463c);
        
    
        var popup_f1d4e911c9e93ce2138e2186ca843619 = L.popup({"maxWidth": "100%"});

        
            
                var html_e662f6c81053cec49d2cd63a32c358bb = $(`<div id="html_e662f6c81053cec49d2cd63a32c358bb" style="width: 100.0%; height: 100.0%;">Scott Elementary School</div>`)[0];
                popup_f1d4e911c9e93ce2138e2186ca843619.setContent(html_e662f6c81053cec49d2cd63a32c358bb);
            
        

        marker_dd0aaa66170dd9c59a348f22f7d58952.bindPopup(popup_f1d4e911c9e93ce2138e2186ca843619)
        ;

        
    
    
            var marker_60f61f80b76ff25f6eeb5f6446a0961c = L.marker(
                [45.60003474, -122.7583503],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_6ddb4ba0b92bf4fe8326025b41fe015c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_60f61f80b76ff25f6eeb5f6446a0961c.setIcon(icon_6ddb4ba0b92bf4fe8326025b41fe015c);
        
    
        var popup_33fbd66edb07c74969cdc9f0539ab78e = L.popup({"maxWidth": "100%"});

        
            
                var html_c926f63f051d14b409256582ff523bca = $(`<div id="html_c926f63f051d14b409256582ff523bca" style="width: 100.0%; height: 100.0%;">Sitton Elementary School</div>`)[0];
                popup_33fbd66edb07c74969cdc9f0539ab78e.setContent(html_c926f63f051d14b409256582ff523bca);
            
        

        marker_60f61f80b76ff25f6eeb5f6446a0961c.bindPopup(popup_33fbd66edb07c74969cdc9f0539ab78e)
        ;

        
    
    
            var marker_145bd37f66b10bccfd4d0cd86b765f62 = L.marker(
                [45.60752093, -122.8565661],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_30bbf9e933da4b3291608c11b0d0fbce = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_145bd37f66b10bccfd4d0cd86b765f62.setIcon(icon_30bbf9e933da4b3291608c11b0d0fbce);
        
    
        var popup_7d632266bebe5cd223571e4eb6dbbb03 = L.popup({"maxWidth": "100%"});

        
            
                var html_2a1e04fabc2c94d1b54d7903ea23e582 = $(`<div id="html_2a1e04fabc2c94d1b54d7903ea23e582" style="width: 100.0%; height: 100.0%;">Skyline Elementary School</div>`)[0];
                popup_7d632266bebe5cd223571e4eb6dbbb03.setContent(html_2a1e04fabc2c94d1b54d7903ea23e582);
            
        

        marker_145bd37f66b10bccfd4d0cd86b765f62.bindPopup(popup_7d632266bebe5cd223571e4eb6dbbb03)
        ;

        
    
    
            var marker_6b99b1cb5fc1ec0856f5cd0928f51099 = L.marker(
                [45.44100753, -122.7040455],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_2729881407e80e6c944ad4a673ab7770 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6b99b1cb5fc1ec0856f5cd0928f51099.setIcon(icon_2729881407e80e6c944ad4a673ab7770);
        
    
        var popup_6190ecccfc7a38fb15983bfd91a3e18f = L.popup({"maxWidth": "100%"});

        
            
                var html_1ef9d9a7492e9b2a4540a350fde8462a = $(`<div id="html_1ef9d9a7492e9b2a4540a350fde8462a" style="width: 100.0%; height: 100.0%;">Stephenson Elementary School</div>`)[0];
                popup_6190ecccfc7a38fb15983bfd91a3e18f.setContent(html_1ef9d9a7492e9b2a4540a350fde8462a);
            
        

        marker_6b99b1cb5fc1ec0856f5cd0928f51099.bindPopup(popup_6190ecccfc7a38fb15983bfd91a3e18f)
        ;

        
    
    
            var marker_1b7a37c755f6ece0119addcf4b20ec3a = L.marker(
                [45.51455439, -122.628987],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b87edd8078958879afa63d7417b03b23 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_1b7a37c755f6ece0119addcf4b20ec3a.setIcon(icon_b87edd8078958879afa63d7417b03b23);
        
    
        var popup_175846e5c07c8f87098ab0e2aab47c45 = L.popup({"maxWidth": "100%"});

        
            
                var html_b6ac3f70bdcd4278bc28efe5ba5cba37 = $(`<div id="html_b6ac3f70bdcd4278bc28efe5ba5cba37" style="width: 100.0%; height: 100.0%;">Sunnyside Environmental School</div>`)[0];
                popup_175846e5c07c8f87098ab0e2aab47c45.setContent(html_b6ac3f70bdcd4278bc28efe5ba5cba37);
            
        

        marker_1b7a37c755f6ece0119addcf4b20ec3a.bindPopup(popup_175846e5c07c8f87098ab0e2aab47c45)
        ;

        
    
    
            var marker_e00026e7fee742ddde2cfb9ec294d250 = L.marker(
                [45.56243336, -122.6438874],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_86bfe6b7ee76eb08f31791f467636527 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_e00026e7fee742ddde2cfb9ec294d250.setIcon(icon_86bfe6b7ee76eb08f31791f467636527);
        
    
        var popup_06bbedc03346eb1dc78faef7a1090107 = L.popup({"maxWidth": "100%"});

        
            
                var html_1a243c5a3ca172c84046ae3fa6ea2ef7 = $(`<div id="html_1a243c5a3ca172c84046ae3fa6ea2ef7" style="width: 100.0%; height: 100.0%;">Vernon Elementary School</div>`)[0];
                popup_06bbedc03346eb1dc78faef7a1090107.setContent(html_1a243c5a3ca172c84046ae3fa6ea2ef7);
            
        

        marker_e00026e7fee742ddde2cfb9ec294d250.bindPopup(popup_06bbedc03346eb1dc78faef7a1090107)
        ;

        
    
    
            var marker_4c7e82f589228cb716b408824bc4e15a = L.marker(
                [45.52457318, -122.5796472],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7e3053cf91f77856c5e7e8d056e3e5a5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4c7e82f589228cb716b408824bc4e15a.setIcon(icon_7e3053cf91f77856c5e7e8d056e3e5a5);
        
    
        var popup_95ca2df66e1c8164540b58a439a49597 = L.popup({"maxWidth": "100%"});

        
            
                var html_839e950b68a1cbb672ee5c3a26f6df6e = $(`<div id="html_839e950b68a1cbb672ee5c3a26f6df6e" style="width: 100.0%; height: 100.0%;">Vestal Elementary School</div>`)[0];
                popup_95ca2df66e1c8164540b58a439a49597.setContent(html_839e950b68a1cbb672ee5c3a26f6df6e);
            
        

        marker_4c7e82f589228cb716b408824bc4e15a.bindPopup(popup_95ca2df66e1c8164540b58a439a49597)
        ;

        
    
    
            var marker_70631ceb5391d2714031b5a888a82deb = L.marker(
                [45.46811016, -122.587309],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_d164fa5a03377bcbe71a10d523ec064a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_70631ceb5391d2714031b5a888a82deb.setIcon(icon_d164fa5a03377bcbe71a10d523ec064a);
        
    
        var popup_606163997b6fdb09efc89dc7b41810a4 = L.popup({"maxWidth": "100%"});

        
            
                var html_848437ea71743f27b87b278bd4e32005 = $(`<div id="html_848437ea71743f27b87b278bd4e32005" style="width: 100.0%; height: 100.0%;">Whitman Elementary School</div>`)[0];
                popup_606163997b6fdb09efc89dc7b41810a4.setContent(html_848437ea71743f27b87b278bd4e32005);
            
        

        marker_70631ceb5391d2714031b5a888a82deb.bindPopup(popup_606163997b6fdb09efc89dc7b41810a4)
        ;

        
    
    
            var marker_5335c5b27c1f3c8fa262e10884f44e4a = L.marker(
                [45.49491557, -122.6509431],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_78fbcf12eba013ca09e3aa3233d91602 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_5335c5b27c1f3c8fa262e10884f44e4a.setIcon(icon_78fbcf12eba013ca09e3aa3233d91602);
        
    
        var popup_e627681a66acf48d2470351846bf1bcc = L.popup({"maxWidth": "100%"});

        
            
                var html_7eeec4cb1630e71b4cbc387c820ce51d = $(`<div id="html_7eeec4cb1630e71b4cbc387c820ce51d" style="width: 100.0%; height: 100.0%;">Winterhaven School</div>`)[0];
                popup_e627681a66acf48d2470351846bf1bcc.setContent(html_7eeec4cb1630e71b4cbc387c820ce51d);
            
        

        marker_5335c5b27c1f3c8fa262e10884f44e4a.bindPopup(popup_e627681a66acf48d2470351846bf1bcc)
        ;

        
    
    
            var marker_d9d8fe02b1bae784105fe5f7922d1511 = L.marker(
                [45.57494256, -122.6533236],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e9f1287036bc7dde475c5b15fd9193d1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d9d8fe02b1bae784105fe5f7922d1511.setIcon(icon_e9f1287036bc7dde475c5b15fd9193d1);
        
    
        var popup_b59d57a96bda32956acb1d1d44d8c13d = L.popup({"maxWidth": "100%"});

        
            
                var html_bdae25b8e813915dbe504cb37bfb25c7 = $(`<div id="html_bdae25b8e813915dbe504cb37bfb25c7" style="width: 100.0%; height: 100.0%;">Woodlawn Elementary School</div>`)[0];
                popup_b59d57a96bda32956acb1d1d44d8c13d.setContent(html_bdae25b8e813915dbe504cb37bfb25c7);
            
        

        marker_d9d8fe02b1bae784105fe5f7922d1511.bindPopup(popup_b59d57a96bda32956acb1d1d44d8c13d)
        ;

        
    
    
            var marker_404443b83328a895bf716a37b6010aa8 = L.marker(
                [45.47508329, -122.582378],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_5d2e923265be63515e4378f790267f2d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_404443b83328a895bf716a37b6010aa8.setIcon(icon_5d2e923265be63515e4378f790267f2d);
        
    
        var popup_f0036ff905da9d799168afab730e1e1d = L.popup({"maxWidth": "100%"});

        
            
                var html_ae99253840a059f7b48575cbe10a39eb = $(`<div id="html_ae99253840a059f7b48575cbe10a39eb" style="width: 100.0%; height: 100.0%;">Woodmere Elementary School</div>`)[0];
                popup_f0036ff905da9d799168afab730e1e1d.setContent(html_ae99253840a059f7b48575cbe10a39eb);
            
        

        marker_404443b83328a895bf716a37b6010aa8.bindPopup(popup_f0036ff905da9d799168afab730e1e1d)
        ;

        
    
    
            var marker_8998977e43d6ccbf33769d4bf130faa2 = L.marker(
                [45.48207794, -122.6120882],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_54908a6b0490af408c59fbb9746e6c94 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8998977e43d6ccbf33769d4bf130faa2.setIcon(icon_54908a6b0490af408c59fbb9746e6c94);
        
    
        var popup_3e6bf0d55fd4f72ad2db251a935df1db = L.popup({"maxWidth": "100%"});

        
            
                var html_fd55e567da776e5f2fb14badf61cc0d0 = $(`<div id="html_fd55e567da776e5f2fb14badf61cc0d0" style="width: 100.0%; height: 100.0%;">Woodstock Elementary School</div>`)[0];
                popup_3e6bf0d55fd4f72ad2db251a935df1db.setContent(html_fd55e567da776e5f2fb14badf61cc0d0);
            
        

        marker_8998977e43d6ccbf33769d4bf130faa2.bindPopup(popup_3e6bf0d55fd4f72ad2db251a935df1db)
        ;

        
    
    
            var marker_4d5db7a3d3e4fc01dc3acdad1c31c737 = L.marker(
                [45.51733408, -122.4865006],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_cb1c96a30c8fd3407171465645b77810 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4d5db7a3d3e4fc01dc3acdad1c31c737.setIcon(icon_cb1c96a30c8fd3407171465645b77810);
        
    
        var popup_bfaa602c73e1eb73b8c6013cff6c7f90 = L.popup({"maxWidth": "100%"});

        
            
                var html_a2a80e9698d2777a8c3ce37f7ed17190 = $(`<div id="html_a2a80e9698d2777a8c3ce37f7ed17190" style="width: 100.0%; height: 100.0%;">Alder Elementary School</div>`)[0];
                popup_bfaa602c73e1eb73b8c6013cff6c7f90.setContent(html_a2a80e9698d2777a8c3ce37f7ed17190);
            
        

        marker_4d5db7a3d3e4fc01dc3acdad1c31c737.bindPopup(popup_bfaa602c73e1eb73b8c6013cff6c7f90)
        ;

        
    
    
            var marker_6e263a2f2d24dd8632d2bed0985eb0e3 = L.marker(
                [45.52348949, -122.462155],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e0028ea0bdd8578f140d8cedd313db15 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6e263a2f2d24dd8632d2bed0985eb0e3.setIcon(icon_e0028ea0bdd8578f140d8cedd313db15);
        
    
        var popup_1cf0ba13cf34bd460b4606359454ef63 = L.popup({"maxWidth": "100%"});

        
            
                var html_2b4becd3d34c8d5320de0e57081a1cc0 = $(`<div id="html_2b4becd3d34c8d5320de0e57081a1cc0" style="width: 100.0%; height: 100.0%;">Davis Elementary School</div>`)[0];
                popup_1cf0ba13cf34bd460b4606359454ef63.setContent(html_2b4becd3d34c8d5320de0e57081a1cc0);
            
        

        marker_6e263a2f2d24dd8632d2bed0985eb0e3.bindPopup(popup_1cf0ba13cf34bd460b4606359454ef63)
        ;

        
    
    
            var marker_05aec494334c799b349ab10abea2962d = L.marker(
                [45.53962223, -122.4365273],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_cfbfb1389069a2a8896b300801e7f673 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_05aec494334c799b349ab10abea2962d.setIcon(icon_cfbfb1389069a2a8896b300801e7f673);
        
    
        var popup_4066d7c2863ee5ac5cbccadb51d1bd60 = L.popup({"maxWidth": "100%"});

        
            
                var html_451d3093f3641a5f269923720b7b6e63 = $(`<div id="html_451d3093f3641a5f269923720b7b6e63" style="width: 100.0%; height: 100.0%;">Fairview Elementary School</div>`)[0];
                popup_4066d7c2863ee5ac5cbccadb51d1bd60.setContent(html_451d3093f3641a5f269923720b7b6e63);
            
        

        marker_05aec494334c799b349ab10abea2962d.bindPopup(popup_4066d7c2863ee5ac5cbccadb51d1bd60)
        ;

        
    
    
            var marker_6a2d91b5786c5a1fed356b4f9518b5b8 = L.marker(
                [45.52609071, -122.5058102],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_bf44b1ddb2a0743303a612e091b0f107 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6a2d91b5786c5a1fed356b4f9518b5b8.setIcon(icon_bf44b1ddb2a0743303a612e091b0f107);
        
    
        var popup_be5d46bed42f977231778ead5c7b83c0 = L.popup({"maxWidth": "100%"});

        
            
                var html_1b7222ee42bed9e9906aa9c71f6180b0 = $(`<div id="html_1b7222ee42bed9e9906aa9c71f6180b0" style="width: 100.0%; height: 100.0%;">Glenfair Elementary School</div>`)[0];
                popup_be5d46bed42f977231778ead5c7b83c0.setContent(html_1b7222ee42bed9e9906aa9c71f6180b0);
            
        

        marker_6a2d91b5786c5a1fed356b4f9518b5b8.bindPopup(popup_be5d46bed42f977231778ead5c7b83c0)
        ;

        
    
    
            var marker_662e588b6225327bba9fe9efac10f867 = L.marker(
                [45.52827463, -122.4720956],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8943a623ce5b5e9fbbcb92078b530636 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_662e588b6225327bba9fe9efac10f867.setIcon(icon_8943a623ce5b5e9fbbcb92078b530636);
        
    
        var popup_351454127cbf7fa05ec05a6257ac2389 = L.popup({"maxWidth": "100%"});

        
            
                var html_efb7b5028e1b98006ccf8beec6b3afd6 = $(`<div id="html_efb7b5028e1b98006ccf8beec6b3afd6" style="width: 100.0%; height: 100.0%;">Hartley Elementary School</div>`)[0];
                popup_351454127cbf7fa05ec05a6257ac2389.setContent(html_efb7b5028e1b98006ccf8beec6b3afd6);
            
        

        marker_662e588b6225327bba9fe9efac10f867.bindPopup(popup_351454127cbf7fa05ec05a6257ac2389)
        ;

        
    
    
            var marker_4999dc25bc84d9f1fc84f6b39836d425 = L.marker(
                [45.53900299, -122.5117219],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_e47f5191aacf3bd0a9568dc14d544499 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_4999dc25bc84d9f1fc84f6b39836d425.setIcon(icon_e47f5191aacf3bd0a9568dc14d544499);
        
    
        var popup_d2846afb4f1582286d4b5ccf91e0de5e = L.popup({"maxWidth": "100%"});

        
            
                var html_e923793ad1a67bc04753b6212ff44e4a = $(`<div id="html_e923793ad1a67bc04753b6212ff44e4a" style="width: 100.0%; height: 100.0%;">Margaret Scott Elementary School</div>`)[0];
                popup_d2846afb4f1582286d4b5ccf91e0de5e.setContent(html_e923793ad1a67bc04753b6212ff44e4a);
            
        

        marker_4999dc25bc84d9f1fc84f6b39836d425.bindPopup(popup_d2846afb4f1582286d4b5ccf91e0de5e)
        ;

        
    
    
            var marker_9f588525de3830f3adea5f640662bd72 = L.marker(
                [45.5360025, -122.4309466],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f7806bd0e3e97462d8739b2038d9ce5e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9f588525de3830f3adea5f640662bd72.setIcon(icon_f7806bd0e3e97462d8739b2038d9ce5e);
        
    
        var popup_1a66f93dd233409318597f33e8e5a5e7 = L.popup({"maxWidth": "100%"});

        
            
                var html_3ab61838ca1adaee82dd68dbbb87ff2d = $(`<div id="html_3ab61838ca1adaee82dd68dbbb87ff2d" style="width: 100.0%; height: 100.0%;">Multnomah Learning Academy</div>`)[0];
                popup_1a66f93dd233409318597f33e8e5a5e7.setContent(html_3ab61838ca1adaee82dd68dbbb87ff2d);
            
        

        marker_9f588525de3830f3adea5f640662bd72.bindPopup(popup_1a66f93dd233409318597f33e8e5a5e7)
        ;

        
    
    
            var marker_f8c4c5e028332ec433abd3abdd0b0ff5 = L.marker(
                [45.5273035, -122.3886831],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_85d374fac5900129a66957bd258e8c89 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f8c4c5e028332ec433abd3abdd0b0ff5.setIcon(icon_85d374fac5900129a66957bd258e8c89);
        
    
        var popup_89d09ce5438a935c01cd54232883a4bf = L.popup({"maxWidth": "100%"});

        
            
                var html_6629cffba864fdfc6a5bd83536c14d5a = $(`<div id="html_6629cffba864fdfc6a5bd83536c14d5a" style="width: 100.0%; height: 100.0%;">Reynolds Arthur Academy</div>`)[0];
                popup_89d09ce5438a935c01cd54232883a4bf.setContent(html_6629cffba864fdfc6a5bd83536c14d5a);
            
        

        marker_f8c4c5e028332ec433abd3abdd0b0ff5.bindPopup(popup_89d09ce5438a935c01cd54232883a4bf)
        ;

        
    
    
            var marker_d764e6a8d533f5e72f4db65426de8315 = L.marker(
                [45.51753614, -122.4742968],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_f9402425616dcb6a75d72c58bb90dcf1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d764e6a8d533f5e72f4db65426de8315.setIcon(icon_f9402425616dcb6a75d72c58bb90dcf1);
        
    
        var popup_c4bf414967b911ecbda747b9b0e3ffc5 = L.popup({"maxWidth": "100%"});

        
            
                var html_cc69103db28e01e7a1941aa55c3bdd73 = $(`<div id="html_cc69103db28e01e7a1941aa55c3bdd73" style="width: 100.0%; height: 100.0%;">Rockwood Preparatory Academy</div>`)[0];
                popup_c4bf414967b911ecbda747b9b0e3ffc5.setContent(html_cc69103db28e01e7a1941aa55c3bdd73);
            
        

        marker_d764e6a8d533f5e72f4db65426de8315.bindPopup(popup_c4bf414967b911ecbda747b9b0e3ffc5)
        ;

        
    
    
            var marker_09d73deefaf53b5a0e354af222a1e9b4 = L.marker(
                [45.52968313, -122.4526154],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_1d8c8a20c5531188d62fd7e6bc0a527e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_09d73deefaf53b5a0e354af222a1e9b4.setIcon(icon_1d8c8a20c5531188d62fd7e6bc0a527e);
        
    
        var popup_1095b7c9c1fb487d2629777ac201f6f3 = L.popup({"maxWidth": "100%"});

        
            
                var html_c87f18e3d43443bdb12db9f314d49b58 = $(`<div id="html_c87f18e3d43443bdb12db9f314d49b58" style="width: 100.0%; height: 100.0%;">Salish Ponds Elementary School</div>`)[0];
                popup_1095b7c9c1fb487d2629777ac201f6f3.setContent(html_c87f18e3d43443bdb12db9f314d49b58);
            
        

        marker_09d73deefaf53b5a0e354af222a1e9b4.bindPopup(popup_1095b7c9c1fb487d2629777ac201f6f3)
        ;

        
    
    
            var marker_6ce857fa18c552b41c872771518eb774 = L.marker(
                [45.51612396, -122.3823014],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c5fb9a4911586eaa89d2ccdd929208e0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_6ce857fa18c552b41c872771518eb774.setIcon(icon_c5fb9a4911586eaa89d2ccdd929208e0);
        
    
        var popup_263fc49bc003931b37f4e9bb23755cf9 = L.popup({"maxWidth": "100%"});

        
            
                var html_d4cec790016464125552bf89cbbe073b = $(`<div id="html_d4cec790016464125552bf89cbbe073b" style="width: 100.0%; height: 100.0%;">Sweetbriar Elementary School</div>`)[0];
                popup_263fc49bc003931b37f4e9bb23755cf9.setContent(html_d4cec790016464125552bf89cbbe073b);
            
        

        marker_6ce857fa18c552b41c872771518eb774.bindPopup(popup_263fc49bc003931b37f4e9bb23755cf9)
        ;

        
    
    
            var marker_dd3545a3158a0f6def37454971dd7551 = L.marker(
                [45.53660341, -122.3860739],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_4686d1a749bd619b2915d2d221553d2f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_dd3545a3158a0f6def37454971dd7551.setIcon(icon_4686d1a749bd619b2915d2d221553d2f);
        
    
        var popup_482565286b2d34229fb927bbab4e0bce = L.popup({"maxWidth": "100%"});

        
            
                var html_5eb6118fb9f99fd60c7ef2cf79bd5173 = $(`<div id="html_5eb6118fb9f99fd60c7ef2cf79bd5173" style="width: 100.0%; height: 100.0%;">Troutdale Elementary School</div>`)[0];
                popup_482565286b2d34229fb927bbab4e0bce.setContent(html_5eb6118fb9f99fd60c7ef2cf79bd5173);
            
        

        marker_dd3545a3158a0f6def37454971dd7551.bindPopup(popup_482565286b2d34229fb927bbab4e0bce)
        ;

        
    
    
            var marker_da4eb072ae6a4d5163113dd58183d6a3 = L.marker(
                [45.5417947, -122.4887135],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_86ca511da9f68f3ca1353254eb3b2745 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_da4eb072ae6a4d5163113dd58183d6a3.setIcon(icon_86ca511da9f68f3ca1353254eb3b2745);
        
    
        var popup_feabba66fcc4be8031c0dcbd6220f265 = L.popup({"maxWidth": "100%"});

        
            
                var html_31abaf49bdb486e25ca9e1fc1aea22e0 = $(`<div id="html_31abaf49bdb486e25ca9e1fc1aea22e0" style="width: 100.0%; height: 100.0%;">Wilkes Elementary School</div>`)[0];
                popup_feabba66fcc4be8031c0dcbd6220f265.setContent(html_31abaf49bdb486e25ca9e1fc1aea22e0);
            
        

        marker_da4eb072ae6a4d5163113dd58183d6a3.bindPopup(popup_feabba66fcc4be8031c0dcbd6220f265)
        ;

        
    
    
            var marker_9481738b8676e0132d64a6251ec296cb = L.marker(
                [45.52903885, -122.4405168],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b27b976a3d55401c25a3de47ddf4740c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9481738b8676e0132d64a6251ec296cb.setIcon(icon_b27b976a3d55401c25a3de47ddf4740c);
        
    
        var popup_f9a63d41c7b3ce6242e097e235477b64 = L.popup({"maxWidth": "100%"});

        
            
                var html_a55193c2f9e640b00d9883745f886697 = $(`<div id="html_a55193c2f9e640b00d9883745f886697" style="width: 100.0%; height: 100.0%;">Woodland Elementary</div>`)[0];
                popup_f9a63d41c7b3ce6242e097e235477b64.setContent(html_a55193c2f9e640b00d9883745f886697);
            
        

        marker_9481738b8676e0132d64a6251ec296cb.bindPopup(popup_f9a63d41c7b3ce6242e097e235477b64)
        ;

        
    
    
            var marker_9c90efbbd7ef08d70f0f3fc8a1eff239 = L.marker(
                [45.43987615, -122.6561545],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_38f09dae68ccde2b889b567a6c19ccce = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9c90efbbd7ef08d70f0f3fc8a1eff239.setIcon(icon_38f09dae68ccde2b889b567a6c19ccce);
        
    
        var popup_dc9d40604aa77d7f521c6f71b03c1a53 = L.popup({"maxWidth": "100%"});

        
            
                var html_96d3e48584d056fd562f150349575688 = $(`<div id="html_96d3e48584d056fd562f150349575688" style="width: 100.0%; height: 100.0%;">Riverdale Grade School</div>`)[0];
                popup_dc9d40604aa77d7f521c6f71b03c1a53.setContent(html_96d3e48584d056fd562f150349575688);
            
        

        marker_9c90efbbd7ef08d70f0f3fc8a1eff239.bindPopup(popup_dc9d40604aa77d7f521c6f71b03c1a53)
        ;

        
    
    
            var marker_2a4ea27d348800f2ca3c006838f2917b = L.marker(
                [45.35052877, -122.8439433],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_a3ef072746ec2a7d97173f732015cbbe = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2a4ea27d348800f2ca3c006838f2917b.setIcon(icon_a3ef072746ec2a7d97173f732015cbbe);
        
    
        var popup_caf881d80d1543cb960c4eb10b62a4e8 = L.popup({"maxWidth": "100%"});

        
            
                var html_0d0337aa89c8998bf93c6de090979010 = $(`<div id="html_0d0337aa89c8998bf93c6de090979010" style="width: 100.0%; height: 100.0%;">Archer Glen Elementary School</div>`)[0];
                popup_caf881d80d1543cb960c4eb10b62a4e8.setContent(html_0d0337aa89c8998bf93c6de090979010);
            
        

        marker_2a4ea27d348800f2ca3c006838f2917b.bindPopup(popup_caf881d80d1543cb960c4eb10b62a4e8)
        ;

        
    
    
            var marker_b6908c118cc26b24ee43290a17a9cd86 = L.marker(
                [45.36511866, -122.8638693],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_266008adf53209d1664edad0737f7829 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b6908c118cc26b24ee43290a17a9cd86.setIcon(icon_266008adf53209d1664edad0737f7829);
        
    
        var popup_639b29d718b1ff60fcde66c859c93b4b = L.popup({"maxWidth": "100%"});

        
            
                var html_3cf9aabdc810aebc1289830b96d89ea0 = $(`<div id="html_3cf9aabdc810aebc1289830b96d89ea0" style="width: 100.0%; height: 100.0%;">Edy Ridge Elementary School</div>`)[0];
                popup_639b29d718b1ff60fcde66c859c93b4b.setContent(html_3cf9aabdc810aebc1289830b96d89ea0);
            
        

        marker_b6908c118cc26b24ee43290a17a9cd86.bindPopup(popup_639b29d718b1ff60fcde66c859c93b4b)
        ;

        
    
    
            var marker_716db4c5bf34ac79cb166b7519540871 = L.marker(
                [45.36149684, -122.8432191],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b78b4aedc3d1e3c3245c9a0efca19121 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_716db4c5bf34ac79cb166b7519540871.setIcon(icon_b78b4aedc3d1e3c3245c9a0efca19121);
        
    
        var popup_1509d55b8d704f9f83b89fb95f68b283 = L.popup({"maxWidth": "100%"});

        
            
                var html_de717940958de03226ec4d4787a33fd5 = $(`<div id="html_de717940958de03226ec4d4787a33fd5" style="width: 100.0%; height: 100.0%;">J Clyde Hopkins Elementary School</div>`)[0];
                popup_1509d55b8d704f9f83b89fb95f68b283.setContent(html_de717940958de03226ec4d4787a33fd5);
            
        

        marker_716db4c5bf34ac79cb166b7519540871.bindPopup(popup_1509d55b8d704f9f83b89fb95f68b283)
        ;

        
    
    
            var marker_9fa980e92770433326141993bbaf0deb = L.marker(
                [45.34922685, -122.8689438],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7fcdc3304235f3739b3bda49cbce475f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_9fa980e92770433326141993bbaf0deb.setIcon(icon_7fcdc3304235f3739b3bda49cbce475f);
        
    
        var popup_581f1dc815aa2be16e8650e74f4161b6 = L.popup({"maxWidth": "100%"});

        
            
                var html_7737b65b52a69f93e098a86d138b156f = $(`<div id="html_7737b65b52a69f93e098a86d138b156f" style="width: 100.0%; height: 100.0%;">Middleton Elementary School</div>`)[0];
                popup_581f1dc815aa2be16e8650e74f4161b6.setContent(html_7737b65b52a69f93e098a86d138b156f);
            
        

        marker_9fa980e92770433326141993bbaf0deb.bindPopup(popup_581f1dc815aa2be16e8650e74f4161b6)
        ;

        
    
    
            var marker_bea1faa8156851b7a4bc7d62abea7e09 = L.marker(
                [45.35119021, -122.8404964],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_ed9fdd196934b875f448fd11c6dcc3f0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_bea1faa8156851b7a4bc7d62abea7e09.setIcon(icon_ed9fdd196934b875f448fd11c6dcc3f0);
        
    
        var popup_a02f87372bfaf95f64c399794257f254 = L.popup({"maxWidth": "100%"});

        
            
                var html_1eb3d9d3ba42e4af7cc47a1539ef9aad = $(`<div id="html_1eb3d9d3ba42e4af7cc47a1539ef9aad" style="width: 100.0%; height: 100.0%;">Sherwood Charter School</div>`)[0];
                popup_a02f87372bfaf95f64c399794257f254.setContent(html_1eb3d9d3ba42e4af7cc47a1539ef9aad);
            
        

        marker_bea1faa8156851b7a4bc7d62abea7e09.bindPopup(popup_a02f87372bfaf95f64c399794257f254)
        ;

        
    
    
            var marker_082f0611db924b138f606e1f2bcd3413 = L.marker(
                [45.41199625, -122.8111605],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b902cc1858c68a0857cf2287c8ed9fec = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_082f0611db924b138f606e1f2bcd3413.setIcon(icon_b902cc1858c68a0857cf2287c8ed9fec);
        
    
        var popup_ea962773006ac76327ce75918fde2536 = L.popup({"maxWidth": "100%"});

        
            
                var html_6a9bd36b88b7225c425b08f5b8fb78c6 = $(`<div id="html_6a9bd36b88b7225c425b08f5b8fb78c6" style="width: 100.0%; height: 100.0%;">Alberta Rider Elementary School</div>`)[0];
                popup_ea962773006ac76327ce75918fde2536.setContent(html_6a9bd36b88b7225c425b08f5b8fb78c6);
            
        

        marker_082f0611db924b138f606e1f2bcd3413.bindPopup(popup_ea962773006ac76327ce75918fde2536)
        ;

        
    
    
            var marker_b95c6f1120b2c1e8c36568cbb48412af = L.marker(
                [45.37846144, -122.7326107],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_99861701afceb288138bcff92d5f5e1e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b95c6f1120b2c1e8c36568cbb48412af.setIcon(icon_99861701afceb288138bcff92d5f5e1e);
        
    
        var popup_42b78bcfd40bd9c9828fa402ced52e4f = L.popup({"maxWidth": "100%"});

        
            
                var html_dd3b6578bd7a26c97a62a10eac44b0d2 = $(`<div id="html_dd3b6578bd7a26c97a62a10eac44b0d2" style="width: 100.0%; height: 100.0%;">Bridgeport Elementary School</div>`)[0];
                popup_42b78bcfd40bd9c9828fa402ced52e4f.setContent(html_dd3b6578bd7a26c97a62a10eac44b0d2);
            
        

        marker_b95c6f1120b2c1e8c36568cbb48412af.bindPopup(popup_42b78bcfd40bd9c9828fa402ced52e4f)
        ;

        
    
    
            var marker_68d1b3f1b69a43ccb574d12ebdd004e5 = L.marker(
                [45.4269688, -122.7827011],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_73f0a6525b4cb06d0ae1d3a6d260d99d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_68d1b3f1b69a43ccb574d12ebdd004e5.setIcon(icon_73f0a6525b4cb06d0ae1d3a6d260d99d);
        
    
        var popup_b5e5d033bd7d987888836a321ac48003 = L.popup({"maxWidth": "100%"});

        
            
                var html_4d2ec173752fde6244c66cde054d28b1 = $(`<div id="html_4d2ec173752fde6244c66cde054d28b1" style="width: 100.0%; height: 100.0%;">Charles F Tigard Elementary School</div>`)[0];
                popup_b5e5d033bd7d987888836a321ac48003.setContent(html_4d2ec173752fde6244c66cde054d28b1);
            
        

        marker_68d1b3f1b69a43ccb574d12ebdd004e5.bindPopup(popup_b5e5d033bd7d987888836a321ac48003)
        ;

        
    
    
            var marker_16cd659fc590e5e9fdc6aea7ba6a4709 = L.marker(
                [45.40245585, -122.8132474],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_13c6da43559482d7d623f329cce53498 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_16cd659fc590e5e9fdc6aea7ba6a4709.setIcon(icon_13c6da43559482d7d623f329cce53498);
        
    
        var popup_6ed397c6f8b4f7c72eb423011ecd7666 = L.popup({"maxWidth": "100%"});

        
            
                var html_1f47b2cc67de0b975bde71450a4fe6d0 = $(`<div id="html_1f47b2cc67de0b975bde71450a4fe6d0" style="width: 100.0%; height: 100.0%;">Deer Creek Elementary School</div>`)[0];
                popup_6ed397c6f8b4f7c72eb423011ecd7666.setContent(html_1f47b2cc67de0b975bde71450a4fe6d0);
            
        

        marker_16cd659fc590e5e9fdc6aea7ba6a4709.bindPopup(popup_6ed397c6f8b4f7c72eb423011ecd7666)
        ;

        
    
    
            var marker_c1bf632c957462be70612f13ca77b8d9 = L.marker(
                [45.40285909, -122.7597047],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_3b0b8cc139c2bffd5bef5a02cc4c9ba4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c1bf632c957462be70612f13ca77b8d9.setIcon(icon_3b0b8cc139c2bffd5bef5a02cc4c9ba4);
        
    
        var popup_c73a1abff59239804d47162271371c4d = L.popup({"maxWidth": "100%"});

        
            
                var html_1dc97c07e3adc3d921a7ff461bd96d2f = $(`<div id="html_1dc97c07e3adc3d921a7ff461bd96d2f" style="width: 100.0%; height: 100.0%;">Durham Elementary School</div>`)[0];
                popup_c73a1abff59239804d47162271371c4d.setContent(html_1dc97c07e3adc3d921a7ff461bd96d2f);
            
        

        marker_c1bf632c957462be70612f13ca77b8d9.bindPopup(popup_c73a1abff59239804d47162271371c4d)
        ;

        
    
    
            var marker_8f270512f3a8ae612413598aa24c4786 = L.marker(
                [45.36256988, -122.7706697],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_aa2320d85b91b0f9a651df1f9588983c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_8f270512f3a8ae612413598aa24c4786.setIcon(icon_aa2320d85b91b0f9a651df1f9588983c);
        
    
        var popup_492aa6af9b9e647fa82192bde3e47dcb = L.popup({"maxWidth": "100%"});

        
            
                var html_f9d64a7b17b7704252e592b6d3b3bdb4 = $(`<div id="html_f9d64a7b17b7704252e592b6d3b3bdb4" style="width: 100.0%; height: 100.0%;">Edward Byrom Elementary School</div>`)[0];
                popup_492aa6af9b9e647fa82192bde3e47dcb.setContent(html_f9d64a7b17b7704252e592b6d3b3bdb4);
            
        

        marker_8f270512f3a8ae612413598aa24c4786.bindPopup(popup_492aa6af9b9e647fa82192bde3e47dcb)
        ;

        
    
    
            var marker_84e4f6a3acd018fc32f80980cf44981a = L.marker(
                [45.41301345, -122.7738446],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_6d7dc4ef300136d578b68e1e1ea4e81f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_84e4f6a3acd018fc32f80980cf44981a.setIcon(icon_6d7dc4ef300136d578b68e1e1ea4e81f);
        
    
        var popup_9495908ae52b89c03cd053b42ca76e81 = L.popup({"maxWidth": "100%"});

        
            
                var html_29bf6237152a4a8edee1b22fbcff2ae5 = $(`<div id="html_29bf6237152a4a8edee1b22fbcff2ae5" style="width: 100.0%; height: 100.0%;">James Templeton Elementary School</div>`)[0];
                popup_9495908ae52b89c03cd053b42ca76e81.setContent(html_29bf6237152a4a8edee1b22fbcff2ae5);
            
        

        marker_84e4f6a3acd018fc32f80980cf44981a.bindPopup(popup_9495908ae52b89c03cd053b42ca76e81)
        ;

        
    
    
            var marker_b8281bb0c2d5dada5828af88c76f9040 = L.marker(
                [45.43378099, -122.8038571],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_cc368488e594074735d5f0bf73308d17 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_b8281bb0c2d5dada5828af88c76f9040.setIcon(icon_cc368488e594074735d5f0bf73308d17);
        
    
        var popup_34f68dc41a3997ee9eb4d6d0e951e389 = L.popup({"maxWidth": "100%"});

        
            
                var html_93a4bad6d126a8b02409888fa01a731d = $(`<div id="html_93a4bad6d126a8b02409888fa01a731d" style="width: 100.0%; height: 100.0%;">Mary Woodward Elementary School</div>`)[0];
                popup_34f68dc41a3997ee9eb4d6d0e951e389.setContent(html_93a4bad6d126a8b02409888fa01a731d);
            
        

        marker_b8281bb0c2d5dada5828af88c76f9040.bindPopup(popup_34f68dc41a3997ee9eb4d6d0e951e389)
        ;

        
    
    
            var marker_58b5361d54e16b7642d2861079276a06 = L.marker(
                [45.44536003, -122.7712521],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7dadc4fb19126c6ca1850737cffd065f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_58b5361d54e16b7642d2861079276a06.setIcon(icon_7dadc4fb19126c6ca1850737cffd065f);
        
    
        var popup_e6311945578d6a8b2963a58f3d47f13f = L.popup({"maxWidth": "100%"});

        
            
                var html_f4d3fd803e291ddba49aa09ac321e4ca = $(`<div id="html_f4d3fd803e291ddba49aa09ac321e4ca" style="width: 100.0%; height: 100.0%;">Metzger Elementary School</div>`)[0];
                popup_e6311945578d6a8b2963a58f3d47f13f.setContent(html_f4d3fd803e291ddba49aa09ac321e4ca);
            
        

        marker_58b5361d54e16b7642d2861079276a06.bindPopup(popup_e6311945578d6a8b2963a58f3d47f13f)
        ;

        
    
    
            var marker_a5227a316e95f3ee35b085c7360aff6d = L.marker(
                [45.37844078, -122.7704978],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_84f33b5a58ee7ec796d2f2eeb5604e2f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a5227a316e95f3ee35b085c7360aff6d.setIcon(icon_84f33b5a58ee7ec796d2f2eeb5604e2f);
        
    
        var popup_a5d3c12aa446d7cc841b4a9afb80b6d4 = L.popup({"maxWidth": "100%"});

        
            
                var html_50fdc111e66f0fc2b85082ab3ab46c7f = $(`<div id="html_50fdc111e66f0fc2b85082ab3ab46c7f" style="width: 100.0%; height: 100.0%;">Multi-sensory Instruction Teaching Children Hands-On (MITCH)</div>`)[0];
                popup_a5d3c12aa446d7cc841b4a9afb80b6d4.setContent(html_50fdc111e66f0fc2b85082ab3ab46c7f);
            
        

        marker_a5227a316e95f3ee35b085c7360aff6d.bindPopup(popup_a5d3c12aa446d7cc841b4a9afb80b6d4)
        ;

        
    
    
            var marker_f591316dc65c30c500608913ff14587f = L.marker(
                [45.37233569, -122.776386],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_b1b84b7f0013f1d67e74c29f2ada19ab = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f591316dc65c30c500608913ff14587f.setIcon(icon_b1b84b7f0013f1d67e74c29f2ada19ab);
        
    
        var popup_7c24db0e64c8f7e6d1bbccda6989fb04 = L.popup({"maxWidth": "100%"});

        
            
                var html_c939c775ce6df717d90b3bb5b81b3434 = $(`<div id="html_c939c775ce6df717d90b3bb5b81b3434" style="width: 100.0%; height: 100.0%;">Tualatin Elementary School</div>`)[0];
                popup_7c24db0e64c8f7e6d1bbccda6989fb04.setContent(html_c939c775ce6df717d90b3bb5b81b3434);
            
        

        marker_f591316dc65c30c500608913ff14587f.bindPopup(popup_7c24db0e64c8f7e6d1bbccda6989fb04)
        ;

        
    
    
            var marker_a2e16ea11bf2b37f7ff5abcc71c57af6 = L.marker(
                [45.30936733, -122.7453569],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_fc08eb0221ca3b5f97cbb515e002821d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a2e16ea11bf2b37f7ff5abcc71c57af6.setIcon(icon_fc08eb0221ca3b5f97cbb515e002821d);
        
    
        var popup_82ed84fbbcf8da622faa10b0197197be = L.popup({"maxWidth": "100%"});

        
            
                var html_292b37776e51e3d23cf9b7bd12e59ef5 = $(`<div id="html_292b37776e51e3d23cf9b7bd12e59ef5" style="width: 100.0%; height: 100.0%;">Boeckman Creek Primary School</div>`)[0];
                popup_82ed84fbbcf8da622faa10b0197197be.setContent(html_292b37776e51e3d23cf9b7bd12e59ef5);
            
        

        marker_a2e16ea11bf2b37f7ff5abcc71c57af6.bindPopup(popup_82ed84fbbcf8da622faa10b0197197be)
        ;

        
    
    
            var marker_a8899170221c0ab87e08329f609d46bc = L.marker(
                [45.36990392, -122.6189734],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_2f42f850950080862be253c5282524c3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_a8899170221c0ab87e08329f609d46bc.setIcon(icon_2f42f850950080862be253c5282524c3);
        
    
        var popup_d0902d21048291fad8e1e581f6ba2295 = L.popup({"maxWidth": "100%"});

        
            
                var html_1a3f70067107c3fbba9df46bbe278ed4 = $(`<div id="html_1a3f70067107c3fbba9df46bbe278ed4" style="width: 100.0%; height: 100.0%;">Bolton Primary School</div>`)[0];
                popup_d0902d21048291fad8e1e581f6ba2295.setContent(html_1a3f70067107c3fbba9df46bbe278ed4);
            
        

        marker_a8899170221c0ab87e08329f609d46bc.bindPopup(popup_d0902d21048291fad8e1e581f6ba2295)
        ;

        
    
    
            var marker_2dd95c6565864d8b6358afdc437abe37 = L.marker(
                [45.3004171, -122.7950488],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_c7abdce8b3855bd988609dec3473a543 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_2dd95c6565864d8b6358afdc437abe37.setIcon(icon_c7abdce8b3855bd988609dec3473a543);
        
    
        var popup_039cb0527e3906ec894a8e373965b019 = L.popup({"maxWidth": "100%"});

        
            
                var html_6f4cca65c53e601cdc2b4d575fd67c28 = $(`<div id="html_6f4cca65c53e601cdc2b4d575fd67c28" style="width: 100.0%; height: 100.0%;">Boones Ferry Primary School</div>`)[0];
                popup_039cb0527e3906ec894a8e373965b019.setContent(html_6f4cca65c53e601cdc2b4d575fd67c28);
            
        

        marker_2dd95c6565864d8b6358afdc437abe37.bindPopup(popup_039cb0527e3906ec894a8e373965b019)
        ;

        
    
    
            var marker_294ecad4031a65a92a696d68fbdeeca8 = L.marker(
                [45.38887418, -122.6335152],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_55a0be0aa963e5473a9099bf646f457d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_294ecad4031a65a92a696d68fbdeeca8.setIcon(icon_55a0be0aa963e5473a9099bf646f457d);
        
    
        var popup_32ff986023a2bb6c5a691298b47f7e38 = L.popup({"maxWidth": "100%"});

        
            
                var html_54520d178addbbd1dbffe432bf3487f5 = $(`<div id="html_54520d178addbbd1dbffe432bf3487f5" style="width: 100.0%; height: 100.0%;">Cedaroak Park Primary School</div>`)[0];
                popup_32ff986023a2bb6c5a691298b47f7e38.setContent(html_54520d178addbbd1dbffe432bf3487f5);
            
        

        marker_294ecad4031a65a92a696d68fbdeeca8.bindPopup(popup_32ff986023a2bb6c5a691298b47f7e38)
        ;

        
    
    
            var marker_96f857669b5975100cd3555daf3e3b34 = L.marker(
                [45.31057175, -122.7872521],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_7070f251fceab68c3dea1b7fdeb66b71 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_96f857669b5975100cd3555daf3e3b34.setIcon(icon_7070f251fceab68c3dea1b7fdeb66b71);
        
    
        var popup_d056e8179487d091f39d6ca0e86859c0 = L.popup({"maxWidth": "100%"});

        
            
                var html_bee1affbed8e83e730f69fc5b8cdc4b0 = $(`<div id="html_bee1affbed8e83e730f69fc5b8cdc4b0" style="width: 100.0%; height: 100.0%;">Lowrie Primary School</div>`)[0];
                popup_d056e8179487d091f39d6ca0e86859c0.setContent(html_bee1affbed8e83e730f69fc5b8cdc4b0);
            
        

        marker_96f857669b5975100cd3555daf3e3b34.bindPopup(popup_d056e8179487d091f39d6ca0e86859c0)
        ;

        
    
    
            var marker_001e01cb713da0091f01a7f8f8636ff6 = L.marker(
                [45.37772722, -122.7025338],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8d2765eb0e436a85cfd5db28502ce0fd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_001e01cb713da0091f01a7f8f8636ff6.setIcon(icon_8d2765eb0e436a85cfd5db28502ce0fd);
        
    
        var popup_d92cf04967dbb9070d9862bc3f70fc8d = L.popup({"maxWidth": "100%"});

        
            
                var html_17413af763e71bbe75359a8e854c8a16 = $(`<div id="html_17413af763e71bbe75359a8e854c8a16" style="width: 100.0%; height: 100.0%;">Stafford Primary School</div>`)[0];
                popup_d92cf04967dbb9070d9862bc3f70fc8d.setContent(html_17413af763e71bbe75359a8e854c8a16);
            
        

        marker_001e01cb713da0091f01a7f8f8636ff6.bindPopup(popup_d92cf04967dbb9070d9862bc3f70fc8d)
        ;

        
    
    
            var marker_bc30496d5cc5fc2d978a9dd2f88fbec8 = L.marker(
                [45.36136112, -122.6268639],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_579f29b397e6e80d28f3e0a8a6c9bc6b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_bc30496d5cc5fc2d978a9dd2f88fbec8.setIcon(icon_579f29b397e6e80d28f3e0a8a6c9bc6b);
        
    
        var popup_4592d60dd21c9454ecbfb58300d10266 = L.popup({"maxWidth": "100%"});

        
            
                var html_2bb352b93fec0b0efd289a1630000fe4 = $(`<div id="html_2bb352b93fec0b0efd289a1630000fe4" style="width: 100.0%; height: 100.0%;">Sunset Primary School</div>`)[0];
                popup_4592d60dd21c9454ecbfb58300d10266.setContent(html_2bb352b93fec0b0efd289a1630000fe4);
            
        

        marker_bc30496d5cc5fc2d978a9dd2f88fbec8.bindPopup(popup_4592d60dd21c9454ecbfb58300d10266)
        ;

        
    
    
            var marker_d1bf4e0dd9dac588d7bb5b78ff2454ad = L.marker(
                [45.37462669, -122.651252],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_8deed6f27871e39b91a2c53276b18e65 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_d1bf4e0dd9dac588d7bb5b78ff2454ad.setIcon(icon_8deed6f27871e39b91a2c53276b18e65);
        
    
        var popup_552453201a40300b3b94a1605ac9123f = L.popup({"maxWidth": "100%"});

        
            
                var html_59e590796601fd3bfcef0bc4f53bdbd0 = $(`<div id="html_59e590796601fd3bfcef0bc4f53bdbd0" style="width: 100.0%; height: 100.0%;">Trillium Creek Primary School</div>`)[0];
                popup_552453201a40300b3b94a1605ac9123f.setContent(html_59e590796601fd3bfcef0bc4f53bdbd0);
            
        

        marker_d1bf4e0dd9dac588d7bb5b78ff2454ad.bindPopup(popup_552453201a40300b3b94a1605ac9123f)
        ;

        
    
    
            var marker_f55c68d789ecef94155fd130c77d3cb6 = L.marker(
                [45.34313666, -122.6528697],
                {}
            ).addTo(marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3);
        
    
            var icon_675f1afd0b80f4f3d2cd396fc097bd3d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "ok-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_f55c68d789ecef94155fd130c77d3cb6.setIcon(icon_675f1afd0b80f4f3d2cd396fc097bd3d);
        
    
        var popup_5d41f4002220baa6ed1ddf39fd3bcbc8 = L.popup({"maxWidth": "100%"});

        
            
                var html_431ea3380a6576ba61a143ce755a0f14 = $(`<div id="html_431ea3380a6576ba61a143ce755a0f14" style="width: 100.0%; height: 100.0%;">Willamette Primary School</div>`)[0];
                popup_5d41f4002220baa6ed1ddf39fd3bcbc8.setContent(html_431ea3380a6576ba61a143ce755a0f14);
            
        

        marker_f55c68d789ecef94155fd130c77d3cb6.bindPopup(popup_5d41f4002220baa6ed1ddf39fd3bcbc8)
        ;

        
    
    
                marker_cluster_5fd11ca7a75bf62f3ce5eb2b522305f3.addTo(map_e7bef7aa87e92bc65c34b6776536fb7d);
</script>
</html>
