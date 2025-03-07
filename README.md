@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/_res/SettingsIcons.css);
@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/BlurpleRecolor/BlurpleRecolor.css);

:root {
	--font:					"gg sans", "Noto Sans";
	
	--mentioncolor: 			250, 166, 26;
	--successcolor: 			59, 165, 92;
	--warningcolor: 			250, 166, 26;
	--dangercolor: 				237, 66, 69;
	
	--textbrightest: 			255, 255, 255;
	--textbrighter: 			220, 221, 222;
	--textbright: 				185, 187, 190;
	--textdark: 				142, 146, 151;
	--textdarker: 				114, 118, 125;
	--textdarkest: 				79, 84, 92;
	
	--backgroundaccent: 			64, 68, 75;
	--backgroundprimary: 			54, 57, 63;
	--backgroundsecondary: 			47, 49, 54;
	--backgroundsecondaryalt: 		41, 43, 47;
	--backgroundtertiary: 			32, 34, 37;
	--backgroundfloating: 			24, 25, 28;
	
	
	--font_v:				var(--font_s, var(--font));
	
	--mentioncolor_v:			var(--mentioncolor_s, var(--mentioncolor));
	--successcolor_v:			var(--successcolor_s, var(--successcolor));
	--warningcolor_v:			var(--warningcolor_s, var(--warningcolor));
	--dangercolor_v:			var(--dangercolor_s, var(--dangercolor));
	
	--textbrightest_v:			var(--textbrightest_s, var(--textbrightest));
	--textbrighter_v:			var(--textbrighter_s, var(--textbrighter));
	--textbright_v:				var(--textbright_s, var(--textbright));
	--textdark_v:				var(--textdark_s, var(--textdark));
	--textdarker_v:				var(--textdarker_s, var(--textdarker));
	--textdarkest_v:			var(--textdarkest_s, var(--textdarkest));
	
	--backgroundaccent_v:			var(--backgroundaccent_s, var(--backgroundaccent));
	--backgroundprimary_v:			var(--backgroundprimary_s, var(--backgroundprimary));
	--backgroundsecondary_v:		var(--backgroundsecondary_s, var(--backgroundsecondary));
	--backgroundsecondaryalt_v:		var(--backgroundsecondaryalt_s, var(--backgroundsecondaryalt));
	--backgroundtertiary_v:			var(--backgroundtertiary_s, var(--backgroundtertiary));
	--backgroundfloating_v:			var(--backgroundfloating_s, var(--backgroundfloating));
}

.theme-light:not(.custom-profile-theme),
.theme-dark:not(.custom-profile-theme),
.theme-amoled:not(.custom-profile-theme),
.visual-refresh.theme-light:not(.custom-profile-theme),
.visual-refresh.theme-dark:not(.custom-profile-theme),
.visual-refresh.theme-amoled:not(.custom-profile-theme),
.visual-refresh .theme-light:not(.custom-profile-theme),
.visual-refresh .theme-dark:not(.custom-profile-theme),
.visual-refresh .theme-amoled:not(.custom-profile-theme) {
	--text-positive: rgb(var(--successcolor_v));
	--text-warning: rgb(var(--warningcolor_v));
	--text-danger: rgb(var(--dangercolor_v));
	
	--info-positive-background: rgba(var(--successcolor_v), .1);
	--info-positive-foreground: rgb(var(--successcolor_v));
	--info-positive-text: #fff;
	--info-warning-background: rgba(var(--warningcolor_v), .1);
	--info-warning-foreground: rgb(var(--warningcolor_v));
	--info-warning-text: #fff;
	--info-danger-background: rgba(var(--dangercolor_v), .1);
	--info-danger-foreground: rgb(var(--dangercolor_v));
	--info-danger-text: #fff;
	
	--status-positive: rgb(var(--successcolor_v));
	--status-positive-background: rgb(var(--successcolor_v));
	--status-positive-text: #fff;
	--status-warning: rgb(var(--warningcolor_v));
	--status-warning-background: rgb(var(--warningcolor_v));
	--status-warning-text: #fff;
	--status-danger: rgb(var(--dangercolor_v));
	--status-danger-background: rgb(var(--dangercolor_v));
	--status-danger-text: #fff;
	
	--button-positive-background: rgba(var(--successcolor_v), .8);
	--button-positive-background-hover: rgba(var(--successcolor_v), .9);
	--button-positive-background-active: rgb(var(--successcolor_v));
	--button-positive-background-disabled: rgba(var(--successcolor_v), .2);
	--button-warning-background: rgba(var(--warningcolor_v), .8);
	--button-warning-background-hover: rgba(var(--warningcolor_v), .9);
	--button-warning-background-active: rgb(var(--warningcolor_v));
	--button-warning-background-disabled: rgba(var(--warningcolor_v), .2);
	--button-danger-background: rgba(var(--dangercolor_v), .8);
	--button-danger-background-hover: rgba(var(--dangercolor_v), .9);
	--button-danger-background-active: rgb(var(--dangercolor_v));
	--button-danger-background-disabled: rgba(var(--dangercolor_v), .2);
	--button-secondary-background: rgb(var(--textdarkest_v));
	--button-secondary-background-hover: rgb(var(--textdarker_v));
	--button-secondary-background-active: rgb(var(--textdark_v));
	--button-secondary-background-disabled: rgb(var(--textdarkest_v));

	--button-outline-positive-text: rgb(var(--successcolor_v)) !important;
	--button-outline-positive-text-hover: rgb(var(--successcolor_v)) !important;
	--button-outline-positive-text-active: rgb(var(--successcolor_v)) !important;
	--button-outline-positive-background: transparent !important;
	--button-outline-positive-background-hover: transparent !important;
	--button-outline-positive-background-active: rgba(var(--successcolor_v), .1) !important;
	--button-outline-positive-border: rgba(var(--successcolor_v), .1) !important;
	--button-outline-positive-border-hover: rgba(var(--successcolor_v), .6) !important;
	--button-outline-positive-border-active: rgb(var(--successcolor_v)) !important;
	
	--button-outline-warning-text: rgb(var(--warningcolor_v)) !important;
	--button-outline-warning-text-hover: rgb(var(--warningcolor_v)) !important;
	--button-outline-warning-text-active: rgb(var(--warningcolor_v)) !important;
	--button-outline-warning-background: transparent !important;
	--button-outline-warning-background-hover: transparent !important;
	--button-outline-warning-background-active: rgba(var(--warningcolor_v), .1) !important;
	--button-outline-warning-border: rgba(var(--warningcolor_v), .1) !important;
	--button-outline-warning-border-hover: rgba(var(--warningcolor_v), .6) !important;
	--button-outline-warning-border-active: rgb(var(--warningcolor_v)) !important;
	
	--button-outline-danger-text: rgb(var(--dangercolor_v)) !important;
	--button-outline-danger-text-hover: rgb(var(--dangercolor_v)) !important;
	--button-outline-danger-text-active: rgb(var(--dangercolor_v)) !important;
	--button-outline-danger-background: transparent !important;
	--button-outline-danger-background-hover: transparent !important;
	--button-outline-danger-background-active: rgba(var(--dangercolor_v), .1) !important;
	--button-outline-danger-border: rgba(var(--dangercolor_v), .1) !important;
	--button-outline-danger-border-hover: rgba(var(--dangercolor_v), .6) !important;
	--button-outline-danger-border-active: rgb(var(--dangercolor_v)) !important;
	
	--button-outline-primary-text: rgb(var(--textbrightest_v)) !important;
	--button-outline-primary-text-hover: rgb(var(--textbrightest_v)) !important;
	--button-outline-primary-text-active: rgb(var(--textbrightest_v)) !important;
	--button-outline-primary-background: transparent !important;
	--button-outline-primary-background-hover: transparent !important;
	--button-outline-primary-background-active: rgba(var(--textbrightest_v), .1) !important;
	--button-outline-primary-border: rgba(var(--textbrightest_v), .1) !important;
	--button-outline-primary-border-hover: rgba(var(--textbrightest_v), .6) !important;
	--button-outline-primary-border-active: rgb(var(--textbrightest_v)) !important;
	
	--header-primary: rgb(var(--textbrightest_v));
	--header-secondary: rgb(var(--textbright_v));
	--text-normal: rgb(var(--textbrighter_v));
	--text-muted: rgb(var(--textdarker_v));
	--channels-default: rgb(var(--textdark_v));
	--channel-icon: rgb(var(--textdark_v));
	
	--interactive-normal: rgb(var(--textbright_v));
	--interactive-hover: rgb(var(--textbrighter_v));
	--interactive-active: rgb(var(--textbrightest_v));
	--interactive-muted: rgb(var(--textdarkest_v));
	
	--home-background: rgb(var(--backgroundprimary_v));
	
	--modal-background: rgb(var(--backgroundprimary_v));
	--modal-footer-background: rgb(var(--backgroundsecondary_v));
	
	--background-primary: rgb(var(--backgroundprimary_v));
	--background-secondary: rgb(var(--backgroundsecondary_v));
	--background-secondary-alt: rgb(var(--backgroundsecondaryalt_v));
	--background-tertiary: rgb(var(--backgroundtertiary_v));
	--background-accent: rgb(var(--backgroundaccent_v));
	--background-floating: rgb(var(--backgroundfloating_v));
	--background-nested-floating: rgb(var(--backgroundfloating_v));
	--background-mobile-primary: rgb(var(--backgroundprimary_v));
	--background-mobile-secondary: rgb(var(--backgroundsecondary_v));
	
	--bg-backdrop: rgba(0 0,0, .7);
	--bg-backdrop-no-opacity: rgb(0,0,0);
	--bg-mod-faint: rgba(var(--backgroundaccent_v), .2);
	--bg-mod-subtle: rgba(var(--backgroundaccent_v), .3);
	--bg-mod-normal: rgba(var(--backgroundaccent_v), .4);
	--bg-mod-strong: rgba(var(--backgroundaccent_v), .5);
	--bg-base-primary: rgb(var(--backgroundprimary_v));
	--bg-base-secondary: rgb(var(--backgroundsecondary_v));
	--bg-base-tertiary: rgb(var(--backgroundtertiary_v));
	--bg-surface-raised: rgb(var(--backgroundprimary_v));
	
	--background-mod-faint: rgba(var(--backgroundaccent_v), .2);
	--background-mod-subtle: rgba(var(--backgroundaccent_v), .3);
	--background-mod-normal: rgba(var(--backgroundaccent_v), .4);
	--background-mod-strong: rgba(var(--backgroundaccent_v), .5);
	--background-base-low: rgb(var(--backgroundprimary_v));
	--background-base-lower: rgb(var(--backgroundsecondary_v));
	--background-base-lowest: rgb(var(--backgroundsecondaryalt_v));
	--background-surface-highest: rgb(var(--backgroundaccent_v));
	--background-surface-higher: rgb(var(--backgroundprimary_v));
	--background-surface-high: rgb(var(--backgroundprimary_v));
	--chat-background-default: rgb(var(--backgroundprimary_v));
	
	--app-border-frame: transparent;
	--border-faint: rgba(var(--backgroundaccent_v), .2);
	--border-subtle: rgba(var(--backgroundaccent_v), .4);
	--border-strong: rgba(var(--backgroundaccent_v), .6);
	
	--background-modifier-hover: rgba(var(--backgroundaccent_v), .3);
	--background-modifier-active: rgba(var(--backgroundaccent_v), .4);
	--background-modifier-selected: rgba(var(--backgroundaccent_v), .6);
	--background-modifier-accent: rgba(var(--textdark_v), .1);
	
	--background-mentioned: rgba(var(--mentioncolor, --warningcolor_v), .05);
	--background-mentioned-hover: rgba(var(--mentioncolor, --warningcolor_v), .08);
	--background-mentioned-accent: rgb(var(--mentioncolor, --warningcolor_v));
	
	--background-message-hover: rgba(var(--backgroundfloating_v), .15);
	--background-message-automod: rgba(var(--dangercolor_v), .05);
	--background-message-automod-hover: rgba(var(--dangercolor_v), .1);
	
	--card-gradient-bg: var(--background-tertiary);
	--card-primary-bg: var(--background-primary);
	--card-secondary-bg: var(--background-secondary);
	--card-gradient-pressed-bg: var(--background-floating);
	--card-primary-pressed-bg: var(--background-secondary);
	--card-secondary-pressed-bg: var(--background-tertiary);
	
	--scrollbar-thin-thumb: rgb(var(--backgroundtertiary_v));
	--scrollbar-thin-track: transparent;
	--scrollbar-auto-thumb: rgb(var(--backgroundtertiary_v));
	--scrollbar-auto-track: rgb(var(--backgroundsecondary_v));
	--scrollbar-auto-scrollbar-color-thumb: rgb(var(--backgroundtertiary_v));
	--scrollbar-auto-scrollbar-color-track: rgb(var(--backgroundsecondary_v));
	
	--elevation-stroke: 0 0 0 1px rgba(6,6,7, .08);
	--elevation-low: 0 1px 0 rgba(6,6,7, .1), 0 1.5px 0 rgba(6,6,7, .25), 0 2px 0 rgba(6,6,7, .025);
	--elevation-medium: 0 4px 4px rgba(0,0,0, .08);
	--elevation-high: 0 8px 16px rgba(0,0,0, .16);
	
	--shadow-border: 0 0 0 1px rgba(6,6,7, .08);
	--shadow-border-filter: drop-shadow(0 0 1px rgba(6,6,7, .08));
	--shadow-button-overlay: 0 12px 24px 0 rgba(6,6,7, .24);
	--shadow-high: 0 12px 24px 0 rgba(0,0,0, .24);
	--shadow-high-filter: drop-shadow(0 12px 24px rgba(0,0,0, .24));
	--shadow-ledge: 0 2px 0 0 rgba(0,0,0, .05), 0 1.5px 0 0 rgba(0,0,0, .05), 0 1px 0 0 rgba(0,0,0, .16);
	--shadow-ledge-filter: drop-shadow(0 1.5px 0 rgba(0,0,0, .24));
	--shadow-low: 0 1px 4px 0 rgba(6,6,7, .14);
	--shadow-low-filter: drop-shadow(0 1px 4px rgba(6,6,7, .14));
	--shadow-low-active: 0 0 4px 0 rgba(6,6,7, .14);
	--shadow-low-active-filter: drop-shadow(0 0 4px rgba(6,6,7, .14));
	--shadow-low-hover: 0 4px 10px 0 rgba(6,6,7, .14);
	--shadow-low-hover-filter: drop-shadow(0 4px 10px rgba(6,6,7, .14));
	--shadow-medium: 0 4px 8px 0 rgba(0,0,0, .16);
	--shadow-medium-filter: drop-shadow(0 4px 8px rgba(0,0,0, .16));
	--shadow-mobile-navigator-x: 0 0 10px 0 rgba(0,0,0, .22);
	--shadow-mobile-navigator-x-filter: drop-shadow(0 0 10px rgba(0,0,0, .22));
	--shadow-top-high: 0 -12px 32px 0 rgba(0,0,0, .24);
	--shadow-top-high-filter: drop-shadow(0 -12px 32px rgba(0,0,0, .24));
	--shadow-top-ledge: 0 -2px 0 0 rgba(0,0,0, .05), 0 -1.5px 0 0 rgba(0,0,0, .05), 0 -1px 0 0 rgba(0,0,0, .16);
	--shadow-top-ledge-filter: drop-shadow(0 -1.5px 0 rgba(0,0,0, .24));
	--shadow-top-low: 0 -1px 4px 0 rgba(0,0,0, .14);
	--shadow-top-low-filter: drop-shadow(0 -1px 4px rgba(0,0,0, .14));
	
	--logo-primary: rgb(var(--accentcolor_v));
	
	--focus-primary: rgb(var(--focuscolor, var(--linkcolor_v))) !important;
	
	--guild-header-text-shadow: 0 1px 1px rgba(var(--backgroundfloating_v), .5);
	
	--channeltextarea-background: rgba(var(--backgroundaccent_v), .8);
	--channel-text-area-placeholder: rgb(var(--textdarker_v));
	
	--input-background: rgb(var(--backgroundtertiary_v));
	--input-border: rgb(var(--backgroundsecondary_v));
	
	--activity-card-background: rgb(var(--backgroundtertiary_v));
	
	--textbox-markdown-syntax: rgb(var(--textdark_v));
	
	--search-popout-option-fade: linear-gradient(90deg,transparent,var(--background-floating) 80%);
	--search-popout-option-fade-hover: linear-gradient(90deg,transparent,var(--background-primary) 50%);
	--search-popout-option-user-nickname: var(--text-normal);
	--search-popout-option-user-username: var(--text-muted);
	--search-popout-option-filter-text: var(--text-muted);
	--search-popout-option-non-text-color: var(--text-normal);
	--search-popout-option-filter-color: var(--text-normal);
	--search-popout-option-answer-color: var(--text-normal);
	--search-popout-date-picker-border: 1px solid hsla(214,calc(var(--saturation-factor, 1)*9.1%),15.1%,0.3);
	--search-popout-date-picker-hint-text: var(--text-normal);
	--search-popout-date-picker-hint-value-text: #fff;
	
	--deprecated-card-bg: rgba(var(--backgroundtertiary_v), .6);
	--deprecated-card-editable-bg: rgba(var(--backgroundtertiary_v), .3);
	--deprecated-store-bg: rgb(var(--backgroundprimary_v));
	--deprecated-quickswitcher-input-background: rgb(var(--backgroundaccent_v));
	--deprecated-quickswitcher-input-placeholder: rgb(var(--textdarker_v));
	--deprecated-text-input-bg: rgba(0,0,0, .1);
	--deprecated-text-input-border: rgba(0,0,0, .3);
	--deprecated-text-input-border-hover: #040405;
	--deprecated-text-input-border-disabled: #202225;
	--deprecated-text-input-prefix: rgb(var(--textbrighter_v));
	
	--font-primary: var(--font_v) !important;
	--font-display: var(--font_v) !important;
}

html {
	color: var(--header-primary);
}


/* ~~~~		0.		TABLE OF CONTENTS				~~~~ */
/*
	1.	GENERAL
		1.	TEXT
		2.	BUTTONS
		3.	INPUTS
		4.	SEARCHBARS
		5.	IMAGES	
	2.	GUILDLIST
	3.	CHANNELLIST
		1.	GUILDHEADER
		2.	CHANNELS
		3.	DMCHANNELS
		4.	ACCOUNT/VOICE/GOLIVE
	4.	CHAT
		1.	CHANNELHEADER
		2.	MESSAGES
			1.	MESSAGE
			2.	EMBEDS
			3.	NITROGIFT
			4.	INVITE
		3.	TEXTAREA
		4.	AUTOCOMPLETEMENU
		5.	MEMBERLIST
		6.	CALL
	5.	PEOPLES
		1.	SHOP
		2.	FAMILY CENTER
	6.	STORE/NITRO
		1.	BIRTHDAY PAGE
	7.	LIBRARY
	8.	DISCOVERY
	9.	USERSETTINGS
	10.	GUILDSETTINGS
	11.	MODALS
		1.	USERMODAL
		2.	GUILDADD/CREATION
		3.	UPLOADMODAL
		4.	KEYBOARDSHORTCUTSMODAL
		5.	QUICKSWITCHER
		6.	INVITEMODAL/GROUPCREATE
		7.	LOGINSCREEN
		8.	DOWNLOADAPPMODAL
		9.	GUILDBOOSTMODAL
		10.	REACTIONSMODAL
		11.	CHANGELOG
		12.	NOTIFICATIONSMODAL
		13.	PAYMENTMODAL
		14.	CLOUDSYNCRESOLUTION
		15.	APPLICATIONINSTALLATIONMODAL
		16.	DISPATCHERROR
		17.	HYPESQUADQUIZ
		18.	SERVERAPPMODAL
	12.	POPOUTS
		1.	USERPOPOUT
		2.	EMOJIPICKER
		3.	SEARCHPOPOUT
		4.	EVERYONEMENTION
		5.	CHANNELFOLLOW
		6.	CHANNELFOLLOWINFO
		7.	STREAMPREVIEW
		8.	ROLEOVERFLOW
		9.	PUBLICGUILDANNOUNCEMENT
		10.	QUICKSELECTPOPOUT
		11.	RTCSTATUSPOPOUT
		12.	PHONE-/EMAILVALIDATION
		13.	WARNINGPOPOUT
		14.	ADDROLE
		15.	APPPICKER
	13.	BDSUPPORT
	14.	POWERCORDSUPPORT
	15.	PLUGINSUPPORT
		1.	MEMBERCOUNT
		2.	CHANNELTABS
		3.	TYPINGINDICATOR
	16.	WATERMARK
*/


