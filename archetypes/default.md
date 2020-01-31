+++
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
draft = true
author = "Uriah Galang"
tags = []
categories = []
description = "Add Your Post Descrition"
image = "images/blog/{{ replace .Name "-" " " | urlize }}.jpg"
og_type = "article"
slug = "{{ replace .Name "-" " " | urlize }}"
+++
