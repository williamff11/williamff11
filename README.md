```elixir
defmodule About.Me do
  @moduledoc """
    A little bit about me.
  """

  @type t() :: %__MODULE__{
          dailyKnowledge: %{
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
          currentWorkplace: %{
            company: CrediSIS.t(),
            position: SoftwareEngineer.t()
          },
          passions: {
            elixir: Elixir.t(),
            aws: Aws.t(),
            tdd: Tdd.t(),
            scrumn: Scrum.t()
          }
        }
        
        schema "users" do
          ...
end
```