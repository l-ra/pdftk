# pdftk

Just run it ...

```
$ docker run -rm lra73/pdftk 
SYNOPSIS
       pdftk <input PDF files | - | PROMPT>
	    [ input_pw <input PDF owner passwords | PROMPT> ]
	    [ <operation> <operation arguments> ]
	    [ output <output filename | - | PROMPT> ]
	    [ encrypt_40bit | encrypt_128bit ]
	    [ allow <permissions> ]
	    [ owner_pw <owner password | PROMPT> ]
	    [ user_pw <user password | PROMPT> ]
	    [ flatten ] [ need_appearances ]
	    [ compress | uncompress ]
	    [ keep_first_id | keep_final_id ] [ drop_xfa ] [ drop_xmp ]
	    [ verbose ] [ dont_ask | do_ask ]
       Where:
	    <operation> may be empty, or:
	    [ cat | shuffle | burst | rotate |
	      generate_fdf | fill_form |
	      background | multibackground |
	      stamp | multistamp |
	      dump_data | dump_data_utf8 |
	      dump_data_fields | dump_data_fields_utf8 |
	      dump_data_annots |
	      update_info | update_info_utf8 |
	      attach_files | unpack_files ]

       For Complete Help: pdftk --help
```