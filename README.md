## Schema API Client for Python

Build and scale ecommerce with Schema. Create a free account at https://schema.io

## Example

```python
import schema

client = new schema.client({
	'id': '<clientid>',
	'key': '<clientkey>'
})

result = client.get('/categories/shoes/products', {'color': 'blue'})

print result
```

## Documentation

See <http://schema.io/docs/clients#python> for more API docs and usage examples

## Contributing

Pull requests are welcome

## License

MIT
