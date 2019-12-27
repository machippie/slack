
## Default Variables

### slack_started

Restart app if already running

#### Default value

```yaml
slack_started: true
```

### slack_user

User to run user-specific commands

#### Default value

```yaml
slack_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
