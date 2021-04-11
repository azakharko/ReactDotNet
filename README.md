This is the source code from the [tutorial on the ReactJS.NET site](https://reactjs.net/getting-started/tutorial.html).

To run this, follow the instruction:

```javascript
//checkout
git clone https://github.com/azakharko/ReactDotNet.git

cd src/

// restore 
dotnet restore

// build
dotnet build tutorial-code.csproj 

// publish
dotnet publish -c Release -o out tutorial-code.csproj

// run
dotnet out/tutorial-code.dll
```