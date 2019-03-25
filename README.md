# AngularCore
整合範本 Angular 7 + Angular Material 7.3.5 + .Net Core 2.1
方便快速入門<br>
因為使用指令 dotnet new angular 產生出來的範本專案是Angular 5 <br>
剛好最近學習了Angular 7 以及 Material 7.3.5 <br>
就將兩者與.Net Core 2.1 做了整合, 近期會再更新範例.... <br>

Combine Template Angular 7 + Angular Material 7.3.5 + .Net Core 2.1  <br>
Easy quick start  <br>
running dotnet new angular in a terminal/console window, Created is Angular 5.  <br>
Recently we are learning angular,  <br>
Put the latest version to do integration.  <br>

### Status

![travis](https://travis-ci.org/singer0503/AngularCore.svg?branch=master)


### Quick start 快速開始
>請檢查您的 Node 以及 npm 以及 dotnet Core 的版本, Node版本 > 10.5 , npm > 6.8 , dotnet core > 2.1<br>
Verify that you are running at least node 10.5.x and npm 6.8.x and dotnat core 2.1 by running node -v and npm -v and dotnet --version in a terminal/console window. Older versions produce errors, but newer versions are fine.

複製一份至本地端 git clone in your local 
 ```bash
git clone https://github.com/singer0503/AngularCore.git
 ```

執行套件還原 using dotnet cli restore package 
```bash
cd AngularCore
dotnet restore AngularCore.csproj
```

執行 start 
```bash
dotnet run
```