/* ~~~~		1.		GENERAL						~~~~ */

svg [style*="stroke: rgb(114, 118, 125)"],
svg [style*="stroke: #72767d"],
svg [style*="stroke: #72767D"],
svg [stroke="rgb(114, 118, 125)"],
svg [stroke="#72767d"],
svg [stroke="#72767D"] {
	stroke: var(--text-muted) !important;
}
svg [style*="fill: rgb(114, 118, 125)"],
svg [style*="fill: #72767d"],
svg [style*="fill: #72767D"],
svg [fill="rgb(114, 118, 125)"],
svg [fill="#72767d"],
svg [fill="#72767D"] {
	fill: var(--text-muted) !important;
}
svg [style*="stroke: rgb(79, 84, 92)"],
svg [style*="stroke: #4f545c"],
svg [style*="stroke: #4F545C"],
svg [stroke="rgb(79, 84, 92)"],
svg [stroke="#4f545c"],
svg [stroke="#4F545C"] {
	stroke: var(--interactive-muted) !important;
}
svg [style*="fill: rgb(79, 84, 92)"],
svg [style*="fill: #4f545c"],
svg [style*="fill: #4F545C"],
svg [fill="rgb(79, 84, 92)"],
svg [fill="#4f545c"],
svg [fill="#4F545C"] {
	fill: var(--interactive-muted) !important;
}

.highlight {
	background: rgba(var(--mentioncolor, --warningcolor_v), .3);
}

#app-mount .elevationLow__2b2f1, #app-mount .elevationLow_be38de, .lightElevationLow_b62459 {
	box-shadow: 0 1px 5px 0 rgba(0,0,0, .3);
}
#app-mount .elevationHigh__2b2f1, #app-mount .elevationHigh__08882, .lightElevationHigh_c9beeb {
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .elevationBorderLow__2b2f1, #app-mount .elevationBorderLow_d10573, .lightElevationBorderLow__1e5e8 {
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 1px 5px 0 rgba(0,0,0, .3);
}
#app-mount .elevationBorderHigh__2b2f1, #app-mount .elevationBorderHigh__30406, .lightElevationBorderHigh__68386, .darkElevationBorderHigh__4ef1e {
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
}

#app-mount .bubble_f7877e {
	background-color: var(--background-floating);
	color: var(--text-normal);
}
#app-mount .bubble_f7877e::before {
	border: 5px solid transparent;
	border-top-color: var(--background-floating);
}

#app-mount .card_b846e5::before {
	background-color: var(--background-primary);
	border-color: var(--background-secondary);
}
#app-mount .button_e18686 {
	background-color: var(--background-primary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 1px 5px 0 rgba(0,0,0, .3);
}
#app-mount .button_e18686:hover {
	background-color: var(--background-accent);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
}

#app-mount .text__2636e {
	color: var(--header-primary);
}
#app-mount .editIcon__2636e {
	-webkit-mask: url(https://discord.com/assets/c87be216431a35927431.svg);
	background: var(--header-primary);
}

#app-mount .scrollbarGhost__506b3::-webkit-scrollbar-thumb {
	background-color: var(--scrollbar-thin-thumb);
	border-color: transparent;
}
#app-mount .scrollbarGhost__506b3::-webkit-scrollbar-track {
	background-color: var(--scrollbar-thin-track);
	border-color: transparent;
	border-width: initial;
}
#app-mount .scrollbarGhostHairline__506b3::-webkit-scrollbar-thumb {
	background-color: var(--scrollbar-thin-thumb);
	border-radius: 2px;
	cursor: move;
}
#app-mount .scrollbarDefault__506b3::-webkit-scrollbar-thumb {
	background-color: var(--scrollbar-auto-thumb);
	border-color: transparent;
}
#app-mount .scrollbarDefault__506b3::-webkit-scrollbar-track {
	background-color: var(--scrollbar-auto-track);
	border-color: transparent;
}

#app-mount .breadcrumbWrapper__75797 {
	color: rgba(var(--textbrightest_v), .3);
}
#app-mount .activeBreadcrumb__56acd {
	color: rgba(var(--textbrightest_v), .6);
}

html .iconBadge__0c126 {
	background-color: var(--background-floating);
	color: var(--header-primary);
}

/* ----		1.1.		TEXT						---- */

#app-mount h1.title_d1da5f,
#app-mount h2.title_d1da5f {
	color: var(--header-primary);
}
#app-mount h3.title_d1da5f {
	color: var(--text-normal);
}
#app-mount h4.title_d1da5f,
#app-mount h5.title_d1da5f,
#app-mount h6.title_d1da5f {
	color: var(--header-secondary);
}

#app-mount .text__0e310,
#app-mount .title__496be {
	color: var(--text-muted);
}

#app-mount .title_d1da5f {
	color: var(--header-secondary);
}

#app-mount .markdown_d285a6 {
	color: var(--text-normal);
}
#app-mount .markdown_d285a6 th {
	background-color: var(--background-tertiary);
	border-color: var(--interactive-muted);
	color: var(--header-primary);
}
#app-mount .markdown_d285a6 td {
	border-color: var(--interactive-muted);
}
#app-mount .markdown_d285a6 tr {
	border-color: var(--interactive-muted);
	color: var(--header-secondary);
}
#app-mount .markdown_d285a6 tr:nth-child(2n) {
	background-color: var(--background-secondary);
}
#app-mount .markdown_d285a6 .blockquote_d285a6 {
	border-left-color: var(--interactive-muted);
}
#app-mount .markdown_d285a6 code {
	background-color: var(--background-secondary);
}
#app-mount .markdown_d285a6 .codeInline_d285a6 {
	color: var(--text-normal);
}

/* ----		1.2.		BUTTONS						---- */

#app-mount .lookInverted_a299dc.colorPrimary__201d5 .spinnerItem__201d5 {
	background-color: var(--background-accent);
}
#app-mount .lookOutlined__201d5.colorPrimary__201d5 .spinnerItem__201d5,
#app-mount .lookLink__201d5.colorPrimary__201d5 .spinnerItem__201d5 {
	background-color: var(--header-primary);
}

#app-mount .lookFilled__201d5.colorPrimary__201d5:hover,
#app-mount .lookFilled__201d5.hoverPrimary_c2c623.hasHover_dfa15e:hover {
	background-image: linear-gradient(0deg, rgba(255, 255, 255, .15), rgba(255, 255, 255, .15));
}
#app-mount .lookFilled__201d5.colorPrimary__201d5:active,
#app-mount .lookFilled__201d5.hoverPrimary_c2c623.hasHover_dfa15e:active {
	background-image: linear-gradient(0deg, rgba(255, 255, 255, .3), rgba(255, 255, 255, .3));
}
#app-mount .lookFilled__201d5.colorPrimary__201d5,
#app-mount .lookFilled__201d5.colorPrimary__201d5:disabled {
	background-color: var(--background-accent);
	color: #FFF;
}

#app-mount .lookInverted_a299dc.colorPrimary__201d5:hover,
#app-mount .lookInverted_a299dc.hoverPrimary_c2c623.hasHover_dfa15e:hover {
	background-image: linear-gradient(0deg, rgba(0, 0, 0, .1), rgba(0, 0, 0, .1));
}
#app-mount .lookInverted_a299dc.colorPrimary__201d5:active,
#app-mount .lookInverted_a299dc.hoverPrimary_c2c623.hasHover_dfa15e:active {
	background-image: linear-gradient(0deg, rgba(0, 0, 0, .2), rgba(0, 0, 0, .2));
}
#app-mount .lookInverted_a299dc.colorPrimary__201d5,
#app-mount .lookInverted_a299dc.colorPrimary__201d5:disabled {
	background-color: #FFF;
	color: var(--background-accent);
}

#app-mount .lookOutlined__201d5.colorPrimary__201d5:hover,
#app-mount .lookOutlined__201d5.hoverPrimary_c2c623.hasHover_dfa15e:hover {
	border-color: rgba(var(--textbrightest_v), .6);
}
#app-mount .lookOutlined__201d5.colorPrimary__201d5:active,
#app-mount .lookOutlined__201d5.hoverPrimary_c2c623.hasHover_dfa15e:active {
	background-color: rgba(var(--textbrightest_v), .1);
	border-color: var(--header-primary);
}
#app-mount .lookOutlined__201d5.colorPrimary__201d5,
#app-mount .lookOutlined__201d5.colorPrimary__201d5:disabled {
	border-color: rgba(var(--textbrightest_v), .1);
	color: var(--header-primary);
}

#app-mount .lookLink__201d5.colorPrimary__201d5 {
	color: var(--header-primary);
}
#app-mount .lookLink__201d5.colorPrimary__201d5:hover .contents__201d5,
#app-mount .lookLink__201d5.hoverPrimary_c2c623.hasHover_dfa15e:hover .contents__201d5 {
	--button--underline-color: var(--header-primary);
	color: var(--header-primary);
}

#app-mount .borderPrimary__386cf {
	border-color: var(--header-primary) !important;
}

#app-mount .lookInverted_a299dc.colorTransparent__201d5 .spinnerItem__201d5 {
	background-color: rgba(var(--textbrightest_v), .1);
}
#app-mount .lookFilled__201d5.colorTransparent__201d5 .spinnerItem__201d5,
#app-mount .lookOutlined__201d5.colorTransparent__201d5 .spinnerItem__201d5,
#app-mount .lookLink__201d5.colorTransparent__201d5 .spinnerItem__201d5 {
	background-color: var(--header-primary);
}

#app-mount .lookFilled__201d5.colorTransparent__201d5:hover,
#app-mount .lookFilled__201d5.hoverTransparent__31061.hasHover_dfa15e:hover {
	background-color: rgba(var(--textbrightest_v), .05);
}
#app-mount .lookFilled__201d5.colorTransparent__201d5:active,
#app-mount .lookFilled__201d5.hoverTransparent__31061.hasHover_dfa15e:active  {
	background-color: rgba(var(--textbrightest_v), .01);
}
#app-mount .lookFilled__201d5.colorTransparent__201d5,
#app-mount .lookFilled__201d5.colorTransparent__201d5:disabled {
	background-color: rgba(var(--textbrightest_v), .1);
	color: var(--header-primary);
}

#app-mount .lookInverted_a299dc.colorTransparent__201d5:hover,
#app-mount .lookInverted_a299dc.hoverTransparent__31061.hasHover_dfa15e:hover {
	background-color: rgba(var(--textbrightest_v), .05);
}
#app-mount .lookInverted_a299dc.colorTransparent__201d5:active,
#app-mount .lookInverted_a299dc.hoverTransparent__31061.hasHover_dfa15e:active {
	background-color: rgba(var(--textbrightest_v), .1);
}
#app-mount .lookInverted_a299dc.colorTransparent__201d5,
#app-mount .lookInverted_a299dc.colorTransparent__201d5:disabled  {
	background-color: var(--header-primary);
	color: rgba(var(--textbrightest_v), .1);
}

#app-mount .lookOutlined__201d5.colorTransparent__201d5:hover,
#app-mount .lookOutlined__201d5.hoverTransparent__31061.hasHover_dfa15e:hover {
	background-color: rgba(var(--textbrighter_v), .1);
	border-color: var(--interactive-hover);
}
#app-mount .lookOutlined__201d5.colorTransparent__201d5:active,
#app-mount .lookOutlined__201d5.hoverTransparent__31061.hasHover_dfa15e:active {
	background-color: rgba(var(--textbrightest_v), .1);
	border-color: var(--header-primary);
}
#app-mount .lookOutlined__201d5.colorTransparent__201d5,
#app-mount .lookOutlined__201d5.colorTransparent__201d5:disabled {
	background-color: transparent;
	color: var(--text-normal);
}

#app-mount .lookLink__201d5.colorTransparent__201d5 {
	color: var(--text-normal);
}
#app-mount .lookLink__201d5.colorTransparent__201d5:hover .contents__201d5,
#app-mount .lookLink__201d5.hoverTransparent__31061.hasHover_dfa15e:hover .contents__201d5 {
	--button--underline-color: var(--text-normal);
	color: var(--text-normal);
}

#app-mount .borderTransparent_c5801e {
	border-color: var(--text-normal) !important;
}

/* ----		1.3.		INPUTS						---- */

.container__87bf1 {
	background-color: var(--text-muted) !important;
}
.container__87bf1 path[fill] {
	fill: var(--text-muted) !important;
}

#app-mount .prefixInput__9d137 {
	background-color: rgba(0,0,0, .1);
	border-color: rgba(0,0,0, .3);
}
#app-mount .prefixInput__9d137:hover {
	border-color: rgba(0,0,0, .6);
}
#app-mount .prefixInputInput__9d137 {
	color: var(--header-primary);
}
#app-mount .prefixInputInput__9d137::-webkit-input-placeholder,
#app-mount .prefixInputInput__9d137::-moz-placeholder,
#app-mount .prefixInputInput__9d137:-ms-input-placeholder,
#app-mount .prefixInputInput__9d137::placeholder {
	color: var(--text-muted);
}
#app-mount .prefixInputPrefix__9d137 {
	color: var(--text-muted);
}

#app-mount .item__001a7[aria-checked=true] .radioBar__001a7 {
	background: rgb(var(--accentcolor_v));
	color: #fff;
}
#app-mount .item__001a7[aria-checked=true] .radioBar__001a7 .radioIconForeground__001a7 {
	color: #fff;
}
#app-mount .item__001a7 .radioBar__001a7[style*="--radio-bar-accent-color"] {
	background: var(--radio-bar-accent-color);
	border: unset;
	color: #fff;
}
#app-mount .item__001a7[aria-checked=false]:hover .radioBar__001a7[style*="--radio-bar-accent-color"] {
	background: var(--radio-bar-accent-color) linear-gradient(to right, rgba(255, 255, 255, .2), rgba(255, 255, 255, .2));
}
#app-mount .radioBar__001a7[style*="--radio-bar-accent-color"] .refreshIconStroke__001a7 {
	stroke: #fff;
}
#app-mount .radioBar__001a7[style*="--radio-bar-accent-color"] .radioIndicatorChecked__001a7 .refreshIcon__001a7 {
	fill: var(--radio-bar-accent-color);
}
#app-mount .radioBar__001a7[style*="--radio-bar-accent-color"] .radioIndicatorChecked__001a7 .refreshIconFill__001a7 {
	fill: #fff;
}

.lookFilled__3f413.select__3f413 {
	background-color: var(--deprecated-text-input-bg);
	border-color: var(--deprecated-text-input-border);
}
.searchInput__3f413 {
	background-color: transparent;
}
.lookFilled__3f413.select__3f413:hover {
	border-color: var(--deprecated-text-input-border-hover);
}

#app-mount .container_f89b2c {
	background-color: var(--deprecated-text-input-bg);
	border-color: var(--deprecated-text-input-border);
}
#app-mount .container_f89b2c:hover {
	border-color: var(--deprecated-text-input-border-hover);
}

#app-mount .checkbox_f525d3 {
	border-color: var(--text-muted);
}
#app-mount .checkbox_f525d3.checked_f525d3[style*="border-color: rgb(79, 84, 92)"],
#app-mount .checkbox_f525d3.checked_f525d3:not([style*="border-color:"]):not([style*="background-color:"]) {
	background-color: rgb(var(--accentcolor_v)) !important;
	border-color: rgb(var(--accentcolor_v)) !important;
}
#app-mount .checkbox_f525d3.checked_f525d3[style*="border-color: rgb(79, 84, 92)"] path,
#app-mount .checkbox_f525d3.checked_f525d3:not([style*="border-color:"]):not([style*="background-color:"]) path {
	fill: #fff;
}

#app-mount .maxLength__7aff3 {
	color: var(--text-muted);
}

#app-mount .copyInput_fffc15 {
	background-color: var(--deprecated-text-input-bg);
}
#app-mount .copyInputDefault_e19ebf {
	border-color: var(--deprecated-text-input-border);
}
#app-mount .hiddenMessage_e7355b,
#app-mount .inputDefault__591c7 {
	color: var(--header-primary);
}
#app-mount .hiddenMessage_e7355b::placeholder,
#app-mount .inputDefault__591c7::placeholder {
	color: rgba(var(--textbrightest_v), .3);
}

#app-mount .grabber_a562c8 {
	background-color: #fff;
	border-color: var(--background-accent);
}
#app-mount .bar_a562c8 {
	background: var(--background-accent);
}
#app-mount .markValue_a562c8 {
	color: var(--text-muted);
}
#app-mount .markDash_a562c8 {
	background: var(--background-accent);
}

.select_d48ec6 [class*="css-"][class*="-control"] {
	background-color: var(--deprecated-text-input-bg);
	border-color: var(--deprecated-text-input-border);
	color: var(--text-normal);
}
.select_d48ec6 [class*="css-"][class*="-control"]:hover,
.select_d48ec6 [class*="css-"][class*="-control"]:not(:last-child) {
	border-color: var(--deprecated-text-input-border-hover);
}
.select_d48ec6.languageSelector_f69601 [class*="css-"][class*="-control"] {
	background-color: var(--background-tertiary);
	border: none;
}
.select_d48ec6 [class*="css-"][class*="-singleValue"],
.select_d48ec6 [class*="css-"][class*="-placeholder"],
.select_d48ec6 [class*="css-"][class*="-indicatorContainer"] {
	color: var(--text-normal);
}
.css-1gfjib6-option,
.css-1yz4bi9-option,
.css-ru8b0x-option,
.css-1yz4bi9-option {
	background-color: rgba(var(--transparencycolor), .1);
	color: var(--interactive-normal);
}
.css-pkcurw-option,
.css-rzbxvl-option,
.css-1qxn4c5-option,
.css-rzbxvl-option {
	background-color: var(--background-secondary);
	color: var(--interactive-hover);
}
.css-1gxgi19-option,
.css-1ba14n5-option,
.css-6qzljd-option,
.css-1ba14n5-option {
	background-color: var(--background-primary);
	color: var(--interactive-active);
}
.select_d48ec6 > [class*="css-"][class*="-container"] > [class*="css-"][class*="-menu"] {
	background-color: var(--background-tertiary);
	border-color: var(--background-tertiary);
	box-shadow: var(--elevation-high);
	overflow: hidden;
}

