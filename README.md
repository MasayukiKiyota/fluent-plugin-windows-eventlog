# fluent-plugin-windows-eventlog 


## Overview
***Windows event log*** input plugin.  

this plugin is simple.  


## Configuration

```config
<source>
  type windowseventlog
  tag winevent.system
  eventsource  application or security or system)

  interval         [interval] (default: 300)
</source>

```

#### output data format

```
2013-02-24T13:40:00+09:00       winevent.system      {"Provider Name":"Windows","Level":3,"Computer":"winnserver1"}
```


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
