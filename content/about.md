+++
date = '2025-09-22T18:01:18+01:00'
title = 'About'
tags = ['personal']
+++
This is my about page. Here I present myself in broad terms. So let's start.

{{- if .Param "datesinlist" }}<time datetime="{{ .Date.Format "2006-01-02T15:04:05Z07:00" }}">{{ .Date.Format "2006 Jan 02" }}</time> &ndash; {{ end -}}