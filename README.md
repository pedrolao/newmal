

    
    
    
        /* General codes */
        @import url(https://malcat-gen.appspot.com/series?preset=dataimagelinkbefore);
        @import url(https://fonts.googleapis.com/css?family=Orbitron);
        @import url(http://fonts.googleapis.com/css?family=Amaranth);
        @import url(https://fonts.googleapis.com/css?family=Rancho);
        
        #advanced-options {
            position: fixed;
            top: 24px;
            left: 0;
            right: 0;
            background-color: rgba(255,255,255,.9);
            display: none;
            width: 860px;
            margin: 0 auto;
            padding: 25px 0px 30px;
            -moz-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
            -webkit-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
            -o-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
            -ms-box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
            box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
            color: #323232;
            text-align: left;
            font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
            z-index: 1101;
                border: none;
        background-image: url();
                background-repeat: no-repeat;
                background-size: cover;
                background-position: 50% 100%;        }
                
        #advanced-options .advanced-options-header {
            width: 750px;
            margin: 0px auto;
            padding-bottom: 4px;
            border-bottom: 1px solid #BEBEBE;
            font-size: 16px;
                color:rgba(0,0,0,.6) !important;
        }
        
        
        #advanced-options .advanced-options-header .description {
            font-size: 12px;
            font-weight: normal;
            margin-left: 8px;
                color:rgba(0,0,0,.6) !important;
        }
        
        #advanced-options .sort-widget .widget-header, #advanced-options .filter-widget .widget-header, #advanced-options .filter-widget.aired-date .text, #advanced-options .filter-widget.published-date .text {
        color:rgba(0,0,0,.6) !important;
        }
        
        #advanced-options select {
            -ms-appearance: none;
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
            background-image: url(/img/pc/ownlist/icon_pulldown_triangle.png);
            background-repeat: no-repeat;
            background-position: center right;
            background-size: 18px 8px;
            background-color: #FFFFFF;
            display: inline-block;
            height: 25px;
            padding: 4px 20px 4px 4px;
            padding-right: 4px\0;
            border: #BEBEBE 1px solid;
            border-radius: 0px;
            font-size: 12px;
        }
        #advanced-options select::-ms-expand {
            display: none;
        }
        
        #advanced-options select:disabled {
            background-image: url(/img/pc/ownlist/icon_pulldown_triangle_disable.png);
            color: #9B9B9B;
        }
        
        #advanced-options input[type=text] {
            padding: 4px;
            border: #BEBEBE 1px solid;
        }
        
        #advanced-options input:focus {
            outline: none;
        }
        
        
        /* sort */
        #advanced-options .sort-widget {
            margin: 0px auto;
            padding: 12px 0px 0px;
            width: 750px;
        }
        #advanced-options .sort-widget:last-of-type {
            padding-bottom: 45px;
        }
        
        #advanced-options .sort-widget select {
            width: 172px;
            margin-right: 8px;
        }
        
        #advanced-options .sort-widget input[type=radio] {
            display: none;
        }
        #advanced-options .sort-widget input[type=radio] + label {
            background-color: #FFFFFF;
            display: inline-block;
            width: 56px;
            padding: 5px 0px;
            border: #BEBEBE 1px solid;
            border-radius: 4px;
            color: #323232;
            font-size: 12px;
            text-align: center;
            cursor: pointer;
        }
        #advanced-options .sort-widget input[type=radio]:checked + label {
            background-color: #244291;
            border: #244291 1px solid;
            color: #FFFFFF;
        }
        #advanced-options .sort-widget input[type=radio]:disabled + label {
            border: #BEBEBE 1px solid;
            color: #9B9B9B;
        }
        #advanced-options .sort-widget input[type=radio]:checked:disabled + label {
            background-color: #FFFFFF;
            border: #BEBEBE 1px solid;
            color: #9B9B9B;
        }
        
        /* filter */
        #advanced-options .filter-widget {
            margin: 0px auto;
            padding: 12px 0px 0;
            width: 750px;
        }
        
        #advanced-options .filter-widget select {
            margin-right: 8px;
            font-size: 12px;
        }
        
        #advanced-options .filter-widget.title input[type=text] {
            width: 360px;
        }
        
        #advanced-options .filter-widget.airing-status select,
        #advanced-options .filter-widget.publishing-status select {
            width: 152px;
        }
        
        #advanced-options .filter-widget.producer select,
        #advanced-options .filter-widget.magazine select {
            width: 360px;
        }
        
        #advanced-options .filter-widget.aired-date select.year,
        #advanced-options .filter-widget.published-date select.year {
            width: 80px;
        }
        
        #advanced-options .filter-widget.aired-date select.month,
        #advanced-options .filter-widget.published-date select.month,
        #advanced-options .filter-widget.aired-date select.day,
        #advanced-options .filter-widget.published-date select.day {
            width: 60px;
        }
        
        #advanced-options .filter-widget.aired-date .text,
        #advanced-options .filter-widget.published-date .text {
            display: inline-block;
            margin-right: 4px;
            font-size: 12px;
        }
        
        #advanced-options .filter-widget.aired-season select.year {
            width: 80px;
        }
        
        #advanced-options .filter-widget.aired-season select.season {
            width: 110px;
        }
        
        #advanced-options .sort-widget .widget-header,
        #advanced-options .filter-widget .widget-header {
            display: inline-block;
            width: 110px;
            font-size: 12px;
            font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
        }
        
        #advanced-options .sort-widget:last-of-type,
        #advanced-options .filter-widget:last-of-type {
            padding-bottom: 40px;
        }
        
        #advanced-options .advanced-options-button {
            width: 750px;
            margin: 0px auto;
            padding: 12px 0px 0px;
            border-top: 1px solid #BEBEBE;
            text-align: center;
        }
        
        #advanced-options .btn-apply,
        #advanced-options .btn-clear {
            background-color: rgba(0,0,0, 0.8);
            display: inline-block;
            width: 135px;
            margin: 0 4px;
            padding: 6px 0px;
            border-radius: 4px;
            font-size: 12px;
            color: #FFFFFF;
            text-align: center;
            -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
        }
        
        #advanced-options .btn-apply:hover,
        #advanced-options .btn-clear:hover {
          background-color: rgba(0,0,0, 0.8);
        }
        
        
        
        /**
         * General Styles
         */
         
         
        td {
            line-height: 1.5em;
                height: 25px !important;
        }
        
        a {
            color: #fff;
            text-decoration: none;
        }
        a:hover {
            color: #fff !important;
            text-decoration: none;
        }
        
        #footer-block {
            padding: 15px 0;
            background-color: #244291;
            color: #FFFFFF;
            font-family: Avenir, "lucida grande", tahoma, verdana, arial, sans-serif;
                display:none;
        }
        
        #copyright {
            font-size: 12px;
            color: #FFFFFF;
            padding-top: 3px;
            text-align: center;
        }
        
        /*
         * Header
         */
        .header a {
            font-weight: bold;
            color: #fff !important;
        }
        .header a:hover {
            text-decoration: underline;
        }
        
        .header {
            position: absolute;
            color: #fff;
            display: block;
            width: 100%;
            height: 50px;
            margin: 0 auto
                border:none;
                background: -webkit-linear-gradient(rgba(0,0,0,.5), transparent); /* For Safari 5.1 to 6.0 */
            background: -o-linear-gradient(rgba(0,0,0,.5), transparent); /* For Opera 11.1 to 12.0 */
            background: -moz-linear-gradient(rgba(0,0,0,.5), transparent); /* For Firefox 3.6 to 15 */
            background: linear-gradient(rgba(0,0,0,.5), transparent); /* Standard syntax */
                -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
                z-index: 40;
        }
        
        .header:hover {background-color:rgba(0,0,0,.5);
          -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
        
        }
        
        .header .header-menu {
            position: absolute;
            top: 5px;
            right: 4px
        }
        .header .header-menu.other {
            top: 5px;
        }
        
        
        
        .header .header-menu .header-info {
            font-size: 10px;
            margin-top: 6px;
            margin-right: 15px;
            text-align: right;
        }
        
        .header .username {
            font-weight: bold;
        }
        
        .header .header-menu .list-menu {
            position: absolute;
            top: 25px;
            right: -4px;
            background-color: rgba(255,255,255,.8);
            display: none;
            border: none !important;
            -moz-box-shadow: rgba(0, 0, 0, 0.4) 0 0 10px;
            -webkit-box-shadow: rgba(0, 0, 0, 0.4) 0 0 10px;
            box-shadow: rgba(0, 0, 0, 0.4) 0 0 10px;
            z-index: 1;
        }
        
        .header .header-menu .list-menu .icon-menu {
            display: block;
            width: 150px;
            height: 30px;
            color: #000;
            font-size: 14px;
            font-weight: bold;
            text-decoration: none;
            -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
        }
        
        .header .header-menu .list-menu .icon-menu:hover {
            background-color: rgba(0,0,0,.5);
        }
        
        .header .header-menu .list-menu .icon-menu svg.icon {
            position: absolute;
            fill: rgba(0,0,0,.5);
            left: 12px;
            top: 4px;
        }
        
        .header .header-menu .list-menu .icon-menu:hover svg.icon {
            fill: rgba(255,255,255,1) !important;
        }
        
        .header .header-menu .list-menu .icon-menu .text {
            position: absolute;
            left: 52px;
            top: 6px;
        }
        
        .header .header-menu .list-menu .icon-menu:hover .text {color:rgba(255,255,255,1) !important;}
        
        .header .header-menu .btn-menu {
        display: block;
            text-align: right;
        color: rgba(0,0,0,0.7) !important;
        font-size: 12px !important;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;
        }
        
        #header-menu-dropdown > a {color: rgba(0,0,0,.5) !important;}
        
        /* svg.icon.icon-manga-list {color: rgba(0,0,0,.5) !important;} */
        
        /**
         * Floating Menu
         */
        /**
         * Floating Menu
         */
        .list-menu-float:before
        {content: "\f0c9";
        font-family: 'FontAwesome' !important;
        display: block;
        text-align: center !important;
        text-indent: 10px;
        color: #fff !important;
        font-size:1.5em !important;
        height: 50px;
        width: 40px;
        line-height: 50px;}
        
        .list-menu-float:hover:before {
        font-size:1.7em !important;
        text-shadow: 0 0 2px #fff, 0 0 1px #fff, 1px 1px 7px #fff, 0 0 0 #fff;
        -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
        }
        
        .list-menu-float
        {position: absolute;
        top: 0px;
        left:0px;
        width: 50px;
        border: none;
        opacity: 1;
        height: 40px !important;
        z-index: 100;
         
        }
        
        .list-menu-float .icon-menu 
        {display: block;
        width: 120px;
        background-color: #dfdfdf;
        height: 30px;
        line-height: 30px;
        text-indent: 10px;
        opacity:0;
         }
        
        .list-menu-float:hover .icon-menu
        {opacity:0;
        -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;}
        
        .list-menu-float .icon-menu.profile
        {background-image: none !important;} 
        
        .list-menu-float .icon-menu.profile:before
        {position:absolute;
        width:120px !important;
        content: "\f007\00a0Profile";
        font-family: 'FontAwesome' !important;
        margin-top:5px !important;
        margin-left:-65px !important;
        color: #000;
        text-align: center;}
        
        .list-menu-float .icon-menu .text
        {opacity: 1;
        width: auto;
        left: 20px;
        top: 0;
        color: #555555;}
        
        .list-menu-float .icon-menu:hover
        {width: 120px !important;
        background-color:rgba(0,0,0,.5) !important;}
        
        .list-menu-float .icon-menu:hover .text, .list-menu-float .icon-menu:hover:before, .list-menu-float .icon-menu:hover:after
        {color: #fff;
        width: auto;}
        
        .list-menu-float .icon-menu.logout
        {border-radius: 0 0 4px 4px;}
        
        .list-menu-float .icon-menu.setting
        {display:none;}
        
        .list-menu-float .icon-menu svg.icon
        {top: 7px !important;
        left: 5px !important;
        width: 15px;
        height: 15px;}
        
        .list-menu-float .icon-menu.setting svg.icon-setting {display:none;}
        /**
         * List Container
         */
        
        .list-container {
            position: absolute;
            background-color: transparent !important;
            width: 1000px;
            left: 0;
            right: 0;
            margin: auto;
                margin-top:100px;
                box-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;
                border:none !important;
                margin-bottom:30px;
        }
        
        /**
         * List Container - Cover Block
         */
        .cover-block {
                position:relative;
            display: block;
            width: 1000px;
            margin: 0 auto;
                height:auto;
            text-align: center;
            vertical-align: middle;
                
        }
        
        .cover-block .image-container {
            display: block;
            width: 1000px;
                height:auto;
                padding-top:0;
        }
        
        .cover-block .image-container.hide {
            display: none;
        }
        
        .cover-block .image-container img {
            max-width: 1000px;
                height: auto;
        }
        
        /* cover image */
        
        #cover-image{
        
          margin:auto;
          width:1000px !important;
          height:auto;
          background-color:transparent;
          background-size: cover !important;
          background-position: 50% 50%;
         
        }
        
        /* setting icon */
        .cover-block .image-container .btn-list-setting {
            display: none;
        }
        
        .cover-block .image-container:hover .btn-list-setting {
            display: block;
            position: absolute;
            top: 20px;
            right: 28px;
            padding: 8px;
            border: rgba(255,255,255,0) 1px solid;
            font-size: 14px;
            color: #ffffff;
            font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
        }
        
        .cover-block .image-container .btn-list-setting:hover {
            position: absolute;
            top: 20px;
            right: 28px;
            background-color: rgba(0,0,0,0.6);
            padding: 8px;
            border: none;
            -moz-box-shadow: 0 0 4px #000000;
            -webkit-box-shadow: 0 0 4px #000000;
            -o-box-shadow: 0 0 4px #000000;
            -ms-box-shadow: 0 0 4px #000000;
            box-shadow: 0 0 4px #000000;
            font-size: 14px;
            color: #ffffff;
            text-shadow: #323232 1px 1px 1px;
        }
        
        .cover-block .image-container .btn-list-setting .fa-camera {
            font-size: 16px;
            -moz-text-shadow: #000000 1px 1px 3px;
            -webkit-text-shadow: #000000 1px 1px 3px;
            -o-text-shadow: #000000 1px 1px 3px;
            -ms-text-shadow: #000000 1px 1px 3px;
            text-shadow: #000000 1px 1px 3px;
            -ms-filter:"progid:DXImageTransform.Microsoft.DropShadow(color=#000000,offx=1,offy=1)";
        }
        
        .cover-block .image-container .btn-list-setting .icon-plus-circle {
            position: absolute;
            top: 4px;
            left: 18px;
            background-color: rgba(0,0,0,0.6);
            border-radius: 50%;
            -moz-box-shadow: -1px 1px 0px 0px #323232;
            -webkit-box-shadow: -1px 1px 0px 0px #323232;
            -o-box-shadow: -1px 1px 0px 0px #323232;
            -ms-box-shadow: -1px 1px 0px 0px #323232;
            box-shadow: -1px 1px 0px 0px #323232;
            font-size: 10px;
        }
        
        .cover-block .image-container .btn-list-setting .text {
          display: none;
        }
        
        .cover-block .image-container .btn-list-setting:hover .text {
          display: inline-block;;
          margin-left: 4px;
        }
        
        
        /**
         * List Container - Status Menu
         */
        .status-menu-container {
            width: 1000px;
            height: 40px;
            background-color: rgba(255,255,255,.9);
            border-bottom: none;
            z-index: 1
        }
        
        .status-menu-container.fixed {
            position: absolute;
            display: none !important;
            top: 0;
        }
        
        .status-menu-container.fixed + div.list-block {
            margin-top: 0;
        }
        
        .status-menu-container .status-menu {
            display: table;
            margin: 0 auto;
            border-collapse: separate;
            border-spacing: 0px 0;
        }
        
        .status-menu-container .status-menu .status-button {
            position: relative;
            display: table-cell;
            padding: 10px;
            left: 17px !important;
            font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
            text-align: center;
            vertical-align: middle;
                 padding: 1.2em 10px;
            line-height: 1.105em;
            font-size: 1.1em;
            color: #9B9B9B;
        }
        
        .status-menu-container .status-menu .status-button.on {
            color: #000;
            font-weight: bold;
        }
        
        .status-menu-container .status-menu .status-button:hover {
            background-color: rgba(0,0,0,.5);
                color: #fff;
            -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
        }
        
        .status-menu-container .status-menu .status-button.on:after, .status-menu .status-button:hover:after {
            opacity: 1
        }
        
        .status-menu-container .status-menu .status-button.watching:before, .status-menu-container .status-menu .status-button.reading:before {
        content: "\f152\00a0\00a0";
        float: left;
        font-size: 1.5em;
        font-family: 'FontAwesome' !important;
        }
        
        .status-menu-container .status-menu .status-button.completed:before {
        content: "\f05d\00a0\00a0";
        float: left;
        font-size: 1.5em;
        font-family: 'FontAwesome' !important;
        }
        
        .status-menu-container .status-menu .status-button.onhold:before {
        content: "\f017\00a0\00a0";
        float: left;
        font-size: 1.5em;
        font-family: 'FontAwesome' !important;
        }
        
        .status-menu-container .status-menu .status-button.plantowatch:before, .status-menu-container .status-menu .status-button.plantoread:before {
        content: "\f073\00a0\00a0";
        float: left;
        font-size: 1.5em;
        font-family: 'FontAwesome' !important;
        }
        
        .status-menu-container .status-menu .status-button.dropped:before {
        content: "\f00d\00a0\00a0";
        float: left;
        font-size: 1.5em;
        font-family: 'FontAwesome' !important;
        }
        
        .status-menu-container .status-menu .status-button.all_anime:before {
        content: "\f022\00a0";
        float: left;
        font-size: 1.5em;
        font-family: 'FontAwesome' !important;
        }
        
        .status-menu-container .status-menu .status-button:after {display:none !important;}
        
        /*scroll bar*/
        
        ::-webkit-scrollbar
        {height: 7px;
        width: 7px;
        background-color: #f5f5f5;}
        ::-webkit-scrollbar-thumb
        {border: 2px solid #f5f5f5;
        background-color: #9B9B9B;}
        
        /**
         * List Container - Status Menu - Search
         */
        .status-menu-container .search-container {
            position: absolute;
            right: 5px;
                z-index:20;
        }
        .status-menu-container .search-container #search-button {
            display: inline-block;
            height: 22px;
            margin-top: 10px;
            color: #787878;
            font-size: 1.6em;
            vertical-align: middle;
        }
        
        .status-menu-container .search-container #search-box {
            display: inline-block;
            width: 0;
            height: 22px;
            overflow: hidden;
            margin-top: 5px;
            -webkit-transition: width 0.3s;
            -moz-transition: width 0.3s;
            transition: width 0.3s;
            -webkit-backface-visibility: hidden;
            vertical-align: middle;
        }
        
        .status-menu-container .search-container #search-box.open {
            display: inline-block;
            width: 130px;
        }
        
        .status-menu-container .search-container #search-box input {
            width: 100%;
            height: 100%;
            box-sizing: border-box;
        }
        
        
        /**
         * List Container - List Block
         */
        .list-block {
            margin: 0;
                min-height:265px;
        }
        
        .list-unit {
            background-color:rgba(255, 255, 255, .2);
                margin: auto;
                width: 1000px;
        }
        
        /**
         * List Container - List Status Title (with Stats)
         */
        .list-unit .list-status-title {
            position: relative;
            display: table-cell;
            background-color: transparent;
            width: 1000px;
           height:0px !important;
        }
        
        .list-unit .list-status-title .text {
            display: block;
            width: 1000px;
            height: 38px !important;
            font-size: 16px;
            color: #fff;
            font-family: 'Helvetica neue', Helvetica, "lucida grande", tahoma, verdana, arial, sans-serif;
            text-align: center;
            vertical-align: middle;
                letter-spacing: -0.1em;
        text-transform: uppercase;
        text-align: center;
        font-weight: 200;
        font-family:Helvetica neue;
        border:none;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #FFF !important;
         font-style: italic;
         background-color: transparent;
        margin-top: 120px !important;
        
        }
        
        
        .list-unit .list-status-title .stats {
            position: absolute;
            height: 39px;
            line-height: 39px;
                width:180px;
            right: -25px;
                margin-top: -197px;
                z-index: 1;
        }
        
        .list-unit .list-status-title .stats a {
            color: #9B9B9B;
                padding:8px;
                margin:0 !important;
        }
        
        .list-unit .list-status-title .stats a.filterd {
            text-shadow: 0px 0px 2px #FFF;
        }
        
        .list-unit .list-status-title .stats a:hover {
                background:rgba(0,0,0,.5);
        padding:8px;
         -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;
        }
        
        
        .list-unit .list-stats {
        background-color: rgba(255,255,255,.8); 
        margin-top: -155px !important;
        color : #000;
        height: 25px;
        margin:auto;
        position: absolute;
        width: 1000px;
        z-index: 1 !important;
        }
        
        
        
        
        /**
         * List Container - List Table
         */
        
        .list-table {
            width: 100%;
            margin: 0 auto;
            border-collapse: collapse;
                background-color:transparent !important;
                color: #fff !important;
                border:none;
        }
        
        .list-table > tbody:nth-of-type(2n+1) {
            background-color: rgba(0, 0, 0, .5) !important;
        
        
        }
        
        .list-table > tbody:nth-of-type(2n) {
        background-color: rgba(0, 0, 0, .5) !important;
        
        }
         
         /**
         * List Container - List Table - Header
         */
         
        .list-table .list-table-header:before {content: "\f0dc\00a0SORT";
        display: block;
        text-align: center !important;
        font-family: 'FontAwesome' !important;
        text-indent: 0px;
        color: #9B9B9B !important;
        font-weight: 700 !important;
        width: 57px;
        line-height: 40px;
        height:40px;
        margin-left:0px !important;
        }
        
        .list-table .list-table-header:hover:before {color:#fff !important;
        background-color:rgba(0,0,0,.5);}
        
        .list-table .list-table-header {
        position: absolute;
            display: block;
        margin-left:0;
        margin-top:-198px;
        z-index:200 !important;        
        }
        
        .list-table .list-table-header .header-title {
             background: #F6F6F6 url("/img/pc/ownlist/bar-table-header.png") no-repeat right 7px / 1px 22px;
            display: block;
            border-bottom: 0;
            height: 39px;
            text-align: center;
            vertical-align: middle;
                z-index:60 !important;
                opacity:0;
        }
        
        .list-table .list-table-header:hover .header-title {opacity:1;
        -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out;}
        
        .list-table .list-table-header .header-title:last-child {
            background-image: none;
        }
        
        .list-table .list-table-header .header-title.status,.list-table .list-table-header .header-title.number,.list-table .list-table-header .header-title.image,.list-table .list-table-header .header-title.tags  {
            background-image: none;
            display:none !important;
        }
        
        .list-table .list-table-header .header-title.title {
            text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.score {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.type {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.progress {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.chapters {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.volumes {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.rated {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.started {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.finished {
          text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.days {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.storage {
            text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.retail {
           text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title.priority {
            text-align: center;
                width:90px;
                line-height: 40px;
                padding:0 !important;
        }
        
        .list-table .list-table-header .header-title .link {
            font-size: 11px;
            color: #323232;
            text-decoration: none
                height:40px;
                width:90px;
        }
        
        .list-table .list-table-header .header-title .link.sort {
            position: relative;
            display: inline-block;
            color: #323232;
                height:40px;
                width:90px;
            white-space: nowrap;
            -moz-transition-property: all;
            -o-transition-property: all;
            -webkit-transition-property: all;
            transition-property: all;
            -moz-transition-duration: 0.3s;
            -o-transition-duration: 0.3s;
            -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
            -moz-transition-timing-function: ease-in-out;
            -o-transition-timing-function: ease-in-out;
            -webkit-transition-timing-function: ease-in-out;
            transition-timing-function: ease-in-out
        }
        
        .list-table .list-table-header .header-title .link.sort:hover {
            color: #000;
                background-color: rgba(0,0,0,.5);
                height:40px;
                width:90px;
        }
        
        .list-table .list-table-header .header-title .sort-icon {
            color: #fff;
        }
        
        
        /* customize list */
        
        
        .list-table .list-table-data:hover {
        box-shadow: 0 0 2px #fff, 0 0 1px #cd06eb, 1px 1px 7px #fff, 0 0 0 #cd06eb !important;
            transition: .2s linear;
        }
        
        
        .list-table .list-table-data:hover .data.title  {
          text-shadow: 0 0 2px #000, 0 0 1px #000, 0 1px 7px #000, 0 0 0.5px #000;
          transition: .1s linear;
          }
        
        
        .header a:hover,.list-table .list-table-data a:not(.edit-disabled):hover {
        text-decoration:underline;
        }
        
        
        /**
         * List Container - List Table - Items
         */
        
        .list-table .list-table-data .data {
            display: table-cell;
            padding: 4px 0;
            text-align: center;
            vertical-align: middle;
                color: #fff !important;
                border:none;
        }
        
        .list-table .list-table-data a:not(.edit-disabled):hover {
            text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;
            color: #fff !important;
        }
        
        .list-table .list-table-data a.edit-disabled {
            cursor: text;
            color: #fff !important;
        }
        
        .list-table .list-table-data .edit-disabled {
                color: #fff !important;
        }
        
        
        
        .list-table .list-table-data .data.title .link {
            font-size: 17px !important;
         text-decoration: none !important;
        font-family: 'Helvetica Neue', sans-serif;
        font-weight:100 !important;
        transition: all 0.1s ease 0s;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000 !important;
        }
        
        .list-table .list-table-data:hover .data.title .link {
          letter-spacing: 0.5px;
          transition: all 0.1s ease 0s;
        }
          
        .list-table .list-table-data .data.title .rewatching, .list-table .list-table-data .data.title .rereading, .list-table .list-table-data .data.title .content-status {
            text-shadow: 0 0 2px #F54EE7, 0 0 1px #F54EE7, 1px 1px 7px #E32BD4, 0 0 0 #F54EE7 !important;
                color: #fff !important;
            font-size: 0.9em;
                text-align:center !important;
                vertical-align:middle !important;
                width: 180px !important;
                display:block;
                opacity:0;
        }
        
        .list-table .list-table-data:hover .data.title .rewatching, .list-table .list-table-data:hover .data.title .rereading, .list-table .list-table-data:hover .data.title .content-status {
            text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000 !important;
                color: #fff !important;
            font-size: 1.0em;
                right: -10px !important;
                top: 30px !important;
                vertical-align:middle !important;
                width: 80px !important;
                text-align:right;
                display:block;
                opacity:1;
                position:absolute;
                font-weight: bold;
        }
        
        .list-table .list-table-data .data.score .link {
            font-size: 1.2em;
            font-weight: bold
        }
        
        td.td1.borderRBL {
        color: #fff !important;
        }
        
        /* */
        .list-table .list-table-data .data.title .more {
            position: relative;
        }
        
        .list-table .more-info {
            display: none;
        }
        
        .list-table .more-info .more-content {
            padding: 10px;
        }
        
        /* */
        
        .list-table .list-table-data .data.status {
            width: 4px;
                z-index:9 !important;
        }
        
        .list-table .list-table-data .data.status .text {
            display: none
        }
        
        .list-table .list-table-data .data.status.reading, .list-table .list-table-data .data.status.watching {
            background-color: #2db039
        }
        
        .list-table .list-table-data .data.status.plantoread, .list-table .list-table-data .data.status.plantowatch {
            background-color: #c3c3c3
        }
        
        .list-table .list-table-data .data.status.completed {
            background-color: #26448f
        }
        
        
        .list-table .list-table-data .data.status.onhold {
            background-color: #f1c83e
        }
        
        .list-table .list-table-data .data.status.dropped {
            background-color: #a12f31
        }
        
        
        /*list status*/
        .list-table .list-table-data:hover .data.status.completed:before, .list-table .list-table-data:hover .data.status.reading:before, .list-table .list-table-data:hover .data.status.watching:before,.list-table .list-table-data:hover .data.status.plantoread:before, .list-table .list-table-data:hover .data.status.plantowatch:before,.list-table .list-table-data:hover .data.status.onhold:before,.list-table .list-table-data:hover .data.status.dropped:before {
        height: 25px;
        width:25px !important;
        background-position:50% 50%;
        background-repeat: no-repeat;
        background-size:15px 17px;
        display: inline-block !important;
        position: relative;
        left: 0 !important;
        top: 0 !important;
        z-index: 10 !important;
        content: "";
        pointer-events: none;
        opacity: 1 !important; }
        
        .list-table .list-table-data:hover .data.status.completed:before {
        background-color: #26448f !important;
        color:#fff;
        content: "\f05d";
        font-size: 1.5em;
        line-height:25px;
        font-family: 'FontAwesome' !important;
        }
        
        .list-table .list-table-data:hover .data.status.watching:before, .list-table .list-table-data:hover .data.status.reading:before
        {background-color: #2db039 !important;
        color:#fff;
        content: "\f152";
        font-size: 1.5em;
        line-height:25px;
        font-family: 'FontAwesome' !important;}
        
        .list-table .list-table-data:hover .data.status.plantowatch:before, .list-table .list-table-data:hover .data.status.plantoread:before
        {background-color: #c3c3c3 !important;
        color:#fff;
        content: "\f073";
        font-size: 1.5em;
        line-height:25px;
        font-family: 'FontAwesome' !important;}
        
        .list-table .list-table-data:hover .data.status.onhold:before
        {background-color: #f1c83e !important;
        color:#fff;
        content: "\f017";
        font-size: 1.5em;
        line-height:25px;
        font-family: 'FontAwesome' !important;}
        
        .list-table .list-table-data:hover .data.status.dropped:before
        {background-color: #a12f31 !important;
        color:#fff;
        content: "\f00d";
        font-size: 1.5em;
        line-height:25px;
        font-family: 'FontAwesome' !important;}
        
        
        .link.sort + a {display: none;} /* remove watch buttons */
        
        
        
        /* tags */
        
        .data.tags:before
        {margin:0;
        width: 12px !important;
        padding: 5px 0 !important;
        z-index: 10;}
        
        data.tags:hover:before
        {width: 15px;
        padding: 5px 5px 5px 4px !important;
        font-size: 1.1em;
        
        color: #fff;
        cursor: default;}
        
        .data.tags:before, .data.tags:hover:before
        {position: absolute;
        left: 25px;
        top: 0px;
        height: 15px !important;}
        
        .list-item:hover .data.tags:before
        {opacity: 1;}
        
        
        
        .data.tags
        {opacity: 1;
        height: 100%;
        width: 0;
        z-index: 25;}
        
        .data.tags *
        {z-index: 25;
        transition: opacity .15s ease-in-out;
        color:#000;
        margin-top:25px;}
        
        .data.tags:hover *
        {width: 180px;
        opacity: 1;
        }
        
        .data.tags a
        {
        text-align:left;
        font-size: 1.0em; 
        color: #000; 
        white-space:nowrap;
        }
        
        .data.tags:before
        {content: '';
        border: none;
        opacity: 0;
        margin-top: 0px;
        background-image:url(http://i.imgur.com/WC8S1cb.png);
        background-size: 15px 14px;
        background-repeat:no-repeat;
        background-position:50% 50%;
        letter-spacing: -1px;
        background-color: rgba(206, 140, 16,1);
        width: 25px !important;
        height:15px !important;
        display:block;}
        
        .data.tags:hover:before
        {content: '';
        background-image:url(http://i.imgur.com/WC8S1cb.png);
        background-size: 15px 14px;
        background-repeat:no-repeat;
        background-position:50% 50%;
        letter-spacing: -1px;
        color: #6ebcf4;
        width: 25px !important;
        height:15px !important;
        display:block;}
        
        
        .data.tags textarea
        {position: absolute; font-family: monospace!important;
        z-index: 50;}
        
        .edit-transition.edit-leave
        {display: none;}
        
        
        .tags .edit
        {position: absolute;
        top: -25px;
        left: 25px;
        width: 25px !important;
        height: 25px;
        font-size: 0 !important;}
        
        .tags .edit:hover
        {width: 25px !important;}
        
        
        div[class*="tags-"]
        {overflow: hidden;
        border-radius: 2px;
        height: 200px;
        background: rgba(255, 255, 255, 0.9);
        
        }
        
        [href*="&tag="]
        {white-space: normal !important;
        text-transform: none;
        pointer-events: none;}
        
        
        
        /*List unit*/
        
        
        .list-table
        {display: table-row;}
        
        .data.status, .data.image ~ td
        {position: absolute;}
        
        .list-table .list-table-data .data.image a
        {border-radius: 2px;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center center !important;}
        
        .list-item
        {margin: 10px;
        position: relative;
        float: left;
        }
        
        .list-item .data
        {opacity: 1;}
        
        .list-item .list-table-data
        {border-radius: 2px;
        position: absolute;}
        
        .list-table .list-table-data .data
        {padding: 0;
        border-bottom: none;}
        
        .list-item .data.image
        {z-index: 0 !important;
        position: absolute;}
        
        .list-item .data.image img
        {height: 100%; width: 100%;}
        
        .list-item, .list-item .list-table-data,.list-item .data.title, .data.tags textarea
        {width: 180px !important;
        height: 283px !important;}
        
         .data.image{overflow:hidden;
         width: 180px !important;
        height: 225px !important;
        margin-top:0px;
        }
        
        .data.image a:before
        {content: "";
        display: inline-block !important;
        position: relative;
        width: 180px;
        height: 225px;
        background-color: rgba(0,0,0,.3);
        background-position: center !important;
        background-repeat: no-repeat !important;
        background-size: cover;
        z-index: 5;
        box-shadow: 0 0 5px black inset; 
        box-sizing: border-box;
        transition: all .2s ease-in-out;}
        
        
        
        .list-table .list-table-data:hover .data.image a:before {
                transition: all .2s ease-in-out;
        transform: scale(1.1);
        }
        
        .list-item .data.number {
        
        padding-left: 7px;
        text-align:left !important;
        line-height:25px !important;
        width:173px;
        height:25px;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;
                background: -webkit-linear-gradient(rgba(0,0,0,.7), transparent); 
            background: -o-linear-gradient(rgba(0,0,0,.7), transparent); 
            background: -moz-linear-gradient(rgba(0,0,0,.7), transparent);
            background: linear-gradient(rgba(0,0,0,.7), transparent); 
        z-index: 1 !important;
        position: absolute;
        
        }
        
        
        /*data item position*/
        .data.title > a
        {position: absolute;
        z-index: 5;
        top: 230px;
        height: 35px !important;
        line-height: 1.05em;
        text-align:center;
        vertical-align:middle;
        width: 100%;
        overflow:hidden;}
        
        .list-item .data.title
        {box-sizing: border-box;
        border-radius: 2px;
        height: 215px !important;padding: 0 !important}
        
        .list-table .list-table-header .header-title.studio {
          display:none !important;
        }
        
        
        .list-item .data.studio {
        width: 180px;
        margin:0;
        height: 30px !important;
        top: 195px;
        z-index: 1 !important;
        display: table;
        background-color: transparent;
                background: rgba(0,0,0,0);
                background: -moz-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
                background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(0,0,0,0)), color-stop(100%, rgba(0,0,0,.7)));
                background: -webkit-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
                background: -o-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
                background: -ms-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);
                background: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(0,0,0,.7) 100%);        
        }
        
        .list-item .data.studio span {
        display: table-cell;
        vertical-align: middle;
        }
        
        .list-item .data.score
        {right: 5px;
        width: 15px; text-align: left;
        bottom: -5px !important;
        }
        
        .list-item .data.score * {
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #FFF !important;
        }
        
        .list-item .data.studio * {
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000 !important;
        font-weight: bold !important;
        color: #fff !important;
        }
        
        .score select.edit-transition
        {margin-left: -5px;}
        
        .data.progress, .data.volume, a[href*="%C2%9"]
        {
        bottom: -5px !important;
        transition: opacity .15s ease-in-out;
        padding-left:5px !important;}
        
        .data.chapter {
        bottom: -5px !important;
        padding-left:70px !important;
        }
        
        .list-item .data.type
        {right: 5px !important;
        width:50px !important;
        top: 5px !important;
        text-align:right !important;
        font-size: 1em;
        transition: opacity .15s ease-in-out;
        font-weight:bold;
        opacity: 1;
        z-index:2;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000;
        }
        
        
        /* add edit more */
        
        .list-table .list-table-data .data.title .add-edit-more {
            top:0;
                left: 50px;
           font-size:0 !important;
           position: absolute;
           z-index: 10 !important;
           text-align:center !important;
                vertical-align:middle !important;
                width: 25px !important;
                height: 25px !important;
                display:block;
          
        }
        
        
        .add-edit-more {
            opacity: 0;
                transition: all 0s ease 0s;
        
        }
        .list-item:hover .add-edit-more {
            opacity: 1;
        }
        
        .list-table .list-table-data .data.title .edit a {
                background-image: url(http://i.imgur.com/OT1yCLP.png);
                display: block;
        width: 25px;
        height: 25px;
                background-size: 15px 15px;
                background-repeat: no-repeat;
                background-color: rgba(8, 142, 160,1);
        background-position: 50% 50%;
        }
        
        .list-table .list-table-data .data.title .more a {
                background-image: url(http://i.imgur.com/cUAaila.png);
                display: inline-block;
        width: 15px;
        height: 15px;
                background-size: cover;
                color: transparent !important;
                display:none;
        }
        
        .list-table .list-table-data .data.title .add a {
                background-image: url(http://i.imgur.com/AoTgUAL.png);
                display: block;
        width: 25px;
        height: 25px;
                background-size: 15px 15px;
                background-repeat: no-repeat;
                background-color: rgba(8, 142, 160,1);
        background-position: 50% 50%;
        }
        
        
        
        /* */
        
        
        
        .list-unit .loading-space {
             margin: 0px;
            height: 20px;
            font-size: 20px;
            text-align: center;
        }
        
        /*override codes*/
        .header .header-info > a {color: rgba(255,255,255,1) !important;}
        .header .header-info {color: rgba(255,255,255,0.8) !important;}
        .header .header-menu {color: rgba(255,255,255,0.8) !important;}
        .header .header-menu .btn-menu {color: rgba(255,255,255,0.8) !important;}
        .username {color: rgba(255,255,255,0.8) !important;}
        #header-menu-button {color: rgba(255,255,255,0.8) !important;}
        .header a {
            font-weight: bold;
            color: #fff !important;
        }
        
        /*profile image & name */
        
        .cover-block::after {
        height: 120px !important;
        width: 120px! important;
        background-repeat: no-repeat;
        background-size: contain;
        position: absolute;
        display:block !important;
        margin-left:57px;
        margin-top:-70px;
        content: "";
        z-index: 2 !important;
        padding: 5px;
        background-color:#fff;
        box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.3);
        border-radius:5px;
        border: 2px solid #fff;
        }
        
        .cover-block::before {
        position: absolute;
        display:block !important;
        margin-left:200px;
        bottom:10px;
        width: 300px;
        color: #ffffff;
        font-size: 29px !important;
        font-family: tahoma;
        text-align: left;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #000 !important;
        letter-spacing: 0 !important; 
        }
        
        /* */
        .header .header-title {
        position: absolute;
        top: 0px;
        left: 40px;
        background-image: url("http://i.imgur.com/39cRtfK.png");
        background-position: left top;
        background-repeat: no-repeat;
        background-size: auto 50px;
        display: block;
        width: 50px !important; 
        height: 50px;
        text-indent: -9999px;
        overflow: hidden
        }
        
        /* customization */
        
        /* The list background */
        
        
        body[data-query*='"status":1'],
        body[data-query*='"status":2'],
        body[data-query*='"status":3'],
        body[data-query*='"status":4'],
        body[data-query*='"status":6'],
        body[data-query*='"status":7'] {
          background-attachment: fixed !important;
          background-position: 50% 50%;
          background-repeat: no-repeat !important;
          background-size:cover;
          
        }
        
        * {cursor: default;}
        
        /* */
        
        
        
         span a[href*="&tag=!"], span a[href*="&tag=%40"], span a[href*="&tag=~"] {display: none !important;}
        
        /* favorite */
        @media entrytags-favorites {}
        a[href$="&tag=*"]
        {position: absolute;
        left: 0;
        width: 150px;
        height: 0;
        font-size: 15px;
        top: 0px;
        color: transparent !important;
        }
        
        a[href$="&tag=*"]:after
        {content: '\f005';
        font-family: 'FontAwesome' !important;
        display: inline-block;
        pointer-events: all;
        /* change the position below, and add in margin-whatever if it's not enough */
        position: absolute;
        top: 238px; 
        left: 135px;
        /* change the size of font */
        font-size: 1.1em;
        color: #fff !important;
        text-shadow: 0 0 2px #000, 0 0 1px #000, 1px 1px 7px #000, 0 0 0 #fff !important;}
        
        
        
        /* Intro animation */
        @keyframes intro {
          from {
            opacity: 0;
            margin-top: 100vh;
          }
          16% {
            opacity: 0;
            margin-top: 100vh;
          }
          to {
            opacity: 1;
            margin-top: 100px;
          }
        }
        .list-container {
          animation: intro 2s;
        }
        
        
        
        /* */
        
        footer {
                position: fixed;
                bottom: 0px;
                left: 0px;
                width: 100%;
                height:30px !important;
                z-index: 9998;
                
        }
        
        #footer-block {
        display:block;
                background-color: transparent;
                background: rgba(0,0,0,0);
                background: -moz-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,1) 100%);
                background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(0,0,0,0)), color-stop(100%, rgba(0,0,0,1)));
                background: -webkit-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,1) 100%);
                background: -o-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,1) 100%);
                background: -ms-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,1) 100%);
                background: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(0,0,0,1) 100%);        
        }
        
        #copyright {
                color: #FFF;
                letter-spacing: 1px;
                text-shadow: 0px 3px 3px #000;
                font-size:10px;
        }
        
        #copyright::after {
                content: "Shelter Style V1 - Layout designed by Takana no Hana"
        }
        
        
        
        /* footer::after {
          content: "";
          display: block;
          width: 20%;
          height: 100%;
          position: fixed;
          bottom: 0px;
          right: 0px;
          background: url(http://i.imgur.com/A0sntp0.png) no-repeat bottom right;
          background-size: 100%;
          pointer-events: none;
          z-index: 3;
        } */
        
        
        
        
        

