## Installation

```sh
pip install -e .

```

## Set Token

Login using Credentials

```sh
datacamp login -u [USERNAME] -p [PASSWORD]
```

```sh
datacamp set-token [TOKEN]
```

## List Courses

```sh
datacamp courses --refresh
```

## Download Options

All Courses

```sh
datacamp download --no-videos --subtitles none all
```

Specific Courses

```sh
datacamp download --no-videos --subtitles none <IDs separated by Space>
```