#app-mount .top_b3f026 .item_b3f026.selected_b3f026 {
	color: var(--text-primary);
}
.side_b3f026 .themed_b3f026.selected_b3f026.item_b3f026:hover:not(.disabled_b3f026),
.topPill_b3f026 .themed_b3f026.selected_b3f026.item_b3f026:hover:not(.disabled_b3f026) {
	background-color: var(--button-secondary-background);
}

#app-mount .customColorPicker_bbc020 {
	background: var(--background-primary);
	border-color: var(--background-tertiary);
}

/* ----		1.4.		SEARCHBARS					---- */

#app-mount .searchBox__56feb {
	background-color: var(--background-accent);
	box-shadow: 0 2px 5px 0 rgba(0,0,0, .2);
}
#app-mount .searchBox__56feb .searchBoxInput__56498::placeholder {
	color: var(--text-muted);
}
#app-mount .searchIcon_d1a3c1 {
	color: var(--text-muted);
}
#app-mount .filterLabel__82eb8 {
	color: var(--header-secondary);
}

/* ----		1.5.		IMAGES						---- */

#app-mount .image__7184c {
	background-image: url(https://discord.com/assets/5420f8fd9d89897c6448.svg);
	opacity: .75;
}

#app-mount .invalidPoop__857bf {
	background-color: rgba(var(--backgroundaccent_v), .6);
	background-image: url(https://discord.com/assets/baa5b6db50bb89d55668.svg);
	opacity: .5;
}

#app-mount .sadImage__29ebd {
	background-image: url(https://discord.com/assets/746284e4cfc7cd6c5e15.svg);
	opacity: .5;
}

#app-mount .cancelImage_b9f95d {
	background: url(https://discord.com/assets/d12b5c285831f85c5eee.svg);
	opacity: .75;
}

#app-mount .emptyWumpus_adb41f {
	background: url(https://discord.com/assets/b3dd9b1e282fff30af5b.svg);
	opacity: .5;
}

#app-mount .authenticationRequiredImage__28393 {
	background-image: url(https://discord.com/assets/ac36a2fad758d64ffbfb.svg);
	opacity: .5;
}
#app-mount .authenticationSuccessImage__28393 {
	background-image: url(https://discord.com/assets/22a55a08151860da8500.svg);
	opacity: .5;
}
#app-mount .authenticationFailImage-3DXXvB {
	background-image: url(https://discord.com/assets/5fc4852a2acb3abf0a64.svg);
	opacity: .5;
}

#app-mount .conflictUploadArt_c68c28 {
	background-image: url(https://discord.com/assets/27f92332674f9dacc1e9.svg);
	opacity: .5;
}
#app-mount .conflictDownloadArt__87c31 {
	background-image: url(https://discord.com/assets/f6bc645aead00959a690.svg);
	opacity: .5;
}
#app-mount .errorArt__7d1bf {
	background-image: url(https://discord.com/assets/c00cfaed1382bf7f33d4.svg);
	opacity: .5;
}

#app-mount .searchIndexBackground_e1fee6 {
	background-image: url(https://discord.com/assets/1876c6a6db747137a124.svg);
	opacity: .5;
}
#app-mount .resultsBlockedImage_c68065 {
	background-image: url(https://discord.com/assets/83720a1a3ec0963a1f71.svg);
	opacity: .5;
}
#app-mount .noResultsImage_a9e706 {
	background-image: url(https://discord.com/assets/45cd76fed34c8e398cc8.svg);
	opacity: .5;
}
#app-mount .noResultsImage_a9e706.alt_a9e706 {
	background-image: url(https://discord.com/assets/99d35a435f00582ddf41.svg);
	opacity: .5;
}
#app-mount .errorImage_a9e706 {
	background-image: url(https://discord.com/assets/8eeb59bba0a61cbffc41.svg);
	opacity: .5;
}

#app-mount .emptyStateImage_d4883c {
	background: url(https://discord.com/assets/b3dd9b1e282fff30af5b.svg);
	opacity: .5;
}

#app-mount .wrapper__61a6b {
	background-image: url(https://discord.com/assets/14223d22c9628be36fc0.svg);
}
#app-mount .image__61a6b {
	background-image: url(https://discord.com/assets/72eaa596042042be6259.svg);
	opacity: .5;
}

#app-mount .gameIcon_b52e4f {
	background-color: rgba(var(--textbrightest_v), .1);
	color: var(--header-primary);
}

#app-mount .noResults__6d749 {
	background-image: url(https://discord.com/assets/c586aac99de98cfb010d.svg);
	opacity: .5;
}

#app-mount .art__0668f {
	background-image: url(https://discord.com/assets/1a8d1cce8efe66c22c6d.svg);
	opacity: .5;
}

#app-mount .art_cb3c76 {
	background-image: url(https://discord.com/assets/29306de8953471954035.svg);
	opacity: .5;
}

#app-mount .imageUnverified_d450d1 {
	background-image: url(https://discord.com/assets/f0cba42b6a6d3b2de4fd.svg);
	opacity: .5;
}

#app-mount .imageUpgrade_fcc792 {
	background-image: url(https://discord.com/assets/7e81dd54960672eabe78.svg);
}
#app-mount .imageCancel_fcc792 {
	background-image: url(https://discord.com/assets/d12b5c285831f85c5eee.svg);
}
#app-mount .imageUnclaimed_fcc792 {
	background-image: url(https://discord.com/assets/41675689ca055858e137.svg);
	opacity: .5;
}
#app-mount .imageUnverified_fcc792 {
	background-image: url(https://discord.com/assets/f0cba42b6a6d3b2de4fd.svg);
	opacity: .5;
}

#app-mount .emptyPreviewImage__04666 {
	background-image: url(https://discord.com/assets/3a354aac283f909d403d.svg);
	opacity: .5;
}

.fullArt_b97f6b,
.fullArt__86d5c {
	opacity: .5;
}

.image__45690 {
	opacity: .5;
}
.image__45690[style*='url("/assets/9e2f412156e2ac1f14e9.svg")'] {
	background-image: url(https://discord.com/assets/64df6f04b850029d2e78.svg) !important;
}

.image__08515 {
	opacity: .5;
}
.image__08515[style*='url("/assets/d6dfb89ab06b62044dbb.svg")'] {
	background-image: url(https://discord.com/assets/8eeb59bba0a61cbffc41.svg) !important;
}
.image__08515[style*='url("/assets/75081bdaad2d359c1469.svg")'] {
	background-image: url(https://discord.com/assets/45cd76fed34c8e398cc8.svg) !important;
}

.image__08515[style*='url("/assets/0629e34902ae58f8e4ca.svg")'] {
	background-image: url(https://discord.com/assets/24aa06be5457e66bdd64.svg) !important;
}
.image__08515[style*='url("/assets/5741692705ba077f4190.svg")'] {
	background-image: url(https://discord.com/assets/bca918618b884a382ab5.svg) !important;
}
.image__08515[style*='url("/assets/a72746e7108167af95c8.svg")'] {
	background-image: url(https://discord.com/assets/01864c39871ce619d855.svg) !important;
}
.image__08515[style*='url("/assets/ee4637f8627629dd0da5.svg")'] {
	background-image: url(https://discord.com/assets/532f1d4582d881960783.svg) !important;
}

.image__08515[style*='url("/assets/c8be48745cf680093019.svg")'] {
	background-image: url(https://discord.com/assets/295da3fc92e2adb1b852.svg) !important;
}
.image__08515[style*='url("/assets/5e3480eff150b1cb323e.svg")'] {
	background-image: url(https://discord.com/assets/cf8f9096a9322f2ae0d7.svg) !important;
}
.emptyStateImage__97dd8 {
	opacity: .5;
}
.emptyStateImage__97dd8[src='/assets/39e3f389716400ced39a.svg'] {
	background-image: url(https://discord.com/assets/1bb2be01aece015602f7.svg);
	object-position: -999999px -999999px;
}
.image__08515[style*='url("/assets/c65431f185feb7b00749.svg")'] {
	background-image: url(https://discord.com/assets/cdc3f4f6fbf3a0f0766f.svg) !important;
}
.image__08515[style*='url("/assets/a1b0a14d2f22c155a2b3.svg")'] {
	background-image: url(https://discord.com/assets/c7c4065874955761be3b.svg) !important;
}

img[src='/assets/73984240bd99493de947.svg'] {
	background-image: url(https://discord.com/assets/c1875fc8a42a61903ba1.svg);
	opacity: .5;
	object-position: -999999px -999999px;
}

img[src='/assets/387a7c504c96b992872d.svg'] {
	background-image: url(https://discord.com/assets/1964f50ca0220e98dc32.svg);
	opacity: .5;
	object-position: -999999px -999999px;
}

#app-mount .footerImage__98b95 {
	background-image: url(https://discord.com/assets/a4bee30fe0b5a0f5b3c7.svg);
	opacity: .5;
}

#app-mount .imageError__3af5f {
	opacity: .5;
}

#app-mount .emptyImage_e37a20 {
	background-image: url(https://discord.com/assets/1766a563ac224f0a403d.svg);
	opacity: .5;
}

#app-mount .missingEntitlementImage__65266 {
	background-image: url(https://discord.com/assets/b3dd9b1e282fff30af5b.svg);
	opacity: .5;
}

#app-mount .image__97ca1 {
	background-image: url(https://discord.com/assets/a7d6af4279f16c27ae9b.svg);
	opacity: .5;
}

#app-mount .image_a202d2 {
	background-image: url(https://discord.com/assets/9e9722bd5c8ec20fd746.svg);
	opacity: .5;
}

#app-mount .image__5b754 {
	background-image: url(https://discord.com/assets/c8718df1382ba878f1fc.svg);
	opacity: .5;
}

#app-mount .image_df963a {
	background-image: url(https://discord.com/assets/1766a563ac224f0a403d.svg);
	opacity: .5;
}

/* ~~~~		2.		GUILDLIST					~~~~ */

#app-mount .guildSeparator__252b6 {
	background-color: var(--border-subtle, var(--background-modifier-accent));
}
#app-mount .folder__48112.hover__48112,
#app-mount .childWrapper_a6ce15,
#app-mount .circleIconButton__5bc7e {
	background-color: var(--background-primary);
}
#app-mount .folder__48112,
#app-mount .expandedFolderBackground__48112 {
	background-color: var(--background-secondary);
}
#app-mount .wrapper__8436d.selected_ae80f7 .childWrapper_a6ce15,
#app-mount .wrapper__8436d:hover .childWrapper_a6ce15 {
	background-color: var(--brand-experiment);
}
#app-mount .circleIconButton__5bc7e.selected__5bc7e {
	background-color: var(--green-360);
}

/* ~~~~		3.		CHANNELLIST					~~~~ */

/* ----		3.1.		GUILDHEADER					---- */

/* ----		3.2.		CHANNELS					---- */

#app-mount .icon_b2d72f {
	color: var(--header-secondary);
}
#app-mount .emptyUser_b2d72f {
	background-color: var(--background-accent);
}
#app-mount .moreUsers_b2d72f {
	background-color: var(--background-floating);
	color: var(--header-secondary);
}
#app-mount .streamPreview__6da2d {
	background-color: var(--background-tertiary);
	color: var(--header-secondary);
}
#app-mount .previewContainer__6da2d {
	background-color: var(--background-floating);
}
#app-mount .watchButton__6da2d {
	border-color: var(--header-secondary);
	color: var(--header-secondary);
}
#app-mount .watchButton__6da2d:not([disabled]):hover {
	border-color: var(--header-primary);
	color: var(--header-primary);
}

/* ----		3.3.		DMCHANNELS					---- */

.selected_bf202d,
.selected_bf202d:focus-within,
.selected_bf202d:hover {
	background-color: var(--background-modifier-hover);
	color: var(--header-primary);
}

/* ----		3.4.		ACCOUNT/VOICE/GOLIVE				---- */

#app-mount .userList_bad975::before {
	background-color: var(--background-secondary);
	border-color: transparent var(--background-tertiary) var(--background-tertiary) transparent;
}
#app-mount .header_bad975 {
	background-color: var(--background-tertiary);
	color: var(--header-primary);
}
#app-mount .content_bad975 {
	background-color: var(--background-secondary);
}
#app-mount .username_bad975 {
	color: var(--text-normal);
}
#app-mount .discriminator_bad975 {
	color: var(--text-muted);
}


/* ~~~~		4.		CHAT						~~~~ */

.mainTableContainer__09a38 {
	background: var(--background-secondary);
}

#app-mount .scrollerContainer_c6b11b,
#app-mount .emptyPage__5d7c9 {
	background: var(--bg-overlay-chat,var(--background-primary));
}
#app-mount .scrollerContainer_c6b11b .prompt__5d7c9 {
	background: var(--background-secondary);
}

/* ----		4.1.		CHANNELHEADER					---- */

#app-mount .container__9293f.themed__9293f {
	box-shadow: var(--elevation-low);
}

#app-mount .back__8b3a3 {
	color: var(--interactive-normal);
}
#app-mount .back__8b3a3:hover {
	color: var(--interactive-hover);
}
#app-mount .back__8b3a3:active {
	color: var(--interactive-active);
}
#app-mount .cloud__49676 {
	color: var(--text-muted);
}

/* ----		4.2.		MESSAGES					---- */

.noChannel__01d5c {
	background-color: var(--background-primary);
}
.content_f75fb0::before {
	display: none;
}
#app-mount .background_c54132,
#app-mount .container_f369db,
#app-mount .container__0b563,
#app-mount .header__0b563,
#app-mount .container_c2efea {
	background-color: var(--background-primary);
}
#app-mount .background_c54132 .container_c68a2c,
#app-mount .background_c54132 .container__29699,
#app-mount .background_c54132 .container__60371,
#app-mount .background_c54132 .icon_ac2d0d,
#app-mount .background_c54132 .containerCard__95c7a,
#app-mount .background_c54132 .containerCard__95c7a:hover,
#app-mount .background_c54132 .interactiveCard_d92364,
#app-mount .background_c54132 .emptyStateContainer__08276,
#app-mount .background_c54132 .card_d4f6c7,
#app-mount .container_f369db .mainCard_f369db,
#app-mount .container_f369db .sidebarCard__7449f,
#app-mount .container__0b563 .channelRow_e4503a {
	background-color: var(--background-secondary);
}
#app-mount .action_c66e86,
#app-mount .row_d13feb {
	background-color: var(--background-secondary);
}
#app-mount .background_c54132 .icon_ac2d0d {
	border-color: var(--background-secondary);
}
@media (max-width: 1300px) {
	.container__29699,
	.container__60371 {
		background: none !important;
	}
}
#app-mount .background_c54132 .containerCard__95c7a {
	border-color: var(--background-secondary);
}
#app-mount .background_c54132 .container__55cc1:hover,
#app-mount .container_f369db .pill_a2c9e8,
#app-mount .container__0b563 .channelRow_e4503a:hover {
	background: var(--background-tertiary);
}
#app-mount .textContentFooter__9a337 {
	background: linear-gradient(0deg, rgba(var(--backgroundsecondary_v), 1), rgba(var(--backgroundsecondary_v), .97) 36px, rgba(var(--backgroundsecondary_v), .4));
}

#app-mount .reaction_f8896c.reactionMe_f8896c {
	background-color: var(--brand-experiment-15a);
	border-color: var(--brand-experiment);
}

#app-mount .reaction_f8896c.reactionMe_f8896c .reactionCount_f8896c {
	color: var(--brand-experiment-200);
}

#app-mount .scrollSeparator__01dab {
	box-shadow: 0 1px 0 0 rgba(var(--backgroundfloating_v), .3), 0 1px 2px 0 rgba(var(--backgroundfloating_v), .3);
}

#app-mount .title__7184c {
	color: var(--header-primary);
}
#app-mount .description__7184c {
	color: var(--header-secondary);
}
#app-mount .emptyChannelIcon__00de6 {
	position: relative;
	background: var(--background-accent);
	overflow: hidden;
}
#app-mount .emptyChannelIcon__00de6::before {
	content: "";
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: var(--header-primary);
	-webkit-mask: url(https://discord.com/assets/1b60cdb56c8c081495ac.svg) center no-repeat;
}

/* ====		4.2.1.		MESSAGE						==== */

#app-mount .message__89466 {
	background-color: var(--background-primary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
}

#app-mount .mentioned__5126c::before {
	background-color: rgb(var(--mentioncolor, --warningcolor_v));
}

#app-mount .ephemeralMessage__124d2,
#app-mount .operations_bab751 {
	color: var(--channels-default);
}

.icon__235ca[style*="/assets/7ed159b6acb6da5d9593.svg"] {
	-webkit-mask: url(https://discord.com/assets/7ed159b6acb6da5d9593.svg) center/cover no-repeat;
	background: var(--header-secondary) !important;
}
.icon__235ca[style*="/assets/a1d461025204711133ec.svg"] {
	-webkit-mask: url(https://discord.com/assets/a1d461025204711133ec.svg) center/cover no-repeat;
	background: var(--header-secondary) !important;
}

#app-mount .wrapper_f316dd {
	background-color: var(--background-tertiary);
	color: var(--header-primary);
}

#app-mount .videoControls_f316dd {
	color: #fff;
}

#app-mount .spoilerContent__54ab5 {
	background-color: rgba(var(--textbrightest_v), .1);
}
#app-mount .spoilerContent__54ab5.hidden__54ab5 {
	background-color: var(--background-tertiary);
}
#app-mount .spoilerContent__54ab5.hidden__54ab5:hover {
	background-color: rgba(var(--backgroundtertiary_v), .8);
}

/* ====		4.2.2.		EMBEDS						==== */

#app-mount .description__72090 {
	color: var(--header-primary);
}
#app-mount .tagline__72090 {
	color: var(--header-secondary);
}
#app-mount .tile__72090 {
	background-color: var(--background-tertiary);
	box-shadow: 0 0 0 rgba(var(--backgroundtertiary_v), .15);
}
#app-mount .tile__72090:hover {
	background-color: var(--background-floating);
}

#app-mount .progress__0ccae {
	background-color: rgba(var(--textdarker_v), .3);
}
#app-mount .metadata__0ccae {
	color: var(--text-muted);
}

#app-mount .loadingBackground_a8b53f {
	background-image: linear-gradient(90deg, var(--background-primary),var(--background-accent),var(--background-primary));
}
#app-mount .loadingImage_a8b53f {
	background-color: var(--background-secondary);
}
#app-mount .embedHorizontal_a8b53f,
#app-mount .embedVertical_a8b53f {
	background-color: var(--background-primary);
}

#app-mount .svgContentRight__7b484 {
	fill: var(--interactive-muted);
}
#app-mount .svgContentLeft__7b484 {
	fill: var(--interactive-muted);
}
#app-mount .svgContentLines__7b484,
#app-mount .svgDots__7b484 {
	fill: var(--text-muted);
}
#app-mount .svgTag__7b484 {
	fill: var(--text-normal);
}
#app-mount .infoLink__124c8 {
	color: var(--header-secondary) !important
}
#app-mount .copyLink__124c8::before {
	background-color: var(--background-accent);
}
#app-mount .buildDetails__124c8,
#app-mount .copyLink__124c8:hover,
#app-mount .infoLink__124c8:hover {
	color: var(--header-primary) !important;
}
#app-mount .barLoader__124c8,
#app-mount .buttonLoader__124c8 {
	background-color: var(--background-accent);
}
#app-mount .disabledButtonOverride__124c8 {
	background-color: var(--background-tertiary) !important
}

