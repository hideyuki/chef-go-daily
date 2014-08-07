# chef-go-dialy-cookbook

Infra for Go Dialy

## Environment
- chefdk: 0.2.0-2
- berkshelf: 3.1.3


## Supported Platforms

- ubuntu 14.04

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['chef-go-dialy']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### chef-go-dialy::default

Include `chef-go-dialy` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chef-go-dialy::default]"
  ]
}
```

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (i.e. `add-new-recipe`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request

## License and Authors

Author:: Hideyuki Takei (takehide22@gmail.com)
