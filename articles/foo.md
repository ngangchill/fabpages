    title: My Article Title
    slug: my-custom-slug
    tags: [tag, tag, tag]
    ---
    ## My Markdown Content

The `.md` file contains two sections separated by a `delimiter` string. One
section for the `metadata` and one for the `content`.

### Delimiter String

To separate `metadata` and `content` you MUST use a minimum of three `---`.
You can use more if you want.

### Metadata

Metada will be parsed as `Yaml` so feel free and creative because
you'll access them through an `array`. The only required key is the
`title`. `slug` and `tags` are optionnals. If you don't provide a custom
`slug`, one will be auto generated based on the `title` value...

### Content

Everything under `---` will be parsed as `Markdown`. Again, fell free and
creative.

## Extending and Customize Blogit

I try and will try my best to give you the ability to extend and override
`Blogit`. For now you can easily hack and extend `Jrean\Blogit\Blogit.php` and
`Jrean\Blogit\BlogitCollection.php` to bring your own logic, methods and
attributes.

### Be Creative

With the Blogit API you have access to methods and properties about your
content, metadata, commits, contributors, tags, dates, Github links,...
Have a look at `Jrean\Blogit\Document\*`, `Jrean\Blogit\Repository\*`
and `Jrean\Blogit\Blogit.php`.

## Contribute

This package is (yet) under active development and refactoring.
Please, feel free to comment, contribute and help. I would like/love to bring
`Unit tests`.

## Example

I will write soon a dedicated article for `Blogit` which is now used
on `Production` for [Askjong.com](http://www.askjong.com "AskJong, Quick Updates and Practical Approaches about anything Tech., Laravel, Vim, Php, DigitalOcean and Web Programming.")

## License

Blogit is licensed under [The MIT License (MIT)](LICENSE).