/* ====		4.2.3.		NITROGIFT					==== */

/* ====		4.2.4.		INVITE						==== */

#app-mount .guildIconImage_d5f3cd {
	background-color: var(--background-primary);
}
#app-mount .guildIconExpired_d5f3cd {
	background-image: url(https://discord.com/assets/baa5b6db50bb89d55668.svg);
	opacity: .5;
}
#app-mount .resolvingBackground_d5f3cd {
	background-image: linear-gradient(90deg, var(--background-primary),var(--background-accent),var(--background-primary));
}

#app-mount .invite__4d3fa {
	background: rgba(var(--backgroundsecondary_v), .6);
	border-color: rgba(var(--backgroundsecondary_v), .9);
}
#app-mount .artworkSpotifySessionEnded__4d3fa {
	background-image: url(https://discord.com/assets/a7d6af4279f16c27ae9b.svg);
	opacity: .5;
}
#app-mount .header__4d3fa {
	color: var(--text-muted);
}
#app-mount .name__4d3fa,
#app-mount .partyStatus__4d3fa {
	color: var(--header-primary);
}
#app-mount .moreUsers__4d3fa {
	background-color: var(--background-floating);
	color: var(--header-secondary);
}
#app-mount .partyMemberEmpty__4d3fa {
	background: var(--background-accent);
}
#app-mount .helpIcon__4d3fa {
	background-color: var(--header-primary);
}
#app-mount .helpIcon__4d3fa [fill] {
	fill: var(--background-secondary);
}
#app-mount .textLink__4d3fa,
#app-mount .message-group .textLink__4d3fa {
	color: var(--header-primary);
}

/* ----		4.3.		TEXTAREA					---- */

#app-mount .error_b82429 {
	color: #f36c6c;
}

#app-mount .toolbar_bba883 {
	background-color: var(--background-floating);
}
#app-mount .toolbar_bba883::before {
	border-left: 8px solid transparent;
	border-right: 8px solid transparent;
	border-top: 8px solid var(--background-floating);
}
#app-mount .divider_bba883 {
	border-left: 1px solid rgba(var(--textbrightest_v), .06);
}
#app-mount .icon_bba883 {
	color: var(--interactive-normal);
}
#app-mount .active__05fbc .icon_bba883,
#app-mount .hover_d0ebf2:hover .icon_bba883 {
	color: var(--interactive-active);
}

#app-mount .cooldownWrapper_b21699[style*="color: rgb(79, 84, 92)"] {
	color: var(--text-muted) !important;
}

/* ----		4.4.		AUTOCOMPLETEMENU				---- */

#app-mount .autocomplete__13533 {
	background-color: var(--background-secondary);
}
#app-mount .categoryHeader_d1405b {
	background-color: var(--background-secondary);
}
#app-mount .selected_d5ae15 {
	background-color: var(--background-primary);
}

/* ----		4.5.		MEMBERLIST					---- */

#app-mount .memberListItem_ec58fe:not(.popoutDisabled_ec58fe):hover {
	background-color: var(--background-tertiary);
}

/* ----		4.6.		CALL						---- */

.wrapper_cb9592 {
	background-color: var(--background-primary);
}
.root_bfe55a {
	color: var(--header-primary);
}
.gradientContainer_bfe55a {
	display: none;
}
.divider__49508 {
	background: var(--background-modifier-accent);
}
.playingText__49508 {
	color: var(--header-secondary);
}
.controlIcon_f1ceac {
	color: var(--interactive-normal);
}
.controlIcon_f1ceac:hover {
	color: var(--interactive-hover);
}
.controlIcon_f1ceac.active_f1ceac,
.controlIcon_f1ceac:active {
	color: var(--interactive-active);
}
.pictureInPictureVideo_e4cb9a .controlIcon_f1ceac {
	color: #b9bbbe;
}
.pictureInPictureVideo_e4cb9a .controlIcon_f1ceac:hover {
	color: #dcddde;
}
.pictureInPictureVideo_e4cb9a .controlIcon_f1ceac.active_f1ceac,
.pictureInPictureVideo_e4cb9a .controlIcon_f1ceac:active {
	color: #fff;
}
.colorable_f1ceac.primaryDark_f1ceac {
	background-color: var(--background-secondary);
}
.colorable_f1ceac.primaryDark_f1ceac,
.colorable_f1ceac.primaryDark_f1ceac .centerIcon_f1ceac {
	color: var(--header-primary);
}
.colorable_f1ceac.primaryDark_f1ceac.active_f1ceac,
.colorable_f1ceac.primaryDark_f1ceac:hover {
	background-color: var(--background-tertiary);
}
.root_f555ee {
	color: var(--header-primary);
}
.root_bfe55a {
	color: var(--header-primary);
}
.tile__90dc5 {
	background-color: var(--background-tertiary);
}
.header_c6e099 {
	color: var(--header-primary);
}
#app-mount .regionSelectName__5621e {
	color: var(--header-secondary);
}
#app-mount .quickSelectPopoutOption_b852b1:hover .regionSelectName__5621e {
	color: var(--header-primary);
}

#app-mount .video__94748 {
	background-color: var(--background-floating);
}
#app-mount .video__94748.minimum__94748 {
	background-color: var(--background-floating);
	box-shadow: inset 0 -1px 0 var(--background-tertiary);
}
#app-mount .video__94748.noChat__94748 .videoBackgroundTransition__94748 {
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .video__94748.noChat__94748 .videoTop__94748,
#app-mount .video__94748.normal__94748 .videoTop__94748 {
	background-image: linear-gradient(0deg, transparent,rgba(0,0,0, .9));
}

#app-mount .videoPreview_c06ae9 {
	background-color: var(--background-secondary);
	border: 1px solid var(--background-tertiary);
}


/* ~~~~		5.		PEOPLES						~~~~ */

#app-mount .container__133bf {
	background-color: var(--background-primary);
}

#app-mount .scroller__7d20c {
	border: none;
}

#app-mount .moreMutualGuildsBtn_bd5e23:hover {
	border-color: rgba(var(--textbrightest_v), .6);
	color: var(--header-primary);
}

#app-mount .outer_bf1984.active_bf1984,
#app-mount .outer_bf1984.interactive_bf1984:hover {
	background-color: var(--background-floating);
}
#app-mount .inset_bf1984 {
	background-color: var(--background-secondary);
}

#app-mount .partyMemberOverflow_e45a82 {
	background-color: var(--background-floating);
	color: var(--header-secondary);
}
#app-mount .partyMemberBackground_b2e343,
#app-mount .partyMemberUnknown_e45a82,
#app-mount .partyMemberBackground__0a9a5,
#app-mount .partyMemberUnknown__90098 {
	background-color: var(--background-accent);
}
#app-mount .partyMemberUnknownIcon_e45a82 {
	color: var(--text-muted);
}

#app-mount .popout_c6d10c {
	background-color: var(--background-floating);
	border-color: var(--background-tertiary);
	box-shadow: 0 8px 16px rgba(0,0,0, .24);
}
#app-mount .memberListItem_d6b206:not(.popoutDisabled_d6b206):hover {
	background-color: var(--background-tertiary);
}
#app-mount .memberListHeader_d6b206 {
	color: var(--header-secondary);
}
#app-mount .memberListItem_d6b206:hover {
	background-color: var(--background-tertiary);
}
#app-mount .multipleIconWrapper__00943,
#app-mount .separator__00943 {
	background-color: var(--background-secondary);
}
#app-mount .body__00943 .separator__00943 {
	background-color: var(--background-primary);
}

#app-mount .voiceSectionNoGuildImageWrapper__00943 {
	background: var(--background-tertiary);
	color: var(--header-primary);
}
#app-mount .voiceSectionIconWrapper__00943 {
	background-color: var(--background-floating);
}
#app-mount .voiceSectionIcon__00943,
#app-mount .xboxSectionIcon__00943 {
	color: var(--header-secondary);
}
#app-mount .applicationStreamingPreviewWrapper__00943 {
	background-color: var(--background-secondary-alt);
}

/* ----		5.1.		SHOP						---- */

#app-mount .shop__6db1d {
	background: var(--background-primary);
}

/* ----		5.2.		FAMILY CENTER					---- */

.contentPanel_dc2e0e::-webkit-scrollbar {
	width: 16px;
	height: 16px;
}
.contentPanel_dc2e0e::-webkit-scrollbar-thumb {
	background-color: var(--scrollbar-auto-thumb);
	min-height: 40px;
}
.contentPanel_dc2e0e::-webkit-scrollbar-track {
	background-color: var(--scrollbar-auto-track);
}
.contentPanel_dc2e0e::-webkit-scrollbar-thumb,
.contentPanel_dc2e0e::-webkit-scrollbar-track {
	border: 4px solid transparent;
	background-clip: padding-box;
	border-radius: 8px;
}
.contentPanel_dc2e0e::-webkit-scrollbar-corner {
	background-color: transparent;
}


/* ~~~~		6.		STORE/NITRO					~~~~ */

#app-mount .headerBarTransparentDarkBackground__80679 {
	background-color: var(--background-primary) !important;
	opacity: 0.8;
}
#app-mount .header_dbef3e {
	color: var(--header-primary);
}
#app-mount .blurb__41902,
#app-mount .storeTerms_f84ad0,
#app-mount .subtext__0cc56 {
	color: var(--header-secondary);
}
#app-mount .divider__2dfcf {
	background-color: rgba(var(--backgroundsecondary_v), .6);
}

#app-mount .iconWrapper__0d13e {
	background: var(--background-accent);
}

#app-mount .directoryHeroPrice_c7dbcb,
#app-mount .directoryHeroPricePremium_c7dbcb {
	color: var(--header-primary);
}
#app-mount .directorySearchPrice_c7dbcb {
	color: var(--header-secondary);
}
#app-mount .listingPrice_c7dbcb {
	color: var(--header-primary);
}
#app-mount .originalAmount_c7dbcb {
	color: var(--header-secondary);
}
#app-mount .embedPrice_c7dbcb {
	color: var(--header-primary);
}
#app-mount .embedPrice_c7dbcb .salePercentage_c7dbcb {
	background-color: var(--background-secondary);
}

#app-mount .loadingContainer__0d97c {
	background-color: rgba(0,0,0, .4);
}
#app-mount .libraryLink__857bf {
	color: rgba(var(--textbrightest_v), .6);
}
#app-mount .metadata__857bf {
	color: var(--text-muted);
}

#app-mount .container__6f73d {
	background-color: var(--background-secondary);
}
#app-mount .loading__6f73d {
	background-color: transparent;
}
#app-mount .sectionAccountCredit_b7bb3c
#app-mount .subscriptionDetails_affe1c {
	border-color: rgba(var(--textdarker_v), .3);
}
#app-mount .tier1Banner__85188 {
	background: var(--background-secondary);
	color: var(--header-primary);
}
#app-mount .tier1Banner__85188::before {
	content: "";
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: var(--header-primary);
	-webkit-mask: url(https://discord.com/assets/02211574807b44f50d90.svg) center/cover no-repeat;
}

#app-mount .categoryHeader__15de0,
#app-mount .premiumApplicationsHeader__1f431 {
	border-color: var(--background-accent);
	color: var(--header-primary);
}
#app-mount .viewAllGames__76b00 {
	color: var(--header-primary);
}

#app-mount .content__6d178 {
	color: var(--text-muted);
}

#app-mount .blurb_d77896 {
	color: var(--text-normal);
}
#app-mount .description_d77896 {
	color: var(--header-secondary);
}
#app-mount .row_c85137 {
	background-color: var(--background-secondary);
	color: var(--header-secondary);
}

#app-mount .featureIcon_c85137 {
	color: var(--header-secondary);
}

#app-mount .themedPagination__00dfb .arrow__00dfb {
	color: var(--header-primary);
}
#app-mount .themedPagination__00dfb .dot__00dfb {
	background-color: var(--header-primary);
}
#app-mount .matureListing__49e1d {
	background-color: transparent;
}
#app-mount h3.contentHeader_ffdcab {
	color: #dcddde;
}

#app-mount .circle__6efad {
	color: var(--header-primary);
}
#app-mount .iconCircle__6efad {
	background-color: var(--background-accent);
}
#app-mount .smallHeader__6efad {
	color: var(--header-secondary);
}
#app-mount .text__6efad {
	color: var(--header-primary);
}

#app-mount .description__450d3 {
	color: var(--header-secondary);
}
#app-mount .playerOverflow__450d3 {
	background-color: var(--background-floating);
	color: var(--header-secondary);
}
#app-mount .description__450d3 strong,
#app-mount .discriminator__272da strong,
#app-mount .username__450d3 {
	color: var(--header-primary);
}

#app-mount .label__74994 {
	color: var(--text-muted);
}
#app-mount .username__74994 {
	color: var(--header-primary);
}
#app-mount .notes__74994 {
	color: var(--header-secondary);
}
#app-mount .root__26095 {
	background-color: var(--background-secondary);
}
#app-mount .header__26095 {
	color: var(--header-primary);
}
#app-mount .section__26095 {
	border-bottom-color: var(--background-primary);
}

#app-mount .breadcrumb__67607:hover {
	color: var(--header-primary);
}

#app-mount .separator_f1dca0 {
	background-color: rgba(var(--backgroundsecondary_v), .6);
}
#app-mount .tabNotSelectedColor_f1dca0 {
	color: var(--header-secondary);
}
#app-mount .tabNotSelectedColor_f1dca0:hover,
#app-mount .tabSelectedColor_f1dca0 {
	color: var(--header-primary);
}
#app-mount .tabSelected_f1dca0 {
	border-bottom-color: var(--header-primary);
}
#app-mount .sectionTitle_dec920 {
	color: var(--header-secondary);
}
#app-mount .requirementKey_f1dca0 {
	color: var(--text-muted);
}
#app-mount .requirements_f1dca0 {
	color: var(--text-normal);
}

#app-mount .content_f1d99d {
	background-color: var(--background-secondary);
}
#app-mount .buttonColorInGuild_f1d99d {
	color: var(--header-primary);
}
#app-mount .name_f1d99d {
	color: var(--header-secondary);
}
#app-mount .memberInfo_f1d99d {
	color: var(--text-muted);
}
#app-mount .dotOffline__55389 {
	background-color: var(--text-muted);
}

#app-mount .listing__0f50c {
	color: var(--header-primary);
}
#app-mount .link__0f50c {
	color: var(--header-primary);
}

#app-mount .applicationName_e8937f {
	color: var(--text-normal);
}
#app-mount .price__9237d {
	background-color: var(--background-accent);
	color: var(--header-primary);
}

/* ----		6.1.		BIRTHDAY PAGE					---- */

#app-mount .outerContainer_f12976 {
	background-color: var(--background-primary);
}
#app-mount .outerContainer_f12976 .heroWrapper__5f3c1 {
	overflow: hidden;
	border-radius: 10px;
}
#app-mount .outerContainer_f12976 .birthdayExplanationWrapper_f12976,
#app-mount .outerContainer_f12976 .flipCardOpened_f12976,
#app-mount .outerContainer_f12976 .activityCard_f12976,
#app-mount .outerContainer_f12976 .celebrateCardContainer_f12976 {
	background-color: var(--background-secondary);
}


/* ~~~~		7.		LIBRARY						~~~~ */

#app-mount .headerCellSorted__19516 {
	color: var(--header-primary);
}

#app-mount .rate__7eeec {
	color: var(--text-muted);
}
#app-mount .background__27106 {
	stroke: var(--background-accent);
}
#app-mount .usageInfo__27106 {
	color: var(--header-secondary);
}

#app-mount .installationPath_a6f654 {
	box-shadow: 0 1px 0 0 var(--background-accent);
}
#app-mount .rowTitle_a6f654 {
	color: var(--text-normal);
}
#app-mount .rowBody_a6f654 {
	color: var(--text-muted);
}
#app-mount .defaultLocationCheckbox_a6f654 {
	color: var(--header-primary);
}
#app-mount .defaultIndicator_a6f654 {
	background-color: var(--background-accent);
	color: var(--header-primary);
}

#app-mount .applicationName_fb04e1 {
	color: var(--header-primary);
}
#app-mount .applicationSubText_fb04e1 {
	color: var(--text-muted);
}
#app-mount .hiddenLibraryApplication__37ace {
	border-color: var(--background-accent);
}
#app-mount .hiddenLibraryApplication__37ace::before {
	background: rgba(var(--backgroundtertiary_v), .3);
	border-color: var(--background-tertiary);
}
#app-mount .restoreButton_fb04e1 {
	background: var(--background-primary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 1px 5px 0 rgba(0,0,0, .3);
}
#app-mount .restoreButton_fb04e1:hover {
	background: var(--background-secondary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
}

#app-mount .card_e90879 {
	box-shadow: var(--elevation-medium);
}
#app-mount .card_e90879:focus,
#app-mount .card_e90879:hover {
	box-shadow: var(--elevation-high);
}


/* ~~~~		8.		DISCOVERY						~~~~ */

#app-mount .pageWrapper_a3a4ce {
	background-color: var(--background-primary);
	color: var(--header-primary);
}
.footerImage_a3a4ce {
	opacity: .5;
}

#app-mount .search_f69601 .searchBox_f69601 {
	background-color: #fff;
}
#app-mount .search_f69601 .searchBox_f69601:focus,
#app-mount .search_f69601 .searchBox_f69601:focus-within {
	box-shadow: 0 0 0 1px rgb(91,67,240), 0 0 0 2px rgba(91,67,240, .6), 0 0 0 3px rgba(91,67,240, .3);
	border-color: transparent;
}
#app-mount .search_f69601 .searchBox_f69601 .searchBoxInput_f69601 {
	color: #2e3338;
}
#app-mount .search_f69601 .searchBox_f69601 .searchBoxInput_f69601::-webkit-input-placeholder,
#app-mount .search_f69601 .searchBox_f69601 .searchBoxInput_f69601::-moz-placeholder,
#app-mount .search_f69601 .searchBox_f69601 .searchBoxInput_f69601:-ms-input-placeholder,
#app-mount .search_f69601 .searchBox_f69601 .searchBoxInput_f69601::placeholder {
	color: #72767d;
}
#app-mount .search_f69601 .searchBox_f69601 .closeIcon_f69601 {
	color: #4f5660;
}
#app-mount .search_f69601 .searchBox_f69601 .closeIcon_f69601:hover {
	color: #2e3338;
}
#app-mount .search_f69601 .searchBox_f69601 .closeIcon_f69601:focus {
	color: #060607;
}
#app-mount .search_f69601 .searchBox_f69601 .searchIcon_f69601 {
	color: rgba(79,84,92, .6);
}


/* ~~~~		9.		USERSETTINGS					~~~~ */

#app-mount .customContainer__23e6b::before {
	box-shadow: 0 1px 4px rgba(0,0,0, .2);
	border-bottom: 1px solid rgba(0,0,0, .2);
}

