# Unofficial MailerSend integration with Rails

### Setup

1. Add it to your Gemfile
2. Use the adapter:
```ruby
  ActionMailer::Base.delivery_method = :mailersend
```
3. `mailersend-ruby` gem requires `MAILERSEND_API_TOKEN` environment variable,
   so make sure it's set.

### Status

Experimental ActionMailer adapter. The last documented working state is July
2022. The project was documented as having no tests. Current Rails and
MailerSend compatibility and test coverage need verification. Verify compatibility before using it in production.
Contributions are welcome.
