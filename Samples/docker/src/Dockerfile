FROM microsoft/dotnet

COPY ./NetCoreSample /src

RUN cd /src && dotnet restore

EXPOSE 5000

WORKDIR /src
CMD ["dotnet", "run"]
