+++
title               = "{{ replace .File.ContentBaseName "-" " " | title }}"
layout              = "text"
original_title      = ""
authors             = []            # pole; u anonymních použij ["Neznámý"]
languages           = []            # původní jazyk (jen u překladů); např. ["latina"], ["řečtina"], ["němčina"]
original_date       = "{{ now.Format "2006" }}"   # datum vzniku originálu ve formátu EDTF
#   RRRR               "1620"            (jen rok)
#   RRRR-MM            "1789-08"         (měsíc a rok)
#   RRRR-MM-DD         "1620-11-08"      (přesné datum)
#   přibližné          "1200~"           (zobrazí se "cca 1200")
#   nejisté            "1200?"           (zobrazí se "snad 1200")
#   neznámé číslice    "19XX"            (zobrazí se "1900–1999")
#   rozpětí            "1940/1945"       (zobrazí se "1940–1945")
#   otevřené rozpětí   "../1945", "1940/.."   (zobrazí se "do 1945", "od 1940")
#   roční období       "2001-21"         (21=jaro, 22=léto, 23=podzim, 24=zima)
groups              = ["a"]         # právě jedna z hodnot v data/skupiny.toml ("a", "b", ...)
translator          = ""
source_name         = ""
source_url          = ""
source_citation     = ""
date                = {{ now.Format "2006-01-02" }}
lastmod             = {{ now.Format "2006-01-02" }}
period              = ""
tags                = []
note                = ""
summary             = ""

# [[corrections]]
#   date = "2026-01-01"
#   note = "Co bylo opraveno."
+++

Úvodní anotace textu.
