```rust
struct AboutMe;

impl AboutMe {
    const READING_BOOK: &'static str = "Advanced Programming in the UNIX Environment";
    const CURRENT_JOB: &'static str = "Write crypto exchange matcher engine by Rust";
    const WANT_TO_UNDERSTAND: &'static str = "variance, covariant in Rust";
}

trait OpenSource {
    const CONTRIBUTOR_OF: &'static [&'static str] = &["sqlx", "bigdecimal-rs", "actix"];
}

impl OpenSource for AboutMe {}
```

![](https://github-readme-stats.vercel.app/api?username=pymongo&show_icons=true&icon_color=CE1D2D&text_color=718096&bg_color=ffffff&hide_title=true)

<!--
- [wakatime](https://wakatime.com/@rust)
-->
