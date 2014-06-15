# Github Release and git tag

```
git tag -h
usage: git tag [-a|-s|-u <key-id>] [-f] [-m <msg>|-F <file>] <tagname> [<head>]
   or: git tag -d <tagname>...
   or: git tag -l [-n[<num>]] [--contains <commit>] [--points-at <object>]
		[<pattern>...]
   or: git tag -v <tagname>...

    -l, --list            list tag names
    -n[<n>]               print <n> lines of each tag message
    -d, --delete          delete tags
    -v, --verify          verify tags

Tag creation options
    -a, --annotate        annotated tag, needs a message
    -m, --message <message>
                          tag message
    -F, --file <file>     read message from file
    -s, --sign            annotated and GPG-signed tag
    --cleanup <mode>      how to strip spaces and #comments from message
    -u, --local-user <key-id>
                          use another key to sign the tag
    -f, --force           replace the tag if exists
    --column[=<style>]    show tag list in columns
    --sort <type>         sort tags

Tag listing options
    --contains <commit>   print only tags that contain the commit
    --points-at <object>  print only tags of the object
```

## Github Release

See [Releases · azu/github-release-annotation-example](https://github.com/azu/github-release-annotation-example/releases "Releases · azu/github-release-annotation-example")

```sh
git tag -a "annotation title" -m "release message body"
```

Summary

* `-a` is Release title
* `-m` is Release message body


Referrence

* [Git - Tagging](http://git-scm.com/book/en/Git-Basics-Tagging "Git - Tagging")
* [Git - タグ](http://git-scm.com/book/ja/Git-%E3%81%AE%E5%9F%BA%E6%9C%AC-%E3%82%BF%E3%82%B0 "Git - タグ")