#app-mount .notice__88b94 {
	background: rgba(var(--backgroundtertiary_v), .95);
}
#app-mount .container_fcf29c[style*="background-color: rgba(248, 249, 249"],
#app-mount .container_fcf29c[style*="background-color: rgba(32, 34, 37"] {
	background-color: rgba(var(--backgroundfloating_v), .9) !important;
}
#app-mount .container_fcf29c[style*="background-color: rgba(248, 249, 249"] .message_fcf29c,
#app-mount .container_fcf29c[style*="background-color: rgba(32, 34, 37"] .message_fcf29c {
	color: var(--header-primary) !important;
}
#app-mount .message_fcf29c {
	color: var(--header-primary);
}
#app-mount .streamerModeEnabledImage_aa3ffd {
	background-image: url(https://discord.com/assets/c133c9df9ee4552c188a.svg);
	opacity: .5;
}

.contentRegion__23e6b div[role="tabpanel"] {
	width: 100%;
}
.toolsContainer__23e6b {
	margin-right: 37px;
}
#app-mount .closeButton_c2b141 {
	border-color: var(--channels-default);
}
#app-mount .closeButton_c2b141 path[fill] {
	fill: var(--channels-default);
}
#app-mount .closeButton_c2b141:hover {
	background-color: rgba(var(--backgroundaccent_v), .3);
	border-color: var(--header-secondary);
}
#app-mount .closeButton_c2b141:hover path[fill] {
	fill: var(--header-secondary);
}
#app-mount .closeButton_c2b141:active {
	border-color: var(--text-normal);
}
#app-mount .closeButton_c2b141:active path[fill] {
	fill: var(--text-normal);
}
#app-mount .keybind_c2b141 {
	color: var(--channels-default);
}

#app-mount .closeButtonBold_c2b141 {
	border-color: var(--header-secondary);
}
#app-mount .closeButtonBold_c2b141 path[fill] {
	fill: var(--header-secondary);
}
#app-mount .closeButtonBold_c2b141:hover {
	background-color: rgba(var(--backgroundaccent_v), .6);
	border-color: var(--text-normal);
}
#app-mount .closeButtonBold_c2b141:hover path[fill] {
	fill: var(--text-normal);
}
#app-mount .closeButtonBold_c2b141:active {
	border-color: var(--header-primary);
}
#app-mount .closeButtonBold_c2b141:active path[fill] {
	fill: var(--header-primary);
}
#app-mount .keybind_c2b141 {
	color: var(--header-secondary);
}

#app-mount .emptyStateHeader_d4883c {
	color: var(--header-primary);
}
#app-mount .emptyStateSubtext_d4883c {
	color: var(--header-secondary);
}

#app-mount .codeRedemptionRedirect_a706ba {
	background: var(--background-modifier-selected);
	border-color: var(--background-modifier-selected);
	color: var(--header-primary);
}
#app-mount .subText__6bc46 {
	color: var(--text-muted);
}
#app-mount .subTextHeader__6bc46 {
	color: var(--text-muted);
}
#app-mount .subTextRow__6bc46 {
	color: var(--header-secondary);
}
#app-mount .giftCodeRow__6bc46 {
	border-color: rgba(var(--textdarkest_v), .6);
}
#app-mount .bodyButtonColor__5a673 {
	background: var(--background-tertiary);
	color: var(--header-primary);
}
#app-mount .bodyButtonColor__5a673:hover {
	background: var(--background-secondary);
}
#app-mount .bodyButtonColor__5a673:active {
	background: var(--background-primary);
}
#app-mount .card__6bc46 {
	color: var(--header-primary);
}

#app-mount .gemIndicatorContainer_b03ca0 {
	background-color: var(--background-floating);
}
#app-mount .gemWithoutLabel__6225b {
	color: var(--header-primary);
}
#app-mount .tierLabel__41356 {
	color: var(--header-primary);
}
#app-mount .guildHeaderBackground__04920 {
	background-image: url(https://discord.com/assets/467602d632b5f9c1ce4b.svg);
	opacity: .75;
}

#app-mount .progress__06283 {
	background-color: var(--text-muted);
}
#app-mount .notches__06283.gray__06283 {
	color: var(--background-primary);
}
.icon_f43ba5[src="/assets/6762ed8abdaef6a7f6fc.png"],
.icon_f43ba5[src="/assets/5af9f85713084d6867a6.png"] {
	-webkit-mask: url(https://discord.com/assets/6762ed8abdaef6a7f6fc.png) center/contain no-repeat;
	background-color: var(--header-primary);
	object-position: -999999px -999999px;
}
.icon_f43ba5[src="/assets/ea67b1321e3d4154e476.png"],
.icon_f43ba5[src="/assets/12c09c71eb271a47bcab.png"] {
	-webkit-mask: url(https://discord.com/assets/ea67b1321e3d4154e476.png) center/contain no-repeat;
	background-color: var(--header-primary);
	object-position: -999999px -999999px;
}
.cameraWrapper_d41d5f {
	background-color: var(--background-secondary);
	border-color: var(--background-tertiary);
}

#app-mount .row__740f2 {
	box-shadow: inset 0 -1px 0 rgba(var(--textdarker_v), .3);
}

.disabled_e03935 {
	color: var(--interactive-muted);
}
.option_e03935 {
	background-color: var(--interactive-muted);
}


#app-mount .game_cc46f0 {
	box-shadow: var(--elevation-low);
}
#app-mount .gameName_cc46f0 {
	color: var(--header-primary);
}
#app-mount .gameNameInput_cc46f0:focus,
#app-mount .gameNameInput_cc46f0:hover {
	background-color: var(--background-primary);
	border-color: rgba(var(--textdark_v), .3);
}
#app-mount .lastPlayed_cc46f0,
#app-mount .overlayStatusText__668e1 {
	color: var(--text-muted);
}
#app-mount .toggleIconOn_cc46f0 .fill_cc46f0 {
	fill: var(--text-muted);
}
#app-mount .addGamePopout_cc46f0 {
	background-color: var(--background-primary);
}
#app-mount .addGamePopout_cc46f0 .cancelButton_cc46f0 {
	color: var(--header-primary);
}
#app-mount .nowPlayingAdd_cc46f0 {
	color: var(--header-secondary);
}
#app-mount .nowPlaying_cc46f0 {
	background-color: var(--status-positive-background);
}
#app-mount .nowPlaying_cc46f0 .gameName_cc46f0 {
	color: var(--status-positive-text);
}
#app-mount .nowPlaying_cc46f0 .gameNameInput_cc46f0:focus,
#app-mount .nowPlaying_cc46f0 .gameNameInput_cc46f0:hover {
	background-color: transparent;
	border-color: var(--status-positive-text);
}
#app-mount .nowPlaying_cc46f0 .gameNameInput_cc46f0 {
	position: relative;
	z-index: 3;
}
#app-mount .nowPlaying_cc46f0 .gameNameInput_cc46f0 + * {
	position: relative;
}
#app-mount .nowPlaying_cc46f0 .gameNameInput_cc46f0:focus + *::before,
#app-mount .nowPlaying_cc46f0 .gameNameInput_cc46f0:hover + *::before {
	content: "";
	display: block;
	position: absolute;
	top: -24px;
	left: -5px;
	width: 240px;
	height: 24px;
	border-radius: 3px;
	background-color: var(--status-positive-text);
	opacity: 0.3;
	pointer-events: none;
	z-index: 2;
}
#app-mount .nowPlaying_cc46f0 .lastPlayed_cc46f0,
#app-mount .nowPlaying_cc46f0 .overlayStatusText__668e1 {
	color: var(--status-positive-text);
}
#app-mount .nowPlaying_cc46f0 .toggleIconOff_cc46f0 .fill_cc46f0,
#app-mount .nowPlaying_cc46f0 .toggleIconOn_cc46f0 .fill_cc46f0 {
	fill: var(--status-positive-text);
}
#app-mount .notDetected_cc46f0 {
	background-color: var(--background-secondary);
}
#app-mount .notDetected_cc46f0 .gameName_cc46f0 {
	color: var(--interactive-active);
}
#app-mount .notDetected_cc46f0 .lastPlayed_cc46f0 {
	color: var(--text-muted);
}

.bd-social-link[title="BD" i] .bd-social-logo,
.bd-social-link[title="BetterDiscord" i] .bd-social-logo,
.bd-social-link[title="BBD" i] .bd-social-logo,
.bd-social-link[title="BandagedBD" i] .bd-social-logo {
	background: var(--interactive-normal);
	-webkit-mask: url(https://mwittrien.github.io/BetterDiscordAddons/Themes/_res/svgs/settingsicons/betterdiscord.svg) center/contain no-repeat;
	opacity: 1;
	transition: background .15s ease;
}
.bd-social-link[title="BD" i]:hover .bd-social-logo,
.bd-social-link[title="BetterDiscord" i]:hover .bd-social-logo,
.bd-social-link[title="BBD" i]:hover .bd-social-logo,
.bd-social-link[title="BandagedBD" i]:hover .bd-social-logo {
	background: var(--interactive-active);
}
.bd-social-link[title="BD" i] .bd-social-logo > *,
.bd-social-link[title="BetterDiscord" i] .bd-social-logo > *,
.bd-social-link[title="BBD" i] .bd-social-logo > *,
.bd-social-link[title="BandagedBD" i] .bd-social-logo > * {
	display: none;
}


/* ~~~~		10.		GUILDSETTINGS					~~~~ */

#app-mount .guildSettingsOverviewNotice__3bf33 {
	background-color: rgba(var(--backgroundtertiary_v), .95);
}
#app-mount .dragged_f07e3e {
	-webkit-mask: url(https://discord.com/assets/038a865e09c25dc13e30.svg) center/contain no-repeat;
	background: var(--background-tertiary);
}
.theme-light .messageContainer__981c8 {
	display: none;
}

#app-mount .emojiAliasInput_e7d73e .emojiInput_e7d73e {
	background-color: var(--deprecated-text-input-bg);
	border: 1px solid var(--deprecated-text-input-border);
	margin-top: -1px;
	margin-left: -8px;
}
#app-mount .emojiAliasInput_e7d73e .emojiInput_e7d73e:hover {
	border-color: var(--deprecated-text-input-border-hover);
}
#app-mount .emojiAliasInput_e7d73e .emojiInput_e7d73e:focus {
	border-color: rgb(var(--accentcolor_v));
}
#app-mount .emojiRow_e7d73e:hover .emojiAliasPlaceholderContent_e7d73e,
#app-mount .emojiRow_e7d73e:focus-within .emojiAliasPlaceholderContent_e7d73e {
	visibility: hidden !important;
	color: transparent !important;
}
#app-mount .emojiAliasPlaceholder_e7d73e {
	color: var(--header-primary);
}

#app-mount .auditLog__43dab {
	border-color: var(--background-tertiary);
	color: var(--text-muted);
}
#app-mount .auditLog__43dab strong {
	color: var(--header-primary);
}
#app-mount .auditLog__43dab:hover .expandForeground__43dab {
	stroke: var(--header-primary);
}
#app-mount .headerClickable__43dab,
#app-mount .headerDefault__43dab {
	background-color: rgba(var(--backgroundtertiary_v), .3);
	color: var(--header-secondary);
}
#app-mount .headerExpanded__43dab {
	background-color: rgba(var(--backgroundtertiary_v), .6);
	color: var(--header-secondary);
}
#app-mount .divider__43dab {
	background-color: var(--background-tertiary);
}
#app-mount .userHook__43dab {
	color: var(--header-primary);
}
#app-mount .expandForeground__43dab {
	stroke: rgba(var(--textbrightest_v), .6);
}
#app-mount .timestamp__43dab {
	color: var(--text-muted);
}
#app-mount .changeDetails__43dab {
	background-color: rgba(var(--backgroundtertiary_v), .3);
}
.themeOverrideLight__43dab.icon__43dab,
.themeOverrideDark__43dab.icon__43dab,
#app-mount .icon__43dab {
	background: none !important;
}
.icon__43dab::before {
	content: "";
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	background: var(--header-primary);
}
.icon__43dab.applicationCommand__43dab::before {
	-webkit-mask: url(https://discord.com/assets/295610bf2d3ec357b4bb.svg);
}
.icon__43dab.autoModerationBlockMessage__43dab::before {
	-webkit-mask: url(https://discord.com/assets/2cb2c7601c0b9a2a1ccd.svg);
}
.icon__43dab.autoModerationRule__43dab::before {
	-webkit-mask: url(https://discord.com/assets/2cb2c7601c0b9a2a1ccd.svg);
}
.icon__43dab.targetAll__43dab::before {
	-webkit-mask: url(https://discord.com/assets/cda90da758440b5e2cbc.svg);
}
.icon__43dab.targetBan__43dab::before {
	-webkit-mask: url(https://discord.com/assets/559f43e29d80d719b397.svg);
}
.icon__43dab.targetChannel__43dab::before {
	-webkit-mask: url(https://discord.com/assets/fd8bb90a4678f63f6a50.svg);
}
.icon__43dab.targetEmoji__43dab::before {
	-webkit-mask: url(https://discord.com/assets/b734b6798a8b89611ee7.svg);
}
.icon__43dab.targetGuild__43dab::before {
	-webkit-mask: url(https://discord.com/assets/30039d24e09f9ae53597.svg);
}
.icon__43dab.targetGuildHome__43dab::before {
	-webkit-mask: url(https://discord.com/assets/bde25f93c922e02f8459.svg);
}
.icon__43dab.targetGuildScheduledEvent__43dab::before {
	-webkit-mask: url(https://discord.com/assets/119b4083c9d4fce05f2d.svg);
}
.icon__43dab.targetIntegration__43dab::before {
	-webkit-mask: url(https://discord.com/assets/a82903ac1478ed97b6d4.svg);
}
.icon__43dab.targetInvite__43dab::before {
	-webkit-mask: url(https://discord.com/assets/5cc5c2e0ad18a7c383d8.svg);
}
.icon__43dab.targetMember__43dab::before {
	-webkit-mask: url(https://discord.com/assets/c53abf7172caf6e94497.svg);
}
.icon__43dab.targetMemberRole__43dab::before {
	-webkit-mask: url(https://discord.com/assets/63a73b3d5daccfd7a8fc.svg);
}
.icon__43dab.targetMessage__43dab::before {
	-webkit-mask: url(https://discord.com/assets/f88edd51273b2e14999a.svg);
}
.icon__43dab.targetPermission__43dab::before {
	-webkit-mask: url(https://discord.com/assets/93b984f7ed0c42796562.svg);
}
.icon__43dab.targetRole__43dab::before {
	-webkit-mask: url(https://discord.com/assets/842d46ac28c4cc831849.svg);
}
.icon__43dab.targetStageInstance__43dab::before {
	-webkit-mask: url(https://discord.com/assets/f39f5d92d79071dcd992.svg);
}
.icon__43dab.targetSticker__43dab::before {
	-webkit-mask: url(https://discord.com/assets/0020113abbe97807c0be.svg);
}
.icon__43dab.targetVanityUrl__43dab::before {
	-webkit-mask: url(https://discord.com/assets/9ecac67adfc57255096c.svg);
}
.icon__43dab.targetWebhook__43dab::before {
	-webkit-mask: url(https://discord.com/assets/2cb2c7601c0b9a2a1ccd.svg);
}
.icon__43dab.targetWidget__43dab::before {
	-webkit-mask: url(https://discord.com/assets/fb3b404502ba18187ace.svg);
}
.icon__43dab.thread__43dab::before {
	-webkit-mask: url(https://discord.com/assets/6960c3e51b7f0dcefcc0.svg);
}

#app-mount .card__83361 {
	border-color: var(--background-secondary-alt);
}
#app-mount .card_eafb9c {
	border-color: var(--background-secondary-alt);
}

#app-mount .card__991c2 {
	box-shadow: var(--elevation-high);
}
.splashImage__991c2[src="/assets/467602d632b5f9c1ce4b.svg"],
.splashImage__991c2[src="/assets/d4d9f2bff23beec65b1f.svg"] {
	background: url(https://discord.com/assets/467602d632b5f9c1ce4b.svg) center/cover no-repeat;
	opacity: .75;
	object-position: -999999px -999999px;
}

#app-mount .background_c44edb {
	color: var(--background-tertiary);
}
#app-mount .tierInProgress_c44edb {
	background-color: var(--background-tertiary);
}
#app-mount .tierHeaderLocked_f15dca {
	background-color: var(--background-tertiary);
	color: var(--header-secondary);
}
#app-mount .tierHeaderUnlocked_f15dca {
	background-color: var(--background-tertiary);
}
#app-mount .tierCloseClose_f15dca {
	color: var(--header-primary);
}
#app-mount .tierBody_f15dca {
	background-color: var(--background-secondary);
	color: var(--header-secondary);
}

#app-mount .tierCurrent_fc87b4 {
	box-shadow: 0 4px 8px rgba(0,0,0, .24);
}

#app-mount .member__55269 {
	box-shadow: 0 1px 0 0 rgba(var(--textbrightest_v), .04);
}
#app-mount .member__55269 .name__7635a {
	color: var(--header-primary);
}
#app-mount .member__55269 .tag__1a537 {
	color: var(--text-muted);
}
#app-mount .member__55269 .roleWrapper__0f174 {
	color: rgba(var(--textbrightest_v), .8);
}
#app-mount .member__55269 .overflowIconFg__2b31c {
	fill: var(--header-primary);
}
#app-mount .member__55269 .ownerHelpIcon__021a4 {
	color: var(--header-primary);
}

#app-mount .to__910e1 {
	background-color: var(--background-secondary);
	box-shadow: 0 0 0 4px var(--background-secondary);
}
#app-mount .fromToWrapper__910e1 {
	background: transparent;
}
#app-mount .fromToWrapper__910e1::before {
	content: "";
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	-webkit-mask: url(https://discord.com/assets/a2e6c7df5d20d1aeaacb.svg) 50% 0 no-repeat;
	background: var(--header-primary);
}

#app-mount .inviteSettingsInviteRow__1de14 {
	box-shadow: 0 1px 0 0 rgba(var(--textbrightest_v), .04);
}

#app-mount .bannedUser_cdb2b0 {
	box-shadow: 0 1px 0 0 rgba(var(--textbrightest_v), .04);
}
#app-mount .bannedUser_cdb2b0 .username_cdb2b0 {
	color: var(--header-primary);
}
#app-mount .bannedUserModal_cdb2b0 .reasonHeader_cdb2b0 {
	color: var(--text-normal);
}


/* ~~~~		11.		MODALS						~~~~ */

#app-mount .root__49fc1:not(.noBackground_f061f6),
#app-mount .modal__7f8f5 {
	background-color: var(--background-primary);
	border: none;
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .3), 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .rootWithShadow__49fc1:not(.noShadow_f061f6) {
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .3), 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .zoomedCarouselModalRoot_f74404 {
	background: transparent !important;
}
#app-mount .footer__49fc1,
#app-mount .footer_c33701 {
	background-color: var(--background-secondary);
	color: var(--header-secondary);
}
#app-mount .footerSeparator__49fc1 {
	box-shadow: inset 0 1px 0 rgba(var(--backgroundsecondary_v), .6);
}

#app-mount .modal_6GHvdM .tabBarContainer_b9fccc {
	background: rgba(0,0,0, .2);
	box-shadow: 0 2px 3px 0 rgba(0,0,0, .1);
}

#app-mount .content_a934ca + .videoContainer_a934ca {
	box-sizing: border-box;
	height: 100%;
}
#app-mount .testimonialContainer_d3081b path[fill="#2B2D31"] {
	fill: var(--background-secondary);
}
#app-mount .testimonialContainer_d3081b .quotes__3e7e2 {
	color: var(--header-secondary);
}

