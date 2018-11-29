# daily-report-tool

The prototype of daily report tool, which is born for aggregating and reporting daily github commits.

## Config your env

You can configure env like this.

```ts
export let env = {
  email: {
    account: "your-email-address@gmail.com",
    password: "Your email password",
    to: "report-email-address@gmail.com"
  }
};
```

## Config your account

You can configure github account like this.

```ts
export let account = {
  username: "Your github username",
  password: 'Your github password'
};
```
## TODO:
- [ ] Add necessary types