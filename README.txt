using v1.18.4 and erlang 27; check with "asdf help"

elixir types:
list    []
atom    :name
tuple   {}
map     %{key: value}   
    usage: 
    iex> xy = %{a: "b"}
    iex> xy.a
    "b"

    matching:
    iex> %{a: myvar} = xy
    iex> myvar
    "b"

    update:
        a)
        iex> xy = Map.put(xy, :a, "c")

        b)
        iex> xy = %{ xy | a: "c" }

keyword list




creating a project:
> mix new cards

start elixir interactive shell in context of your project
> iex -S mix

using ex_doc:
> mix docs

running tests:
> mix test