#app-mount .separator__33f29 {
	box-shadow: 0 1px 0 0 rgba(var(--backgroundfloating_v), .3), 0 1px 2px 0 rgba(var(--backgroundfloating_v), .3);
}
#app-mount .divider__33f29 {
	border-color: var(--background-secondary);
}

#app-mount .message_fcc792 {
	color: var(--header-secondary);
}
#app-mount .secondaryButton_fcc792 {
	color: var(--header-primary);
}

#app-mount .divider__65336 {
	border-color: var(--background-secondary);
}
#app-mount .backButtonColor__4cae5 {
	color: var(--header-primary);
}
#app-mount .checkboxLabel_a11995 {
	color: var(--header-secondary);
}

/* ----		11.1.		USERMODAL					---- */

.emptyIcon__9d78f {
	opacity: .5;
}

/* ----		11.2.		GUILDADD/CREATION				---- */

.container_eb2cd2 {
	background-color: var(--background-secondary);
	border: none;
}
.container_eb2cd2:hover {
	background-color: var(--background-secondary-alt);
	border: none;
}
.arrow_eb2cd2 {
	-webkit-mask: url(https://discord.com/assets/ebd4163d89c2d849ec54.svg) center/cover no-repeat;
	background: var(--text-normal);
	object-position: -999999px -999999px;
}

.input__991a0 {
	background: transparent;
}
.inputInner__991a0 {
	border: 1px solid var(--deprecated-text-input-border);
}

/* ----		11.3.		UPLOADMODAL					---- */

#app-mount .uploadModal_dbca3c {
	background-color: var(--background-primary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .footer_dbca3c {
	background-color: var(--background-secondary);
	box-shadow: inset 0 1px 0 rgba(var(--backgroundsecondary_v), .6);
}

/* ----		11.4.		KEYBOARDSHORTCUTSMODAL				---- */

#app-mount .keyboardShortcutsModal_f061f6 {
	background-color: var(--background-primary);
}
#app-mount .modalTitle_f061f6 {
	color: var(--header-primary);
}
#app-mount .modalSubtitle_f061f6 {
	border: none;
	box-shadow: var(--elevation-low);
	color: var(--text-normal);
}
#app-mount .keyboardShortcutList_f061f6 .keybindGroup_f061f6 .keybindDescription_c0b6a8 {
	color: var(--header-secondary);
}

#app-mount .combo_fcddc1 {
	color: var(--header-primary);
}
#app-mount .combo_fcddc1 .key_fcddc1 {
	background-color: var(--text-muted);
	border: 1px solid rgba(0, 0, 0, .4);
	box-shadow: inset 0 -4px 0 rgba(0, 0, 0, .4);
	color: var(--header-primary);
}
#app-mount .combo_fcddc1 .key_fcddc1:active {
	box-shadow: inset 0 -2px 0 rgba(0, 0, 0, .6);
	border: 1px solid rgb(0, 0, 0);
	color: var(--header-secondary);
}

/* ----		11.5.		QUICKSWITCHER					---- */

#app-mount .emptyState_ac6cb0 {
	background: transparent;
}
#app-mount .emptyState_ac6cb0::before {
	content: "";
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: url(https://discord.com/assets/c586aac99de98cfb010d.svg) center/100px no-repeat;
	opacity: .5;
}

/* ----		11.6.		INVITEMODAL/GROUPCREATE				---- */

#app-mount .contentWrapper__9b0f4 {
	background-color: var(--background-primary);
}
#app-mount .friendSelected_bbd192,
#app-mount .inviteRow__67dba:hover {
	background-color: var(--background-accent);
	color: var(--header-primary);
}
#app-mount .friend_bbd192,
#app-mount .inviteRowName__67dba {
	color: var(--header-secondary);
}
#app-mount .footer_cba592,
#app-mount .footer__67dba {
	background-color: var(--background-secondary);
	box-shadow: inset 0 1px 0 rgba(var(--backgroundsecondary_v), .6);
}
.footerSeparator_e6af9c {
	display: none;
}
#app-mount .subtitle_cba592,
#app-mount .footerText_cba592,
#app-mount .checkBoxLabel__873a9,
#app-mount .footerText__67dba,
#app-mount .subText__67dba {
	color: var(--header-secondary);
}
#app-mount .errorState_cba592 {
	color: var(--text-muted);
}
#app-mount .notFriends_cba592 .errorStateIcon_cba592 {
	background-image: url(https://discord.com/assets/07aa1f325ebe8b8af5cb.svg);
	opacity: .5;
}
#app-mount .noFriends_cba592 .errorStateIcon_cba592 {
	background-image: url(https://discord.com/assets/adfe130868d2bcf467b5.svg);
	opacity: .5;
}
#app-mount .partyFull_cba592 .errorStateIcon_cba592 {
	background-image: url(https://discord.com/assets/53d74eda11a4185c1acd.svg);
	opacity: .5;
}
#app-mount .noResults_cba592 .errorStateIcon_cba592 {
	background-image: url(https://discord.com/assets/c8718df1382ba878f1fc.svg);
	opacity: .5;
}

/* ----		11.7.		LOGINSCREEN					---- */

.theme-dark.navRow__86e92,
.theme-light.navRow__86e92 {
	background: var(--background-secondary);
}
.subText_dc6abe strong {
	color: rgba(var(--textbright_v), .9);
}

/* ----		11.8.		DOWNLOADAPPMODAL				---- */

.downloadApps__4a98c {
	background-color: var(--background-primary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .3), 0 2px 10px 0 rgba(0,0,0, .2);
}
.downloadApps__4a98c .inner__4a98c {
	height: 100%;
	width: 100%;
	overflow: hidden;
}
.downloadApps__4a98c .header__4a98c {
	color: var(--text-normal);
}
.downloadApps__4a98c .footer__4a98c {
	color: var(--text-muted);
}
.downloadApps__4a98c .header__4a98c {
	color: var(--text-normal);
}
.downloadApps__4a98c .platforms__4a98c .platform__4a98c {
	border-color: var(--header-secondary);
}
.downloadApps__4a98c .platforms__4a98c .platform__4a98c p {
	color: var(--header-secondary);
}
.downloadApps__4a98c .platforms__4a98c .platform__4a98c .downloadButton__4a98c {
	background-color: var(--header-secondary);
}

/* ----		11.9.		GUILDBOOSTMODAL					---- */

#app-mount .subscriberCount_f15dca {
	color: var(--header-secondary);
}
#app-mount .subscriberCount_f15dca strong {
	color: var(--text-normal);
}
#app-mount .moreSubscribers_f15dca {
	background-color: var(--background-tertiary);
	color: var(--header-primary)
}
#app-mount .subscribersPopout_f15dca {
	background: var(--background-floating);
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .subscribersPopoutUser_f15dca {
	color: var(--header-secondary);
}

/* ----		11.10.		REACTIONSMODAL					---- */

#app-mount .container_cc2dff,
#app-mount .reactors_cc2dff {
	background-color: var(--background-primary);
}
#app-mount .remove_cc2dff {
	color: var(--interactive-normal);
}
#app-mount .remove_cc2dff:hover {
	color: var(--interactive-hover);
	background: transparent;
}
#app-mount .remove_cc2dff:active {
	color: var(--interactive-active);
}
#app-mount .scroller_cc2dff {
	background-color: var(--background-secondary);
}
#app-mount .reactionSelected_cc2dff {
	background-color: rgba(var(--backgroundaccent_v), .8);
}
#app-mount .reactionDefault_cc2dff:hover {
	background-color: rgba(var(--backgroundaccent_v), .4);
}
#app-mount .reactorDefault_cc2dff {
	box-shadow: inset 0 -1px 0 rgba(var(--backgroundaccent_v), .3);
}
#app-mount .discriminator_cc2dff {
	color: var(--text-muted);
}

/* ----		11.11.		CHANGELOG					---- */

#app-mount .date__1689b {
	color: var(--header-secondary);
}
#app-mount .content_dc3a33 ol,
#app-mount .content_dc3a33 p,
#app-mount .content_dc3a33 ul li,
#app-mount .content__487be ol,
#app-mount .content__487be p,
#app-mount .content__487be ul li {
	color: var(--header-secondary);
}
#app-mount .content_dc3a33 ul li::before,
#app-mount .content__487be ul li::before {
	background-color: var(--text-normal);
}
#app-mount .video__1689b {
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2);
}
#app-mount .socialLink__1689b {
	color: var(--interactive-normal);
}
#app-mount .socialLink__1689b:hover {
	color: var(--interactive-hover);
}
#app-mount .socialLink__1689b:active {
	color: var(--interactive-active);
}

/* ----		11.12.		NOTIFICATIONSMODAL				---- */

#app-mount .channelName_db81c6 {
	color: var(--header-primary);
}
#app-mount .guildName_db81c6,
#app-mount .override_db81c6,
#app-mount .overrideHighlight_db81c6 {
	color: var(--header-secondary);
}
#app-mount .override_db81c6:hover {
	background-color: rgba(var(--backgroundtertiary_v), .1);
}
#app-mount .overrideHighlight_db81c6,
#app-mount .overrideHighlight_db81c6:hover {
	background-color: rgba(var(--backgroundtertiary_v), .3);
}
#app-mount .checkboxContainer_db81c6::before {
	background-color: rgba(var(--backgroundtertiary_v), .6);
}
#app-mount .overridePlaceholder_db81c6 {
	border: 1px dashed var(--background-floating);
}

/* ----		11.13.		PAYMENTMODAL					---- */

#app-mount .sectionHeader_f0c2ea {
	color: var(--header-secondary);
}

#app-mount .paypalInput_a76d33,
#app-mount .paypalInput_a76d33:focus,
#app-mount .paypalInput_a76d33:hover {
	border-color: var(--deprecated-text-input-border);
}

#app-mount .description__43963 {
	color: var(--text-normal);
}
#app-mount .descriptionWrapper__43963 {
	color: var(--text-muted);
}
#app-mount .defaultIndicator__43963 {
	background-color: var(--text-muted);
	color: var(--header-primary);
}
#app-mount .premiumIndicator__43963 {
	color: var(--header-primary);
}
#app-mount .invalidIndicator__43963 {
	color: var(--header-primary);
}

#app-mount .summaryInfo_e9cb00 {
	color: var(--header-primary);
}
#app-mount .payment_e9cb00 {
	background-color: var(--background-secondary);
	color: var(--header-secondary);
}
#app-mount .hoverablePayment_e9cb00:hover {
	background-color: var(--background-vbackgroundtertiary);
}
#app-mount .paymentHeader_e9cb00 {
	color: var(--header-primary);
	border-color: var(--text-muted);
}
#app-mount .expandedInfo_e9cb00 {
	background-color: var(--background-primary);
}
#app-mount .paymentText_e9cb00 {
	color: var(--header-secondary);
}
#app-mount .giftIcon_e9cb00 {
	color: var(--header-primary);
}

#app-mount .paymentPane__01014 {
	background-color: var(--background-secondary);
	color: var(--header-primary);
}
#app-mount .paginator__01014 {
	background: var(--background-secondary);
	color: var(--text-muted);
}
#app-mount .bottomDivider__01014 {
	border-bottom-color: var(--background-tertiary);
}
#app-mount .tab_b317f5 {
	color: var(--text-muted);
}
#app-mount .externalRowHeader__01014 {
	color: var(--header-secondary);
}

/* ----		11.14.		CLOUDSYNCRESOLUTION				---- */

#app-mount .modal__47998 {
	color: var(--text-normal);
}
#app-mount .conflictButton__47998 {
	background-color: var(--background-secondary);
	border-color: var(--background-tertiary);
}
#app-mount .conflictButton__47998:hover {
	background-color: var(--background-accent);
}
#app-mount .title__47998 {
	color: var(--text-normal);
}
#app-mount .buttonBody__47998 {
	color: var(--header-primary);
}
#app-mount .choiceLine__47998 {
	background-color: rgba(var(--textdarkest_v), .6);
}

/* ----		11.15.		APPLICATIONINSTALLATIONMODAL			---- */

#app-mount .gameName__15293 {
	color: var(--text-normal);
}
#app-mount .installSize__15293 {
	background-color: var(--background-accent);
	color: var(--header-primary);
}
#app-mount .divider__15293 {
	background-color: rgba(var(--backgroundsecondary_v), .6);
}
#app-mount .premiumTerms_a72bfb {
	color: var(--text-normal);
}

/* ----		11.16.		DISPATCHERROR					---- */

#app-mount .body_f3e49b {
	color: var(--text-normal);
}
#app-mount .errorLabel_f3e49b {
	color: var(--header-secondary);
}
#app-mount .errorDetails_f3e49b {
	background: var(--background-secondary);
	border-color: rgba(var(--backgroundsecondary_v), .3);
	color: var(--header-primary);
}
#app-mount .closeLink_f3e49b {
	color: var(--header-primary);
}

/* ----		11.17.		HYPESQUADQUIZ					---- */

#app-mount .prompt__2e257 {
	color: var(--header-primary);
}
#app-mount .selectYourAnswer__2e257 {
	color: var(--channels-default);
}
#app-mount .separator__2e257 {
	background-color: var(--background-accent);
}

/* ----		11.18.		SERVERAPPMODAL					---- */

#app-mount .directoryContainer_da3f59 {
	background: var(--background-primary);
}


/* ~~~~		12.		POPOUTS						~~~~ */

#app-mount .content__79cbe {
	background-color: var(--background-floating) !important;
}
#app-mount .leftArrow_da5928::before {
	border-right-color: var(--background-floating) !important;
}
#app-mount .rightArrow__8c899::before {
	border-left-color: var(--background-floating) !important;
}
#app-mount .contentNarrowNoMedia__79cbe.topArrow__154df::before,
#app-mount .contentWideNoMedia__79cbe.topArrow__154df::before {
	border-bottom-color: var(--header-primary) !important;
}
#app-mount .background__2de27 {
	color: var(--header-primary) !important;
}

#app-mount .popoutLoadingForeground__0f481 {
	background-image: linear-gradient(90deg, var(--background-tertiary),var(--background-accent),var(--background-tertiary));
}

/* ----		12.1.		USERPOPOUT					---- */

#app-mount .outer_c0bea0 {
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
}

#app-mount .outer_c0bea0.custom-profile-theme .inner_c0bea0 .activity_f00225 {
	--bg-surface-overlay: var(--background-secondary-alt);
}
#app-mount .biteSizeOverlayBackground_c69a7b,
#app-mount .fullSizeOverlayBackground_c69a7b,
#app-mount .outer_c0bea0.custom-profile-theme .inner_c0bea0 .activity_f00225,
#app-mount .overlay_c0bea0 {
	--bg-mod-faint: var(--background-primary);
	--border-faint: var(--background-primary);
}

.outer_c0bea0:not(.custom-profile-theme) .container__8061a,
.outer_c0bea0:not(.custom-profile-theme) .statusBubble_af9888,
.outer_c0bea0:not(.custom-profile-theme) .statusBubbleOuter_af9888,
.outer_c0bea0:not(.custom-profile-theme) .statusBubbleOuter_af9888:before,
.outer_c0bea0:not(.custom-profile-theme) .statusBubbleOuter_af9888:after {
	background: var(--background-primary);
	border-color: var(--background-primary);
}

.outer_c0bea0.custom-profile-theme .mask__44b0c circle {
	fill: transparent;
}
#app-mount .outer_c0bea0.custom-profile-theme ::-webkit-scrollbar-thumb {
	background-color: var(--profile-gradient-secondary-color) !important;
}

#app-mount .wumpusTooltip_db70b7 {
	background-color: var(--background-tertiary);
	color: var(--header-primary);
}
#app-mount .wumpusTooltip_db70b7::after {
	border-color: transparent var(--background-tertiary) transparent transparent;
}

.role_dfa8b6[style*="border-color: rgba(185, 187, 190, .6)"] {
	border-color: rgba(var(--textbrighter_v), .6) !important;
}
.role_dfa8b6 .roleCircle__4f569[style*="background-color: rgb(185, 187, 190)"] {
	background-color: rgb(var(--textbrighter_v)) !important;
}
.role_dfa8b6 .roleCircle__4f569[style*="background-color: rgb(185, 187, 190)"] path[fill] {
	fill: rgb(var(--textdarkest_v)) !important;
}

/* ----		12.2.		EMOJIPICKER					---- */

#app-mount .wrapper__29ebd {
	color: var(--text-muted);
}
.categoryItemDefaultCategory_b9ee0c:first-child,
.categoryItemDefaultCategory_b9ee0c:first-child + .categoryItemDefaultCategory_b9ee0c {
	margin-bottom: 8px;
}
#app-mount .imageLoading__1859b {
	background: var(--background-tertiary);
	border-radius: 10px;
}
.premiumPromoClose__3a1b6 {
	-webkit-mask: url(https://discord.com/assets/411dfecce0d7da63ea2b.svg) 50% 50% no-repeat;
	background: var(--interactive-normal);
}
.premiumPromoClose__3a1b6:hover {
	background: var(--interactive-hover);
}
.premiumPromoClose__3a1b6:active {
	background: var(--interactive-active);
}
#app-mount .categoryItemDefaultCategorySelected_b9ee0c .categoryIcon_b9ee0c,
#app-mount .categoryItemDefaultCategorySelected_b9ee0c:hover .categoryIcon_b9ee0c {
	color: var(--interactive-active);
}

#app-mount .inspector_aeaaeb,
#app-mount .wrapper__4e6ce {
	background: var(--background-surface-high);
}

#app-mount .focused_bad108,
#app-mount .result__2dc39:hover {
	box-shadow: 0 11px 22px 1px rgba(4,4,5, .3);
}
#app-mount .focused_bad108::after,
#app-mount .result__2dc39:hover::after {
	box-shadow: inset 0 0 0 2px ,inset 0 0 0 3px var(--background-secondary);
}
#app-mount .placeholder__2dc39 {
	background: rgba(var(--textdarkest_v), .6);
}
#app-mount .endContainer__2dc39::after {
	background-image: url(https://discord.com/assets/6836d88af9197cbd4cbb.svg);
	opacity: .5;
}
#app-mount .endText__2dc39 {
	color: var(--header-secondary);
}
#app-mount .emptyHintCard__2dc39 {
	background-color: var(--background-primary);
	color: var(--header-secondary);
}
#app-mount .container_d5ae15 {
	background-color: var(--background-secondary);
}
#app-mount .header_d5ae15 {
	box-shadow: 0 1px 0 0 rgba(var(--backgroundfloating_v), .3), 0 1px 2px 0 rgba(var(--backgroundfloating_v), .3);
}
#app-mount .backButton_fed6d3 {
	color: var(--interactive-normal);
}
#app-mount .backButton_fed6d3:hover {
	color: var(--interactive-hover);
}
#app-mount .backButton_fed6d3:active {
	color: var(--interactive-active);
}

/* ----		12.3.		SEARCHPOPOUT					---- */

#app-mount .searchAnswer_bd8186,
#app-mount .searchFilter_bd8186 {
	background-color: var(--background-primary);
	color: var(--header-primary);
}

.option__56fec:hover {
	background-color: var(--background-primary);
}

#app-mount .queryContainer__55c99 {
	border-bottom-color: var(--background-modifier-accent);
	color: var(--header-secondary);
}
#app-mount .queryContainer__55c99 strong {
	color: var(--header-primary);
}
#app-mount .focused__55c99 {
	background-color: var(--background-modifier-active);
}

