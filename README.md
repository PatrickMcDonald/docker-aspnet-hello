Hello World on ASP.NET Core in Docker
=====================================

To run from Docker Hub:

    docker run patrickmcdonald/dotnet-hello

To compile locally:

1. Clone the repository

        git clone https://github.com/PatrickMcDonald/docker-aspnet-hello.git

2. Build the docker container

        docker build -t aspnet-hello .

3. Run the created docker container

        docker run aspnet-hello
    
