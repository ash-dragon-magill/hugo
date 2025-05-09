+++
title = '{{ replace .Name "-" " " | title }}'
date = {{ .Date }}
section = '{{ .Section }}'
tags = ['ecommerce']
color_scheme = 'terminal'
# layout = "simple"       # dont include this in the archetype, only use this for splash

[menu.main]
  name       = '{{ replace .Name "-" " " | title }}'
  identifier = '{{ .Section }}'
  url        = '/{{ .Section }}/'
  weight     = 30
+++
