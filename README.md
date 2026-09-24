Introducing Omni TV – A Repository-Free, URL-Based Streaming Architecture
​Hi everyone,
​As many of you know, platforms like Cloudstream and Stremio are great tools. However, they heavily rely on third-party extensions and repositories. When maintainers abandon those extensions or repositories go down, the applications become virtually unusable until a new fix is released.
​To solve this dependency issue, I started developing Omni TV.
​The core concept behind Omni TV is to eliminate the need for any internal extensions or third-party repositories. Instead, it operates on a dynamic URL-based architecture.
​How it works:
​Instead of relying on fixed repos, users will simply paste the URL of any media source or streaming site directly into the app.
​No central repository risks: Even if popular repos go offline, your app remains functional because you can seamlessly switch to another URL.
​Full control: You can add, test, or remove any site URL with a single click.
​Current Project Status:
​UI & Core Architecture: Fully built and functional. The entire application structure, navigation, and user interface are complete (developed on a mobile device using AI assistance).
​Missing Feature (Work in Progress): The app currently lacks the media URL extraction / scraping engine. It cannot parse or pull video sources/streams directly from the entered site URLs yet. Omni-Tv