# Minion

Start with

`elixir -pa ebin --app minion --name minion --cookie minion --no-halt`


Start interactive with

`iex --name minion --cookie minion -S mix`


Execute shell commands on all Nodes:

`Cmd.all "ls"`