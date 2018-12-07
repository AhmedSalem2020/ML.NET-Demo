Machine Learning for .NET
ML.NET is a cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers.

ML.NET allows .NET developers to develop their own models and infuse custom ML into their applications without prior expertise in developing or tuning machine learning models, all in .NET.

ML.NET was originally developed in Microsoft Research and evolved into a significant framework over the last decade and is used across many product groups in Microsoft like Windows, Bing, PowerPoint, Excel and more.

With this first preview release ML.NET enables ML tasks like classification (e.g. support text classification, sentiment analysis) and regression (e.g. price-prediction).

Along with these ML capabilities this first release of ML.NET also brings the first draft of .NET APIs for training models, using models for predictions, as well as the core components of this framework such as learning algorithms, transforms, and ML data structures.

Installation
ML.NET runs on Windows, Linux, and macOS - any platform where 64 bit .NET Core or later is available.

The current release is 0.5. Check out the release notes.

First ensure you have installed .NET Core 2.0 or later. ML.NET also works on the .NET Framework. Note that ML.NET currently must run in a 64 bit process.

Once you have an app, you can install the ML.NET NuGet package from the .NET Core CLI using:

dotnet add package Microsoft.ML
or from the NuGet package manager:

Install-Package Microsoft.ML
Or alternatively you can add the Microsoft.ML package from within Visual Studio's NuGet package manager or via Paket.


