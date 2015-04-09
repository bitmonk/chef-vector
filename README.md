# chef-vector-cookbook

TODO: Install Netflix's Vector tool: http://techblog.netflix.com/2015/04/introducing-vector-netflixs-on-host.html

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['chef-vector']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### chef-vector::default

Include `chef-vector` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chef-vector::default]"
  ]
}
```

## License and Authors

Author:: Justin Alan Ryan (<bitmonk@icloud.com>)
