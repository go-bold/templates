# Go Bold Templates

Official project templates for [Go Bold Framework](https://github.com/go-bold/go-bold).

## Templates

### Default
Complete full application.
```bash
bold new myapp
```

## Template Variables

- `{{PROJECT_NAME}}` - Project name
- `{{MODULE_NAME}}` - Go module name
- `{{APP_NAME}}` - Display name
- `{{PACKAGE_NAME}}` - Package name

```bash
# Use custom repo
bold new myapp --repo=username/templates --template=custom
```

## Contributing

1. Fork repo
2. Create template in `templates/name/`
3. Test with `bold new test --repo=youruser/templates`
4. Submit PR

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
