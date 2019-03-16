FROM microsoft/dotnet:2.2-aspnetcore-runtime
RUN mkdir /data
COPY ./ /data
WORKDIR /data
EXPOSE 80
ENTRYPOINT ["dotnet", "dotnetMVCDemo.dll"]
