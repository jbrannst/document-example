# examples
Just an example of how to generate example data in order to understand how a certain model can influence for example performance.


To use the template to populate an Atlas instance you'd run something like
```
mgeneratejs template.json -n 100000 | mongoimport mongodb+srv://cluster1.em4dc.mongodb.net --username test --password H4rdT°Gue55Pwd -d example -c shipments --drop 
```

see also [mgeneratejs|https://github.com/rueckstiess/mgeneratejs] and [atlas|https://www.mongodb.com/cloud/atlas] 
