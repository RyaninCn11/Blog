# RyaninCn11's Blog

Built with Hugo

Theme [Stack](https://github.com/CaiJimmy/hugo-theme-stack) designed by Jimmy, modified by RyaninCn11.

> Theme Stack (RyaninCn11 modified) in folder `themes/stack-modified` is NOT the original Theme Stack, you need to see [here](https://github.com/CaiJimmy/hugo-theme-stack) for the original one.

## Markdown alerts

The built-in alert types are `NOTE`, `TIP`, `IMPORTANT`, `WARNING`, and `CAUTION`:

```markdown
> [!NOTE] Optional title
>
> Alert content.
```

Custom types are configured in `config/_default/params.toml` under `article.alerts`:

```toml
[article.alerts.custom]
    color      = "#0ea5e9"
    background = "rgba(14, 165, 233, 0.08)"
    icon       = "assets/icon-custom.svg"
    title      = "自定义"
```

Place the matching SVG in the project `assets` directory. Icon paths may be written as `custom`, `icons/custom`, or an explicit path such as `assets/icons/custom.svg`. The `title` value is used when the Markdown alert does not provide its own title.

## License

[LICENSE](LICENSE)
