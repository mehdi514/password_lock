# PasswordLock
## Usage 
```elixir
{:ok,pid } -> PasswordLock.start_link("mypass")
```
### Unlock
```elixir
PasswordLock.unlock pid,"your_pass"
```
### reset 
```elixir
PasswordLock.reset pid,{"oldpassword","newpassword"}

```

