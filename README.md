defmodule Lolo.About do
  @moduledoc """
  A module to represent Lolo's professional profile in Elixir.
  """

  def specialization, do: "Fullstack Development & AI Exploration"

  def core_skills, do: [
    "Elixir",
    "JavaScript",
    "TypeScript",
    "React",
    "Nodejs",
    "HTML",
    "CSS",
    "Docker",
    "GIT",
    "SQL",
    "NoSQL"
  ]
end

defmodule Lolo.Profile do
  use Ash.Resource, 
    data_layer: Ash.DataLayer.Ets,
    domain: Lolo.Domain

  attributes do
    attribute :intro, :string
    attribute :current_focus, :string
    attribute :technical_projects, {:array, :string}
  end

  def intro, do: "I’m Lolo and I'm on the fullstack journey, currently, deep-diving in Elixir ♥"
  def current_focus, do: "Now exploring LiveView, and the world of AI."
  def technical_projects, do: [
    "Elixir Projects",
    "JavaScript Applications",
    "TypeScript Implementations",
    "React Frontends",
    "Nodejs Services",
    "HTML & CSS Designs",
    "Dockerized Environments",
    "Version Control with GIT",
    "SQL & NoSQL Databases"
  ]
end

