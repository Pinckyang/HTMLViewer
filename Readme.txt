<!--ÓÅ»¯Html½âÎö-->
<window style="width:100%;height:100%;size:auto;">
<resource type="text/javascript" src="index/main.js">
<resource type="text/css" src="index/main.css">
<header style="background-image:header-background.png">
	<title style="text-align:left">demo</title>
	<button style="background-image:closebtn.png;float:right"/>
	<button style="background-image:closebtn.png;float:right"/>
</header>
<body>
	<panel id="mainmenu">
		<button>
			<popup value="microsoft"><span>microsoft</span></popup>
			<popup value="oracle"><span>oracle</span></popup>
			<popup>
					<popup value="oracle"><span>oracle</span></popup>
					<popup value="MySql"><span>MySql</span></popup>
					<popup value="Java"><span>Java</span></popup>
			</popup>
		<button>
	<panel>
   <panel style="dock:client;size:auto">
		<textbox value="test"><!--autocomplete-->
			<popup>
				<popup value="microsoft"><span>microsoft</span></popup>
				<popup value="oracle"><span>oracle</span></popup>
				<popup>
						<popup value="oracle"><span>oracle</span></popup>
						<popup value="MySql"><span>MySql</span></popup>
						<popup value="Java"><span>Java</span></popup>
				</popup>
				<popup value="apple"><span>apple</span></popup>
				<popup value="sap"><div><h1>compex </h1><hr/><p>sap</p></div></popup>
				<panel>
					<popup value="qq"><span>qq</span></popup>
					<groupbox>
					<title>groupbox demo</title>
					<popup value="taobao"><span>taobao</span></popup>
					</groupbox>
				</panel>
			</popup>
		</textbox>
		<textbox>
			<image src="background-image:bk.png">
			<button title="..." style="float:right">
			</button>
		</textbox>
		<combobox>
			<popup value="microsoft"><span>microsoft</span></popup>
			<popup value="oracle"><span>oracle</span></popup>
		</combobox>
		<label></label>
		<tab>
            <tabItem title="tab1">
				<panel>
				</panel>
            </tabitem>
			<tabItem>
				<panel>
				</panel>
            </tabItem>
        </tab>
		<grid>
			<header>
				<column />
				<column />
				<column/>
				<column>
					<column />
					<column />
				<column>
			</header>
			<row>
				<column/>
				<column/>
				<column/>
				<column/>
				<column/>
			</row>
		</grid>
		<button title="OK">
		</button>
	</panel>
</body>
</window>