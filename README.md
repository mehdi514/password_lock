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
### test 
```elixir
mix test

```
I wrote the complete project article documentation in medium      
[GenServer/GenServer Testing](https://medium.com/@blackode/live-example-of-genserver-and-genserver-testing-ed55c8eb4f76#.k5m8kfiab)