#app-mount .calendarPicker_d27f17 .react-datepicker {
	background: transparent;
}
#app-mount .calendarPicker_d27f17 .react-datepicker__header {
	background-color: var(--background-floating);
	border-color: rgba(var(--backgroundfloating_v), .2);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation {
	background: transparent;
	border-color: rgba(var(--textbrightest_v), .5);
	top: 30px;
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation::before {
	content: "";
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	-webkit-mask: url(https://discord.com/assets/f03e2d8e19438cceaad7.svg) center/6px 12px no-repeat;
	background-color: rgb(var(--textbrightest_v));
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation--previous {
	left: 30px;
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation--next {
	right: 30px;
}
#app-mount .calendarPicker_d27f17 .react-datepicker__current-month {
	border-bottom-color: rgba(var(--backgroundfloating_v), .3);
	color: var(--header-primary);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation.react-datepicker__navigation--next,
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation.react-datepicker__navigation--previous {
	-webkit-mask: url(https://discord.com/assets/f03e2d8e19438cceaad7.svg) 50%/6px 12px no-repeat;
	background: var(--interactive-normal);
	border-color: var(--background-floating);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation.react-datepicker__navigation--next:hover,
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation.react-datepicker__navigation--previous:hover {
	background: var(--interactive-hover);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation.react-datepicker__navigation--next:active,
#app-mount .calendarPicker_d27f17 .react-datepicker__navigation.react-datepicker__navigation--previous:active {
	background: var(--interactive-active);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__week:last-of-type .react-datepicker__day {
	border-bottom-color: var(--background-floating);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__week .react-datepicker__day:last-of-type {
	border-right-color: var(--background-floating);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__day-name {
	color: rgba(var(--textbrightest_v), .6);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__day {
	border-top-color: var(--background-floating);
	border-left-color: var(--background-floating);
	color: var(--header-primary);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__day.react-datepicker__day--selected:hover,
#app-mount .calendarPicker_d27f17 .react-datepicker__day:hover {
	color: var(--header-primary);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__day {
	background-color: var(--background-secondary);
}
#app-mount .calendarPicker_d27f17 .react-datepicker__day.react-datepicker__day--disabled,
#app-mount .calendarPicker_d27f17 .react-datepicker__day.react-datepicker__day--disabled:hover {
	background-color: var(--background-floating);
	color: rgba(var(--textbrightest_v), .3);
	cursor: no-drop;
}
#app-mount .calendarPicker_d27f17 .react-datepicker__day--outside-month {
	background-color: var(--background-tertiary);
	color: rgba(var(--textbrightest_v), .3);
}

/* ----		12.4.		EVERYONEMENTION					---- */

.contentWarningPopout_be95d0 .animation_be95d0 {
	opacity: 0.6;
}
#app-mount .footer_be95d0 {
	background-color: rgba(var(--backgroundtertiary_v), .4);
	color: var(--text-muted);
}

/* ----		12.5.		CHANNELFOLLOW					---- */

#app-mount .header_d5f35b {
	background: var(--background-tertiary);
}
#app-mount .header_d5f35b::before {
	content: "";
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: var(--header-primary);
	-webkit-mask: url(https://discord.com/assets/e9661fbf5e8e3a2e1ac9.svg) center/cover no-repeat;
}

/* ----		12.6.		CHANNELFOLLOWINFO				---- */

#app-mount .guildPopout__51eb2 {
	background-color: var(--background-tertiary);
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2), 0 0 0 1px rgba(var(--backgroundtertiary_v), .6);
}
#app-mount .guildName__51eb2 {
	color: var(--header-primary);
}
#app-mount .dotOffline__1bff9 {
	background-color: var(--header-secondary);
}
#app-mount .placeholderSkeleton__51eb2 {
	background: var(--text-muted);
}

/* ----		12.7.		STREAMPREVIEW					---- */

#app-mount .streamPreview__6da2d {
	background-color: var(--background-tertiary);
}
#app-mount .previewContainer__6da2d {
	background-color: var(--background-secondary-alt);
}
#app-mount .applicationName__15b86 {
	color: var(--header-primary);
}
#app-mount .watchButton__6da2d {
	border-color: var(--text-muted);
	color: var(--header-primary);
}
#app-mount .watchButton__6da2d:not([disabled]):hover {
	border-color: var(--header-primary);
}
#app-mount .previewHover__6da2d {
	background: rgba(0,0,0, .6);
}

/* ----		12.8.		ROLEOVERFLOW					---- */

#app-mount .overflowRolesPopoutHeaderText__48c1c {
	color: var(--text-muted);
}
#app-mount .actionButton__48c1c {
	border-color: var(--header-secondary);
	color: var(--header-secondary);
}
#app-mount .overflowRolesPopout__48c1c {
	color: rgba(var(--textbrightest_v), .8);
}
#app-mount .overflowRolesPopout__48c1c,
#app-mount .overflowRolesPopoutArrow__48c1c {
	background-color: var(--background-tertiary);
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2), 0 0 0 1px rgba(var(--backgroundtertiary_v), .6);
}

/* ----		12.9.		PUBLICGUILDANNOUNCEMENT				---- */

#app-mount .popout_d5c2c4 {
	background-color: var(--background-tertiary);
	box-shadow: 0 2px 10px 0 rgba(0,0,0, .2), 0 0 0 1px rgba(var(--backgroundtertiary_v), .6);
}
#app-mount .popout_d5c2c4 {
	color: var(--header-primary);
}

/* ----		12.10.		QUICKSELECTPOPOUT				---- */

#app-mount .selectableItem_eb626b {
	color: var(--header-primary);
}
#app-mount .selectableItem_eb626b:hover {
	background-color: var(--background-accent);
}
#app-mount .popoutList__92efc {
	background: var(--background-primary);
}
#app-mount .popoutListEmpty__92efc {
	color: var(--header-primary);
}
#app-mount .quickSelectArrow__5988b {
	-webkit-mask: url(https://discord.com/assets/c4643b70509c385fcc83.svg) 50% no-repeat;
	background: var(--interactive-normal);
}
#app-mount .quickSelectPopout_ebaca5 {
	background: var(--background-secondary);
	color: var(--header-primary);
}
#app-mount .quickSelectPopoutOption_b852b1:hover {
	background-color: var(--background-accent);
}

/* ----		12.11.		RTCSTATUSPOPOUT					---- */

#app-mount .container__13b2a {
	width: 290px;
}
#app-mount .container__13b2a canvas {
	background-color: #36393f;
	padding: 5px;
	border-radius: 5px;
}
#app-mount .container__13b2a section {
	background-color: var(--background-primary);
}
#app-mount .container__13b2a section p {
	color: var(--header-primary);
}
#app-mount .container__13b2a section strong {
	color: var(--header-primary);
}
#app-mount .debugButton__83d1b {
	color: var(--header-secondary);
}
#app-mount .krispLogo_e131a9 {
	-webkit-mask: url(https://discord.com/assets/ea67b1321e3d4154e476.svg) center/contain no-repeat;
	background-color: var(--header-primary);
}

/* ----		12.12.		PHONE-/EMAILVALIDATION				---- */

#app-mount .input_f89ba0 {
	background-color: var(--background-accent);
	color: var(--header-primary);
}
#app-mount .phoneFieldPopout__61a01 .countryName__61a01 {
	color: var(--header-secondary);
}
#app-mount .phoneFieldPopout__61a01 .countryCode__61a01 {
	color: var(--header-primary);
}
#app-mount .activityInviteEducationArrow_b88801 {
	-webkit-mask: url(https://discord.com/assets/6f222b93b4b971e68613.svg) center/contain no-repeat;
	background: var(--header-primary);
}

#app-mount .emailVerificationModal_a2241a .title_a2241a {
	color: var(--header-primary);
}
#app-mount .emailVerificationModal_a2241a .body_a2241a {
	color: var(--text-muted);
}

#app-mount .verification_dede4b .image_dede4b {
	background-image: url(https://discord.com/assets/8f8162ee689b2d85996c.svg);
	opacity: .5;
}
#app-mount .verification_dede4b .title_dede4b {
	color: var(--header-primary);
}
#app-mount .verification_dede4b .body_dede4b,
#app-mount .verification_dede4b .footer_dede4b {
	color: var(--header-secondary);
}
#app-mount .verificationBlock__2ee71 {
	border: 1px solid var(--background-tertiary);
}
#app-mount .verificationBlock__2ee71:hover {
	background-color: var(--background-tertiary);
}
#app-mount .verificationBlock__2ee71 .image_dede4b.email__44f2f {
	background-image: url(https://discord.com/assets/9e9722bd5c8ec20fd746.svg);
	opacity: .5;
}
#app-mount .verificationBlock__2ee71 .image_dede4b.phone__0b460 {
	background-image: url(https://discord.com/assets/e9802d8cbd4efea22c7f.svg);
	opacity: .5;
}
#app-mount .verificationBlock__2ee71 .body_dede4b {
	color: var(--header-secondary);
}

/* ----		12.13.		WARNINGPOPOUT					---- */

#app-mount .contentWarningPopout_be95d0 {
	background-color: var(--background-primary);
	box-shadow: 0 2px 10px 0 rgba(var(--backgroundtertiary_v), .2);
}
#app-mount .body_be95d0 {
	color: var(--header-secondary);
}
#app-mount .header_be95d0 {
	color: var(--header-primary);
}

/* ----		12.14.		ADDROLE						---- */

#app-mount .container_d5ae15 {
	width: 300px;
}
#app-mount .autocompleteArrow_d5ae15,
#app-mount .header_d5ae15 {
	background-color: var(--background-tertiary);
}
#app-mount .container_d5ae15 .input_d5ae15 {
	color: var(--header-primary);
}
#app-mount .container_d5ae15 .sectionTag_d5ae15 {
	background-color: var(--background-secondary);
	color: var(--header-secondary);
}

/* ----		12.15.		APPPICKER						---- */

.container_cb32c7:hover,
.keyboard-mode .container_cb32c7:focus {
	background-color: var(--background-accent);
}


/* ~~~~		13.		BDSUPPORT					~~~~ */

html .toast,
html .bd-toast {
	background-color: var(--background-floating);
	box-shadow: var(--elevation-medium);
	color: var(--header-primary);
}

html .bd-settings-group.collapsible .bd-settings-title:hover {
	color: var(--text-normal);
	cursor: pointer;
}
html .bd-settings-group.collapsible .bd-settings-title::before {
	background-color: currentColor;
	opacity: 0.2;
}
html .bd-settings-group.collapsible .bd-settings-title::after {
	background-color: currentColor;
}

.bd-select {
	border: 1px solid transparent;
	padding: 8px 8px 8px 12px;
	cursor: pointer;
	box-sizing: border-box;
	display: grid;
	grid-template-columns: 1fr auto;
	align-items: center;
	border-radius: 4px;
}


.bd-slider-input[type="range"]::-webkit-slider-thumb {
	background-color: #fff;
	border-color: var(--background-accent);
}

.bd-tab-item.selected:hover {
	background-color: var(--background-modifier-selected);
}

.bd-error-modal-content {
	padding: 0 10px 16px 10px;
}

#app-mount .fav {
	background: var(--interactive-active);
	width: 16px;
	height: 16px;
	padding: 0;
	-webkit-mask: url(https://mwittrien.github.io/BetterDiscordAddons/Themes/_res/svgs/common/fav_star_empty.svg) center/contain no-repeat;
}
#app-mount .fav:hover,
#app-mount .fav.active {
	background: #faa61a;
}
#app-mount .fav.active {
	-webkit-mask: url(https://mwittrien.github.io/BetterDiscordAddons/Themes/_res/svgs/common/fav_star.svg) center/contain no-repeat;
}

html .floating-window.resizable {
	background: var(--background-tertiary);
	border-radius: 3px;
}
html .floating-window-titlebar {
	background: var(--background-tertiary);
	border-bottom-color: var(--background-modifier-hover);
	color: var(--header-primary);
	width: unset;
	height: 32px;
	padding: 0;
}
html .floating-window-buttons,
html .floating-window-buttons .button {
	display: flex;
	justify-content: center;
	align-items: center;
	height: 100%;
	padding: 0;
}
html .floating-window-buttons .button {
	width: 32px;
}
html .floating-window-buttons .button:hover {
	background-color: var(--background-modifier-hover);
	color: var(--interactive-hover);
}
html .floating-window-buttons .close-button:hover {
	background-color: rgb(var(--dangercolor_v));
	color: var(--interactive-hover);
}
html .floating-window-buttons .button svg {
	margin: 0;
}
html .floating-window-buttons .close-button svg path.fill,
html .floating-window-buttons .button:not(.close-button) svg path:not([fill]) {
	fill: var(--interactive-normal);
}
html .floating-window-buttons .button:not(.close-button):hover svg path:not([fill]) {
	fill: var(--interactive-hover);
}
html .floating-window-buttons .close-button:hover svg path.fill {
	fill: #fff;
}
html .floating-window-content {
	background: var(--background-tertiary);
	color: var(--header-primary);
}
html #bd-editor-controls,
html .floating-window #bd-editor-controls {
	box-shadow: unset;
	height: 32px;
	padding: 0;
}
html .controls-section,
html #bd-editor-controls button {
	display: flex;
	justify-content: center;
	align-items: center;
	height: 100%;
	padding: 0;
}
html #bd-editor-controls button {
	color: var(--interactive-normal);
	border-radius: 0;
	margin: 0;
	width: 32px;
}
html #bd-editor-controls button:hover {
	background-color: var(--background-modifier-hover);
	color: var(--interactive-hover);
}
html #bd-editor-controls button path:not([fill]) {
	fill: currentColor;
}

html #bd-editor-panel #bd-editor-controls {
	background-color: var(--background-tertiary);
	border-radius: 5px 5px 0 0;
	overflow: hidden;
}
html #bd-editor-panel .editor-wrapper {
	background-color: var(--background-secondary);
	border-radius: 0 0 5px 5px;
	overflow: hidden;
}
html .floating-window #bd-editor-panel .editor-wrapper:last-child {
	border-radius: 0;
}

html .monaco-editor .minimap,
html .monaco-editor .decorationsOverviewRuler {
	display: none;
}

html .monaco-editor,
html .monaco-editor-background,
html .monaco-editor .inputarea.ime-input,
html .monaco-editor .margin {
	background-color: var(--background-secondary);
}
html .monaco-editor,
html .monaco-editor .inputarea.ime-input {
	color: var(--text-normal);
}
html .mtk9 {
	color: var(--text-normal);
}
html .monaco-editor .line-numbers {
	color: var(--channels-default);
}
html .monaco-editor .bracket-match {
	border-color: var(--channels-default);
}
html .monaco-editor .lines-content .cigr {
	box-shadow: 1px 0 0 0 var(--interactive-muted) inset;
}
html .monaco-editor .view-overlays .current-line {
	border-color: var(--interactive-muted);
}

html .monaco-editor .selected-text {
	background-color: var(--background-tertiary);
}
html .monaco-editor .focused .selected-text {
	background-color: rgb(var(--mentioncolor, --warningcolor_v));
}

html .monaco-editor.rename-box {
	background-color: var(--background-secondary) !important;
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2) !important;
	color: var(--header-secondary) !important;
}
html .monaco-editor.rename-box .rename-input {
	background-color: var(--background-primary) !important;
	color: var(--text-normal) !important;
}
html .monaco-editor .find-widget {
	background-color: var(--background-secondary);
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2);
	color: var(--header-secondary);
}
html .monaco-editor .find-widget .monaco-sash {
	background-color: var(--background-accent);
}
html .monaco-editor .find-widget .monaco-inputbox,
html .monaco-editor .find-widget .monaco-inputbox textarea {
	background-color: var(--background-primary) !important;
	color: var(--text-normal) !important;
}
html .monaco-editor .find-widget .button:not(.disabled):hover,
html .monaco-editor.hc-black .find-widget .button:not(.disabled):hover,
html .monaco-editor.vs-dark .find-widget .button:not(.disabled):hover {
	background-color: var(--background-modifier-hover);
}

html .monaco-editor .monaco-editor-hover {
	background-color: var(--background-secondary) !important;
	border: unset !important;
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2) !important;
	color: var(--header-secondary) !important;
}
html .monaco-editor .monaco-editor-hover .hover-row:not(:first-child):not(:empty) {
	border-color: var(--background-modifier-accent);
}
html .monaco-editor .monaco-editor-hover .hover-row .actions {
	background-color: var(--background-floating);
}
html .monaco-editor .monaco-editor-hover .monaco-editor-hover-content[style*="max-height"] {
	max-height: 300px !important;
}

html .monaco-quick-open-widget {
	background-color: var(--background-secondary) !important;
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2) !important;
	color: var(--header-secondary) !important;
}
html .monaco-quick-open-widget input {
	background-color: var(--background-primary) !important;
	color: var(--text-normal) !important;
}
html .monaco-quick-open-widget .results-group {
	color: var(--text-muted) !important;
}
html .monaco-tree[class*="monaco-tree-instance"] .monaco-tree-rows > .monaco-tree-row:hover:not(.highlighted):not(.selected):not(.focused) {
	background-color: var(--background-primary) !important;
	color: var(--header-primary) !important;
}
html .monaco-tree[class*="monaco-tree-instance"] .monaco-tree-rows > .monaco-tree-row:hover:not(.highlighted):not(.selected):not(.focused) .results-group {
	color: var(--header-primary) !important;
}

html .monaco-editor .findOptionsWidget {
	background-color: var(--background-secondary) !important;
	box-shadow: 0 0 0 1px rgba(var(--backgroundtertiary_v), .6), 0 2px 10px 0 rgba(0,0,0, .2) !important;
	color: var(--header-secondary) !important;
}

html .monaco-editor .peekview-widget .head {
	background: var(--background-tertiary) !important;
}
html .monaco-editor .peekview-widget .head .peekview-title .filename {
	color: var(--header-primary) !important;
}
html .monaco-editor .peekview-widget .head .peekview-title .dirname {
	color: var(--header-secondary) !important;
}
html .monaco-editor .reference-zone-widget .ref-tree {
	background: var(--background-secondary) !important;
	color: var(--header-secondary) !important;
}
html .monaco-list[class*="list_id"] .monaco-list-rows {
	background: var(--background-secondary) !important;
}
html .monaco-list[class*="list_id"] .monaco-list-row {
	color: var(--text-muted) !important;
}
html .monaco-drag-image,
html .monaco-list[class*="list_id"] .monaco-list-row.focused,
html .monaco-list[class*="list_id"] .monaco-list-row.focused:hover,
html .monaco-list[class*="list_id"] .monaco-list-row.selected,
html .monaco-list[class*="list_id"] .monaco-list-row.selected:hover,
html .monaco-list[class*="list_id"]:focus .monaco-list-row.selected.focused,
html .monaco-list[class*="list_id"]:not(.drop-target) .monaco-list-row:hover:not(.selected):not(.focused) {
	color: var(--header-primary) !important;
}
html .monaco-list[class*="list_id"] .monaco-list-row.focused,
html .monaco-list[class*="list_id"] .monaco-list-row.focused:hover,
html .monaco-list[class*="list_id"] .monaco-list-row.selected,
html .monaco-list[class*="list_id"] .monaco-list-row.selected:hover,
html .monaco-list[class*="list_id"]:not(.drop-target) .monaco-list-row:hover:not(.selected):not(.focused) {
	background: var(--background-primary) !important;
}
html .monaco-editor .reference-zone-widget .preview .monaco-editor .margin {
	background: var(--background-secondary) linear-gradient(0deg, rgba(var(--accentcolor_v), .1), rgba(var(--accentcolor_v), .1));
}
html .monaco-editor .reference-zone-widget .preview .monaco-editor .monaco-editor-background,
html .monaco-editor .reference-zone-widget .preview .monaco-editor .inputarea.ime-input {
	background: var(--background-secondary) linear-gradient(0deg, rgba(var(--accentcolor_v), .1), rgba(var(--accentcolor_v), .1));
}
html .monaco-editor .reference-zone-widget .ref-tree .monaco-list:focus .monaco-list-rows > .monaco-list-row.selected:not(.highlighted) {
	background: var(--background-primary) !important;
	color: var(--header-primary) !important;
}
html .monaco-editor .reference-zone-widget .ref-tree .referenceMatch .highlight {
	background: rgb(var(--mentioncolor, --warningcolor_v));
}
html .codicon-close,
html .codicon-remove-close,
html .codicon-x {
	color: var(--interactive-normal) !important;
}
html .codicon-close:hover,
html .codicon-remove-close:hover,
html .codicon-x:hover {
	color: var(--interactive-hover) !important;
}

