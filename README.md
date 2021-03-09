# scaffolder
Scaffolds projects using the .NET Core CLI. Requires Python 3.9+ and .NET Core CLI 3.1+.

## Installing and running
The easiest way to get the project is through [git](https://git-scm.com/)
```shell
git clone https://github.com/jonathan-lemos/scaffolder.git
```

To run the script:
```shell
python scaffolder.py [arguments?...]
```
By default, the script will scaffold a C# AWS Lambda project if the current directory is not empty.

To scaffold an F# AWS Lambda project:
```shell
python scaffolder.py --language F#
```

To scaffold a C# AWS Lambda SQS project:
```shell
python scaffolder.py --template lambda.SQS
```

To see all templates:
```shell
python scaffolder.py --list-templates
```

To see all options:
```shell
python scaffolder.py --help
```

To add the script to `$PATH` on OSX/Linux:
```shell
sudo cp scaffolder.py /usr/local/bin
```
