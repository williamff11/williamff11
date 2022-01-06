```elixir
defmodule AboutMe do
  @moduledoc """
    A little bit about me.
  """

  defstruct daily_knowledge: %{
    elixir: Elixir.t(),
    php: Php.t(),
    javascript: Javascript.t(),
    java: Java.t(),
    phoenix: Phoenix.t(),
    laravel: Laravel.t(),
    vuejs: VueJs.t(),
    angular: Angular.t(),
    springboot: Springboot.t(),
    aws: Aws.t(),
    postgressql: PostgresSql.t(),
    mysql: Mysql.t(),
    docker: Docker.t(),
    kubernetes: Kubernetes.t()
  },
  current_workplace: %{
    company: GenPag.t(),
    position: BackEndElixir.t()
  },
  passions: %{
    elixir: Elixir.t(),
    aws: Aws.t(),
    tdd: Tdd.t(),
    scrumn: Scrum.t()
  },
  contacts: %{
    email: "williamff11@gmail.com",
    linkedin: "www.linkedin.com/in/william-freire-121781143",
    twitter: "twitter.com/WilliamFreire6"
  }
end
```
