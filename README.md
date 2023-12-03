# iwmsillylanguage

A silly (:3) language for I Wanna Maker


## Install

Open the game's local files ( in Steam: on Library Game page, click the cog, Manage > Browse Local Files. )

Create a backup folder, cloning a locale/ folder into locale-old/

Download the `silly.mo` and put it inside locale/ folder, replacing:

| File | Language
|-|-
| `cn.mo` | Chinese
| `jp.mo` | Japanese
| `ko.mo` | Korean
| `pt_BR.mo` | Brazilian Portuguese
| `ru.mo` | Russian ( DOESN'T WORK; NOT LISTED )


## Uninstall

Just copy the previously modified file from locale-old/ and paste it in locale/ to overwrite the file.


## Changing the content.

You can use the fixed `iwm_localization_template.pot` to change or add strings to the locale.

( i use linux so i used the `msgfmt` command line thing, idk how bout windows )
