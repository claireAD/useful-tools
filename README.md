## Git release Notes

install git-release-notes

```$ ./bin/install```

generate releases notes

```$ cd mon-projet```

```$ git-release-notes <tag_v1>..<tag_v2> ../ADTools/git-release-notes/ad_markdown.ejs > changelog.markdown```

## Abandoned strings

Launch this command in this current directory and indicate the path to your iOS workspace

```$ ./AbandonedStrings /Users/your-username/path/to/source/code```

## Generate wording file from an iOS .strings or an Android XML file

Copy wording file (.strings or .xml) in the current directory and launch the appropriate command
Output file will be in directory `wording_ios` or `wording_android`

```$ ./bin/generate_wording_ios```

```$ ./bin/generate_wording_android```

## Update wording

Install gem `ADLocalize`

Copy-paste `update_wording` in your iOS project directory, then open it

Set $DRIVE_WORDING_FILE_KEY, $PROJECT_NAME, $TARGET_NAME

To execute script

```$ ./update_wording```
