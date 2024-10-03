![mermaid-diagram-2024-10-03-232504](https://github.com/user-attachments/assets/057ec0cd-60f8-4807-8ea7-df02c13a35e3)# Gramatica para el Robot
## Creditos
- Autor: Alejandro Arango
- Modificado por: Silvia Takahashi
- Modificado por: Juan Pablo Morales.
- Agregadas producciones para manejar globos
- Modificado por Silvia Takahashi
- Modificado por Juan Jose Diaz y Simon Calderon para interpretar nuevas instrucciones y funciones.
- Documentado por Juan Jose Diaz
## Instrucciones

## Diagrama
![Uploading m<svg aria-roledescription="classDiagram" role="graphics-document document" viewBox="0 0 546.796875 969" style="max-width: 546.796875px;" xmlns="http://www.w3.org/2000/svg" width="100%" id="export-svg"><style xmlns="http://www.w3.org/1999/xhtml">@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css"); p {margin: 0;}</style><style>#export-svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:10px;fill:#333;}#export-svg .error-icon{fill:#ffffff;}#export-svg .error-text{fill:#000000;stroke:#000000;}#export-svg .edge-thickness-normal{stroke-width:1px;}#export-svg .edge-thickness-thick{stroke-width:3.5px;}#export-svg .edge-pattern-solid{stroke-dasharray:0;}#export-svg .edge-thickness-invisible{stroke-width:0;fill:none;}#export-svg .edge-pattern-dashed{stroke-dasharray:3;}#export-svg .edge-pattern-dotted{stroke-dasharray:2;}#export-svg .marker{fill:#000000;stroke:#000000;}#export-svg .marker.cross{stroke:#000000;}#export-svg svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:10px;}#export-svg p{margin:0;}#export-svg g.classGroup text{fill:#000000;stroke:none;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:10px;}#export-svg g.classGroup text .title{font-weight:bolder;}#export-svg .nodeLabel,#export-svg .edgeLabel{color:#333;}#export-svg .edgeLabel .label rect{fill:#ffffff;}#export-svg .label text{fill:#333;}#export-svg .edgeLabel .label span{background:#ffffff;}#export-svg .classTitle{font-weight:bolder;}#export-svg .node rect,#export-svg .node circle,#export-svg .node ellipse,#export-svg .node polygon,#export-svg .node path{fill:#ffffff;stroke:#000000;stroke-width:1px;}#export-svg .divider{stroke:#000000;stroke-width:1;}#export-svg g.clickable{cursor:pointer;}#export-svg g.classGroup rect{fill:#ffffff;stroke:#000000;}#export-svg g.classGroup line{stroke:#000000;stroke-width:1;}#export-svg .classLabel .box{stroke:none;stroke-width:0;fill:#ffffff;opacity:0.5;}#export-svg .classLabel .label{fill:#000000;font-size:10px;}#export-svg .relation{stroke:#000000;stroke-width:1;fill:none;}#export-svg .dashed-line{stroke-dasharray:3;}#export-svg .dotted-line{stroke-dasharray:1 2;}#export-svg #compositionStart,#export-svg .composition{fill:#000000!important;stroke:#000000!important;stroke-width:1;}#export-svg #compositionEnd,#export-svg .composition{fill:#000000!important;stroke:#000000!important;stroke-width:1;}#export-svg #dependencyStart,#export-svg .dependency{fill:#000000!important;stroke:#000000!important;stroke-width:1;}#export-svg #dependencyStart,#export-svg .dependency{fill:#000000!important;stroke:#000000!important;stroke-width:1;}#export-svg #extensionStart,#export-svg .extension{fill:transparent!important;stroke:#000000!important;stroke-width:1;}#export-svg #extensionEnd,#export-svg .extension{fill:transparent!important;stroke:#000000!important;stroke-width:1;}#export-svg #aggregationStart,#export-svg .aggregation{fill:transparent!important;stroke:#000000!important;stroke-width:1;}#export-svg #aggregationEnd,#export-svg .aggregation{fill:transparent!important;stroke:#000000!important;stroke-width:1;}#export-svg #lollipopStart,#export-svg .lollipop{fill:#ffffff!important;stroke:#000000!important;stroke-width:1;}#export-svg #lollipopEnd,#export-svg .lollipop{fill:#ffffff!important;stroke:#000000!important;stroke-width:1;}#export-svg .edgeTerminals{font-size:11px;line-height:initial;}#export-svg .classTitleText{text-anchor:middle;font-size:18px;fill:#333;}#export-svg .node .neo-node{stroke:#000000;}#export-svg [data-look="neo"].node rect,#export-svg [data-look="neo"].cluster rect,#export-svg [data-look="neo"].node polygon{stroke:url(#export-svg-gradient);filter:drop-shadow( 0px 1px 2px rgba(0, 0, 0, 0.25));}#export-svg [data-look="neo"].node rect,#export-svg [data-look="neo"].node polygon,#export-svg [data-look="neo"].node path{stroke:url(#export-svg-gradient);filter:drop-shadow( 0px 1px 2px rgba(0, 0, 0, 0.25));}#export-svg [data-look="neo"].node .neo-line path{stroke:hsl(0, 0%, 70%);filter:none;}#export-svg [data-look="neo"].node circle{stroke:url(#export-svg-gradient);filter:drop-shadow( 0px 1px 2px rgba(0, 0, 0, 0.25));}#export-svg [data-look="neo"].node circle .state-start{fill:#000000;}#export-svg [data-look="neo"].statediagram-cluster rect{fill:#ffffff;stroke:url(#export-svg-gradient);stroke-width:1px;}#export-svg [data-look="neo"].icon-shape .icon path{fill:url(#export-svg-gradient);filter:drop-shadow( 0px 1px 2px rgba(0, 0, 0, 0.25));}#export-svg [data-look="neo"].icon-shape path{stroke:url(#export-svg-gradient);filter:drop-shadow( 0px 1px 2px rgba(0, 0, 0, 0.25));}#export-svg :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}</style><g><defs><marker orient="auto" markerHeight="240" markerWidth="190" refY="7" refX="18" class="marker aggregation classDiagram" id="export-svg_classDiagram-aggregationStart"><path d="M 18,7 L9,13 L1,7 L9,1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="28" markerWidth="20" refY="7" refX="1" class="marker aggregation classDiagram" id="export-svg_classDiagram-aggregationEnd"><path d="M 18,7 L9,13 L1,7 L9,1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="240" markerWidth="190" refY="7" refX="18" class="marker extension classDiagram" id="export-svg_classDiagram-extensionStart"><path d="M 1,7 L18,13 V 1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="28" markerWidth="20" refY="7" refX="1" class="marker extension classDiagram" id="export-svg_classDiagram-extensionEnd"><path d="M 1,1 V 13 L18,7 Z"/></marker></defs><defs><marker orient="auto" markerHeight="240" markerWidth="190" refY="7" refX="18" class="marker composition classDiagram" id="export-svg_classDiagram-compositionStart"><path d="M 18,7 L9,13 L1,7 L9,1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="28" markerWidth="20" refY="7" refX="1" class="marker composition classDiagram" id="export-svg_classDiagram-compositionEnd"><path d="M 18,7 L9,13 L1,7 L9,1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="240" markerWidth="190" refY="7" refX="6" class="marker dependency classDiagram" id="export-svg_classDiagram-dependencyStart"><path d="M 5,7 L9,13 L1,7 L9,1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="28" markerWidth="20" refY="7" refX="13" class="marker dependency classDiagram" id="export-svg_classDiagram-dependencyEnd"><path d="M 18,7 L9,13 L14,7 L9,1 Z"/></marker></defs><defs><marker orient="auto" markerHeight="240" markerWidth="190" refY="7" refX="13" class="marker lollipop classDiagram" id="export-svg_classDiagram-lollipopStart"><circle r="6" cy="7" cx="7" fill="transparent" stroke="black"/></marker></defs><defs><marker orient="auto" markerHeight="240" markerWidth="190" refY="7" refX="1" class="marker lollipop classDiagram" id="export-svg_classDiagram-lollipopEnd"><circle r="6" cy="7" cx="7" fill="transparent" stroke="black"/></marker></defs><g class="root"><g class="clusters"/><g class="edgePaths"><path marker-start="url(#export-svg_classDiagram-dependencyStart)" style="fill:none" class="edge-pattern-solid relation" data-edge="true" id="id_Parser_Interpreter_1" d="M172.893,102.135L163.682,107.779C154.471,113.423,136.048,124.712,126.836,136.522C117.625,148.333,117.625,160.667,117.625,166.833L117.625,173"/><path marker-end="url(#export-svg_classDiagram-dependencyEnd)" style="fill:none" class="edge-pattern-solid relation" data-edge="true" id="id_Parser_RobotWorldDec_2" d="M326.522,99L336.586,105.167C346.65,111.333,366.778,123.667,376.842,135C386.906,146.333,386.906,156.667,386.906,161.833L386.906,167"/><path marker-start="url(#export-svg_classDiagram-dependencyStart)" style="fill:none" class="edge-pattern-solid relation" data-edge="true" id="id_Interpreter_Console_3" d="M117.625,298L117.625,303.167C117.625,308.333,117.625,318.667,117.625,367.333C117.625,416,117.625,503,117.625,546.5L117.625,590"/><path marker-end="url(#export-svg_classDiagram-extensionEnd)" style="fill:none" class="edge-pattern-solid relation" data-edge="true" id="id_RobotWorldDec_RobotWorld_4" d="M386.906,292L386.906,298.167C386.906,304.333,386.906,316.667,386.906,326C386.906,335.333,386.906,341.667,386.906,344.833L386.906,348"/></g><g class="edgeLabels"><g transform="translate(117.625, 136)" class="edgeLabel"><g transform="translate(-21.33984375, -12)" data-id="id_Parser_Interpreter_1" class="label"><foreignObject height="24" width="42.6796875"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><span class="edgeLabel">"controla"</span></span></div></foreignObject></g></g><g transform="translate(386.90625, 136)" class="edgeLabel"><g transform="translate(-11.61328125, -12)" data-id="id_Parser_RobotWorldDec_2" class="label"><foreignObject height="24" width="23.2265625"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><span class="edgeLabel">"usa"</span></span></div></foreignObject></g></g><g transform="translate(117.625, 329)" class="edgeLabel"><g transform="translate(-11.61328125, -12)" data-id="id_Interpreter_Console_3" class="label"><foreignObject height="24" width="23.2265625"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><span class="edgeLabel">"usa"</span></span></div></foreignObject></g></g><g transform="translate(386.90625, 329)" class="edgeLabel"><g transform="translate(-22.45703125, -12)" data-id="id_RobotWorldDec_RobotWorld_4" class="label"><foreignObject height="24" width="44.9140625"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><span class="edgeLabel">"extiende"</span></span></div></foreignObject></g></g></g><g class="nodes"><g transform="translate(117.625, 232.5)" data-id="Interpreter" data-node="true" id="classId-Interpreter-2692" class="node default"><rect height="119" width="219.25" y="-59.5" x="-109.625" class="outer title-state" style=""/><line y2="-23.5" y1="-23.5" x2="109.625" x1="-109.625" class="divider"/><line y2="-7.5" y1="-7.5" x2="109.625" x1="-109.625" class="divider"/><g class="label"><foreignObject height="0" width="0"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"></span></div></foreignObject><foreignObject transform="translate( -25.0078125, -52)" height="24" width="50.015625" class="classTitle"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">Interpreter</span></div></foreignObject><foreignObject transform="translate( -102.125, 0)" height="24" width="204.25"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+Interpreter(w: Robotworld, sistema: Console)</span></div></foreignObject><foreignObject transform="translate( -102.125, 28)" height="24" width="135.34375"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+process(String: input) : String</span></div></foreignObject></g></g><g transform="translate(252.265625, 53.5)" data-id="Parser" data-node="true" id="classId-Parser-2693" class="node default"><rect height="91" width="208.6953125" y="-45.5" x="-104.34765625" class="outer title-state" style=""/><line y2="-9.5" y1="-9.5" x2="104.34765625" x1="-104.34765625" class="divider"/><line y2="6.5" y1="6.5" x2="104.34765625" x1="-104.34765625" class="divider"/><g class="label"><foreignObject height="0" width="0"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"></span></div></foreignObject><foreignObject transform="translate( -15.5703125, -38)" height="24" width="31.140625" class="classTitle"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">Parser</span></div></foreignObject><foreignObject transform="translate( -96.84765625, 14)" height="24" width="193.6953125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+command(Console sistema) : String salida</span></div></foreignObject></g></g><g transform="translate(386.90625, 663.5)" data-id="RobotWorld" data-node="true" id="classId-RobotWorld-2694" class="node default"><rect height="595" width="303.78125" y="-297.5" x="-151.890625" class="outer title-state" style=""/><line y2="-261.5" y1="-261.5" x2="151.890625" x1="-151.890625" class="divider"/><line y2="-245.5" y1="-245.5" x2="151.890625" x1="-151.890625" class="divider"/><g class="label"><foreignObject height="0" width="0"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"></span></div></foreignObject><foreignObject transform="translate( -28.51171875, -290)" height="24" width="57.0234375" class="classTitle"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">RobotWorld</span></div></foreignObject><foreignObject transform="translate( -144.390625, -238)" height="24" width="182.03125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+moveForward(steps: int, jump: boolean)</span></div></foreignObject><foreignObject transform="translate( -144.390625, -210)" height="24" width="53.078125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+turnRight()</span></div></foreignObject><foreignObject transform="translate( -144.390625, -182)" height="24" width="73.6484375"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+putChips(n: int)</span></div></foreignObject><foreignObject transform="translate( -144.390625, -154)" height="24" width="77.53125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+pickChips(n: int)</span></div></foreignObject><foreignObject transform="translate( -144.390625, -126)" height="24" width="86.4453125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+putBalloons(n: int)</span></div></foreignObject><foreignObject transform="translate( -144.390625, -98)" height="24" width="89.2265625"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+popBalloons(n: int)</span></div></foreignObject><foreignObject transform="translate( -144.390625, -70)" height="24" width="109.2109375"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+setPosition(x: int, y: int)</span></div></foreignObject><foreignObject transform="translate( -144.390625, -42)" height="24" width="80.875"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+getFacing() : : int</span></div></foreignObject><foreignObject transform="translate( -144.390625, -14)" height="24" width="113.125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+facingNorth() : : boolean</span></div></foreignObject><foreignObject transform="translate( -144.390625, 14)" height="24" width="114.8046875"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+facingSouth() : : boolean</span></div></foreignObject><foreignObject transform="translate( -144.390625, 42)" height="24" width="108.6796875"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+facingEast() : : boolean</span></div></foreignObject><foreignObject transform="translate( -144.390625, 70)" height="24" width="111.265625"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+facingWest() : : boolean</span></div></foreignObject><foreignObject transform="translate( -144.390625, 98)" height="24" width="98.6640625"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+getPosition() : : Point</span></div></foreignObject><foreignObject transform="translate( -144.390625, 126)" height="24" width="89.7578125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+getMyChips() : : int</span></div></foreignObject><foreignObject transform="translate( -144.390625, 154)" height="24" width="102.546875"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+getMyBalloons() : : int</span></div></foreignObject><foreignObject transform="translate( -144.390625, 182)" height="24" width="99.78125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+countBalloons() : : int</span></div></foreignObject><foreignObject transform="translate( -144.390625, 210)" height="24" width="107"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+chipExists() : : boolean</span></div></foreignObject><foreignObject transform="translate( -144.390625, 238)" height="24" width="288.78125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+blockedInRange(x: int, y: int, range: int, direction: int) : : boolean</span></div></foreignObject><foreignObject transform="translate( -144.390625, 266)" height="24" width="58.078125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+getN() : : int</span></div></foreignObject></g></g><g transform="translate(386.90625, 232.5)" data-id="RobotWorldDec" data-node="true" id="classId-RobotWorldDec-2695" class="node default"><rect height="119" width="90.3671875" y="-59.5" x="-45.18359375" class="outer title-state" style=""/><line y2="-23.5" y1="-23.5" x2="45.18359375" x1="-45.18359375" class="divider"/><line y2="20.5" y1="20.5" x2="45.18359375" x1="-45.18359375" class="divider"/><g class="label"><foreignObject height="0" width="0"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"></span></div></foreignObject><foreignObject transform="translate( -37.68359375, -52)" height="24" width="75.3671875" class="classTitle"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">RobotWorldDec</span></div></foreignObject><foreignObject transform="translate( -37.68359375, -12)" height="24" width="67.078125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">&lt;&gt; RobotWorld</span></div></foreignObject><foreignObject transform="translate( -37.68359375, 28)" height="24" width="69.75"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+masMetodos()</span></div></foreignObject></g></g><g transform="translate(117.625, 663.5)" data-id="Console" data-node="true" id="classId-Console-2696" class="node default"><rect height="147" width="134.78125" y="-73.5" x="-67.390625" class="outer title-state" style=""/><line y2="-37.5" y1="-37.5" x2="67.390625" x1="-67.390625" class="divider"/><line y2="34.5" y1="34.5" x2="67.390625" x1="-67.390625" class="divider"/><g class="label"><foreignObject height="0" width="0"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"></span></div></foreignObject><foreignObject transform="translate( -19.7265625, -66)" height="24" width="39.453125" class="classTitle"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">Console</span></div></foreignObject><foreignObject transform="translate( -59.890625, -26)" height="24" width="61.1484375"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">-board: Board</span></div></foreignObject><foreignObject transform="translate( -59.890625, 2)" height="24" width="73.921875"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">-images: Images</span></div></foreignObject><foreignObject transform="translate( -59.890625, 42)" height="24" width="119.78125"><div style="display: inline-block; white-space: nowrap;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel">+printOutput(salida: String)</span></div></foreignObject></g></g></g></g></g></svg>ermaid-diagram-2024-10-03-232504.svg…]()