html .monaco-menu .monaco-action-bar.vertical {
	cursor: default;
	background: var(--background-floating) !important;
	border-radius: 4px;
	box-shadow: var(--elevation-high);
	box-sizing: border-box;
	color: var(--text-normal) !important;
	padding: 8px 6px;
	height: auto;
	max-height: calc(100vh - 32px);
}
html .monaco-menu .monaco-action-bar.vertical .action-label.separator {
	border-bottom: 1px solid var(--background-modifier-accent) !important;
	box-sizing: border-box;
	margin: 4px;
	padding: 0;
	opacity: 1;
}
html .monaco-menu .monaco-action-bar.vertical .action-menu-item {
	position: relative;
	display: flex;
	justify-content: space-between;
	align-items: center;
	border-color: var(--interactive-normal) !important;
	border-radius: 2px;
	box-sizing: border-box;
	color: var(--interactive-normal) !important;
	cursor: pointer;
	margin: 2px 0;
	padding: 6px 8px;
	line-height: 18px;
	font-size: 14px;
	font-weight: 500;
	box-sizing: border-box;
	min-height: 32px;
}
html .monaco-menu .monaco-action-bar.vertical .action-menu-item[style*="color: rgb(255, 255, 255)"],
html .monaco-menu .monaco-action-bar.vertical .action-menu-item:hover {
	border-color: #ffffff !important;
	color: #ffffff !important;
}
html .monaco-menu .monaco-action-bar.vertical .action-menu-item > * {
	border-color: currentColor !important;
	color: currentColor !important;
}
html .monaco-menu .monaco-action-bar.vertical .action-label {
	flex: 1 1 auto;
	white-space: nowrap;
	overflow: hidden;
	font-size: unset;
	line-height: unset;
	text-overflow: ellipsis;
	padding: unset;
}
html .monaco-menu .monaco-action-bar.vertical .keybinding,
html .monaco-menu .monaco-action-bar.vertical .submenu-indicator {
	font-size: unset;
	line-height: unset;
	padding-left: unset;
	flex: 0 0 auto;
	max-height: 18px;
	margin-left: 8px;
}
html .monaco-menu .monaco-action-bar.vertical .submenu-indicator.codicon::before {
	margin-left: 0;
	margin-right: -4px;
	flex: 2 1 auto;
}


/* ~~~~		14.		POWERCORDSUPPORT				~~~~ */

html .powercord-toast-container {
  --toast-background: var(--background-secondary);
  --toast-header: var(--background-tertiary);
  --toast-contents: var(--background-primary);
  --toast-box-shadow: var(--elevation-stroke),var(--elevation-high);
  --toast-border: transparent;
}

html .powercord-pc-icon {
	margin-right: 4px;
}
html .powercord-pc-icon svg {
	padding-right: 0;
	width: 28px;
}
html .powercord-pc-icon::before {
	background: var(--interactive-normal);
	-webkit-mask: url('data:image/png; base64, iVBORw0KGgoAAAANSUhEUgAAAcEAAAHBAgMAAABs1eh7AAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAJUExURQAAAK2trf///xHpVx0AAAACdFJOUwAQayTdXAAABbVJREFUeNrt3UFy8jgQQGFVL2aho+iUqjmJalYqnXISYAgmwbjVrcfkp30Av5I/2RhHMSnZtzx6QrcyPjYyKJ9BdJTjvFUsmC/Fziqikv8FR4MPKndYrwcVO6xfQWi2yk2xwYwU5A0jBDnoomyKFWZkpk7Bi5sgMVkFL2a8uGUkTo9BFwUv5vtipRnXFwddFLyY8WLBi9+Cqy/lghczXix4cdDFHxgXz9WMFwteHHRR8GLGiz8xDpxx4IwDZ+w4Y8cZG87YaMalp2PBi4M+OX5m7DhjC8ZgfFfGMmBGuUpRjPk6DIqxXKkoxus4QMaLFch4GQjJeMYiGU8jQRlPWijjaSgs4ycXy/gxFpjxwwtm/BgMzfhooz6DCcYH20LGB1swBmMw/rmMGWcsNOOzYsOLFS8mutjx4oqv/3mScd44zzEakGWKMVuUZxjFdO6UCUbbcsg8wWg7XUXPKLazR/SMxuWQWc9oXA5ZDIxzs9XCOAVpYpyCtDHOFG2MM1PHxjgxdYyME0Uj48RktTLqi1ZG9WQ1M6qLZkb16WFmVBfNjNqinVFbdGBUXgIcGJVF/W2ccTmk6G9Vjcshs/523Lgcsui/chi/0+q/VomtKPqvjtlWzPqvx8VWnHgEYHw2oX9aZVwOOfFEzrgc8tnzsX7Mobox/gRpfMb0LPh9X2J7xiRPi+2Qgx/jD5DG5ZBPGb/vzPjk7nnwHlJsT+7kQLEdcOiOjN/2VmzPCg8w3hsZn04eCW4hxfaQWQ4V23OH6sl4B1lsJ8chxu3+jI+1jwVvj5lxrYAcLLZnDs2XcTME41qBg4y3kMa/hxwNfo0BYrxxghhvBkExfkFRjNdRYIxeyyGzothpRqflkJqgy3JIURUbzOizHFLF6LIcUhd0WA4pymKDGT2WQyoZHZZDaoPm5ZCiLjaY0b4cUs1oXvLhFVzIaF3ykb2KwRiMwRiMwRiMfwij4IwZZyw0o1ux4VO14sVET9WOF48zZpwx04xeJ0fHiw0vev4Z15sx4YwJZ0w4o+CMgjMKzig0o1Mx0cWOFxterHgxvcEY2xvMVf58fME1p73BZ4cKEr8H+LX3Ofy9nAaSvyf/td87FMWMTx3+GytflDcopncoFvzCyhczfc15wb1VoieOT1H3z4AFZvSZOipGl6mTEgyp/Z/OAjN6QFZlUWhGO6T+P9cLzGiHrOqi0IxWyJl3VxSY0QpZJ4pCM9og597sMgn5zyzjNGSdZZyGvHnxLQPZb17uy0C2mxcYM5D189jUyaJMnogyO8QpSOPbwgpzPbVBVltRoOupBdL80rcCM05AVnyMiXY0M0owBmMwBmMwBmMwBmMw/kbGjDMWmlFdbHix4sVEFztebHix4kV7cOZlBOh11YFx5qUSKKRHcOblICCkC+PMS158If9ezngPmZYz3kH2vbnrxLiFbDPvtTWNse7N3bSiuDd33X5II9/ttCxnLHc7zasZN8W6dxFKK6bq3kWoryj2vU+TtmKqtr1Pk7qiWPc+TdKKk2Pv06SvKPa92wI3xtPu23aneSnjqVjLZqeylPH8M6h5u9OljKe9n0fV9+7vmnMxbXeaVzLKuL6fqu7d3yXvYt7udCXjpSjbnZaFjHLZ3XaneR3jad/nz+HdG/XkW6xPb9T7+mJZxviomJcxPirKMsaHy3qWMT4s5lWMD4uy6qA+XixVFh3Ux8W8ZqbuFNOiIe4UZc0Q9xa9lQUTdb94Trr//OLuwj5Z9QOzCd2iGEXXT+Qo/sJiQ4vykmKPovc28IvOa4rsCVleUmRPyIxP1vySE3LwxYqfHg0vdvz0GHyx0qcHCyk4pAwccuCQBYfMbwApPOTAIQsOmQMyIAMyIAMyIAMyIAMyIP/3kH8FZJyRARmQARmQARmQARmQARmQIORb/OEs4ZAJh0w4ZMIhEw6ZaEh45ZXgxY/D2hJ9WB139i9DGxh/HluS1wAAAABJRU5ErkJggg==') left/18px 18px no-repeat;
}
html .powercord-pc-icon:hover::before {
	background: var(--interactive-hover);
}
html .powercord-pc-icon:active::before {
	background: var(--interactive-active);
}


/* ~~~~		15.		PLUGINSUPPORT					~~~~ */

/* ----		15.1.		MEMBERCOUNT					---- */

#app-mount #MemberCount {
	background-color: var(--background-secondary);
}

/* ----		15.2.		CHANNELTABS					---- */

html #channelTabs-settingsMenu,
html .channelTabs-tabNav > div,
html .channelTabs-tab,
html .channelTabs-fav {
	cursor: pointer;
}
html #channelTabs-settingsMenu:hover [fill]:not([fill="none"]),
html .channelTabs-tabContainer .channelTabs-tabNav > div:hover [fill]:not([fill="none"]),
html .channelTabs-tabContainer .channelTabs-newTab:hover [fill]:not([fill="none"]) {
	fill: var(--header-primary);
}
html .channelTabs-tabContainer .channelTabs-tabNav > .channelTabs-tabNavClose:hover {
	background: rgb(var(--dangercolor_v));
}

/* ----		15.3.		TYPINGINDICATOR					---- */

html .typingindicator-guild,
html .typingindicator-dms,
html .typingindicator-folder {
	background: var(--background-tertiary);
	border: 4px solid var(--background-tertiary);
	border-right: unset;
	box-shadow: unset;
	right: 12px;
	bottom: -5px;
	padding: 2px 0;
}
html .wrapper__48112 .typingindicator-guild,
html .typingindicator-folder {
	background: var(--background-secondary);
	border-color: var(--background-secondary);
}


/* ~~~~		16.		WATERMARK					~~~~ */

html:only-child > head + body div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed {
	display: block !important;
	position: absolute !important;
	max-width: unset !important;
	min-width: unset !important;
	width: 55px !important;
	max-height: unset !important;
	min-height: unset !important;
	height: 16px !important;
	margin: 0 !important;
	padding: 3px 9px 3px !important;
	top: 0 !important;
	left: 0 !important;
	bottom: unset !important;
	right: unset !important;
	opacity: 1 !important;
	visibility: visible !important;
	transform: unset !important;
	animation: unset !important;
}
html:only-child > head + body div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed[style*="display: none"] {
	display: none !important;
}
html:only-child > head + body div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed > * {
	display: none !important;
}
html:only-child > head + body div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed::before,
html:only-child > head + body div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed::after {
	content: "" !important;
	-webkit-mask: url('data:image/svg+xml; utf8, <svg width="55" height="19" version="1.1" xmlns="http://www.w3.org/2000/svg"><path fill="black" d="M3.57642276,0.141304348 L0,0.141304348 L0,4.22826087 L2.38069106,6.40217391 L2.38069106,2.43478261 L3.66260163,2.43478261 C4.47052846,2.43478261 4.86910569,2.83695652 4.86910569,3.4673913 L4.86910569,6.5 C4.86910569,7.13043478 4.49207317,7.55434783 3.66260163,7.55434783 L0,7.55434783 L0,9.85869565 L3.57642276,9.85869565 C5.49390244,9.86956522 7.29288618,8.90217391 7.29288618,6.66304348 L7.29288618,3.39130435 C7.29288618,1.13043478 5.49390244,0.141304348 3.57642276,0.141304348 Z M22.3310976,6.67391304 L22.3310976,3.32608696 C22.3310976,2.11956522 24.4640244,1.83695652 25.1103659,3.05434783 L27.0817073,2.23913043 C26.3168699,0.510869565 24.8949187,0 23.7207317,0 C21.803252,0 19.9073171,1.13043478 19.9073171,3.32608696 L19.9073171,6.67391304 C19.9073171,8.88043478 21.803252,10 23.6776423,10 C24.8841463,10 26.3276423,9.39130435 27.1247967,7.81521739 L25.0134146,6.82608696 C24.4963415,8.17391304 22.3310976,7.84782609 22.3310976,6.67391304 Z M15.8030488,3.7826087 C15.0597561,3.61956522 14.5642276,3.34782609 14.5319106,2.88043478 C14.575,1.75 16.2878049,1.7173913 17.2896341,2.79347826 L18.8731707,1.55434783 C17.8821138,0.326086957 16.7617886,0 15.598374,0 C13.8424797,0 12.1404472,1 12.1404472,2.91304348 C12.1404472,4.77173913 13.5408537,5.76086957 15.0813008,6 C15.8676829,6.10869565 16.7402439,6.42391304 16.7186992,6.97826087 C16.654065,8.02173913 14.5426829,7.9673913 13.5839431,6.7826087 L12.0650407,8.23913043 C12.9591463,9.40217391 14.1764228,10 15.3182927,10 C17.074187,10 19.0239837,8.9673913 19.0993902,7.08695652 C19.2071138,4.69565217 17.5050813,4.09782609 15.8030488,3.7826087 Z M8.59634146,9.85869565 L11.0093496,9.85869565 L11.0093496,0.141304348 L8.59634146,0.141304348 L8.59634146,9.85869565 Z M49.2835366,0.141304348 L45.7071138,0.141304348 L45.7071138,4.22826087 L48.0878049,6.40217391 L48.0878049,2.43478261 L49.3589431,2.43478261 C50.1668699,2.43478261 50.5654472,2.83695652 50.5654472,3.4673913 L50.5654472,6.5 C50.5654472,7.13043478 50.1884146,7.55434783 49.3589431,7.55434783 L45.6963415,7.55434783 L45.6963415,9.85869565 L49.2727642,9.85869565 C51.1902439,9.86956522 52.9892276,8.90217391 52.9892276,6.66304348 L52.9892276,3.39130435 C53,1.13043478 51.2010163,0.141304348 49.2835366,0.141304348 Z M31.7353659,0 C29.753252,0 27.7819106,1.09782609 27.7819106,3.33695652 L27.7819106,6.66304348 C27.7819106,8.89130435 29.7640244,10 31.7569106,10 C33.7390244,10 35.7103659,8.89130435 35.7103659,6.66304348 L35.7103659,3.33695652 C35.7103659,1.10869565 33.7174797,0 31.7353659,0 Z M33.2865854,6.66304348 C33.2865854,7.35869565 32.5109756,7.7173913 31.7461382,7.7173913 C30.9705285,7.7173913 30.1949187,7.36956522 30.1949187,6.66304348 L30.1949187,3.33695652 C30.1949187,2.61956522 30.9489837,2.23913043 31.7030488,2.23913043 C32.4894309,2.23913043 33.2865854,2.58695652 33.2865854,3.33695652 L33.2865854,6.66304348 Z M44.3605691,3.33695652 C44.3067073,1.05434783 42.7770325,0.141304348 40.8056911,0.141304348 L36.9815041,0.141304348 L36.9815041,9.86956522 L39.4268293,9.86956522 L39.4268293,6.77173913 L39.8577236,6.77173913 L42.0768293,9.85869565 L45.0930894,9.85869565 L42.4861789,6.52173913 C43.6495935,6.15217391 44.3605691,5.14130435 44.3605691,3.33695652 Z M40.8487805,4.65217391 L39.4268293,4.65217391 L39.4268293,2.43478261 L40.8487805,2.43478261 C42.3784553,2.43478261 42.3784553,4.65217391 40.8487805,4.65217391 Z" transform="translate(1 3)"></path></svg>') center/contain no-repeat !important;
	width: 55px !important;
	height: 19px !important;
	display: inline !important;
	position: absolute !important;
	top: unset !important;
	left: unset !important;
	bottom: unset !important;
	right: unset !important;
	padding: 0 !important;
	margin: 0 !important;
	visibility: visible !important;
	transform: unset !important;
	animation: unset !important;
}
html:only-child > head + body > div#app-mount.appMount__51fd7 > div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed::before {
	background: rgb(125,125,125) !important;
	opacity: 0.5 !important;
}
html:only-child > head + body > div#app-mount.appMount__51fd7 > div.typeWindows__421ed.titleBar__421ed > div.wordmark__421ed::after {
	background: var(--text-muted) !important;
	opacity: 1 !important;
}

html:only-child > head + body div.app_a3002d > div.app__160d8 > div.layers__960e4.layers__160d8 > div.layer__960e4.baseLayer__960e4 + div.layer__960e4 > div.standardSidebarView__23e6b > div.sidebarRegion__23e6b > div.sidebarRegionScroller__23e6b.thin_d125d2.scrollerBase_d125d2.fade_d125d2 > nav.sidebar__23e6b > div.side_b3f026 div.info__2debe {
	position: relative !important;
}
html:only-child > head + body div.app_a3002d > div.app__160d8 > div.layers__960e4.layers__160d8 > div.layer__960e4.baseLayer__960e4 + div.layer__960e4 > div.standardSidebarView__23e6b > div.sidebarRegion__23e6b > div.sidebarRegionScroller__23e6b.thin_d125d2.scrollerBase_d125d2.fade_d125d2 > nav.sidebar__23e6b > div.side_b3f026 div.info__2debe::after {
	content: "DiscordRecolor by" !important;
	font-size: 12px !important;
	color: var(--text-muted) !important;
	cursor: pointer !important;
	display: inline !important;
	opacity: 1 !important;
	padding: 0 !important;
	margin: 0 !important;
	cursor: text !important;
	visibility: visible !important;
	position: relative !important;
	top: unset !important;
	left: unset !important;
	bottom: unset !important;
	right: unset !important;
	transform: unset !important;
	animation: unset !important;
}
html:only-child > head + body div.app_a3002d > div.app__160d8 > div.layers__960e4.layers__160d8 > div.layer__960e4.baseLayer__960e4 + div.layer__960e4 > div.standardSidebarView__23e6b > div.sidebarRegion__23e6b > div.sidebarRegionScroller__23e6b.thin_d125d2.scrollerBase_d125d2.fade_d125d2 > nav.sidebar__23e6b > div.side_b3f026 div.info__2debe::before {
	content: "DevilBro" !important;
	font-size: 12px !important;
	font-weight: 600 !important;
	color: rgb(var(--accentcolor_v)) !important;
	display: inline !important;
	opacity: 1 !important;
	padding: 0 !important;
	margin: 0 !important;
	cursor: pointer !important;
	visibility: visible !important;
	position: absolute !important;
	top: unset !important;
	left: 108px !important;
	bottom: 8px !important;
	right: unset !important;
	transform: unset !important;
	animation: unset !important;
}
