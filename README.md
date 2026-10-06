# 📸 Picture of the Day

A simple website that showcases a new featured picture every day, sourced from the **Wikimedia Commons Picture of the Day**.

🌐 **Live Website:** [https://pingsabinbaral-ux.github.io/pictureoftheday/](https://pingsabinbaral-ux.github.io/pictureoftheday/)

---

## About

**Picture of the Day** displays the daily featured image from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Commons:Picture_of_the_day). The site updates itself automatically, so visitors always see a fresh picture without any manual work.

## How It Works

A scheduled **GitHub Actions** workflow (a cron job) runs every day, fetches the latest Wikimedia Commons Picture of the Day, and updates the site. The updated site is then published to the live website.

## Project Structure

```
pictureoftheday/
├── .github/
│   └── workflows/     # GitHub Actions cron job that updates the picture daily
├── public/            # Website files served to visitors
├── LICENSE            # CC0 1.0 Universal license
└── README.md
```

## Image Credits

All pictures come from [Wikimedia Commons](https://commons.wikimedia.org/). Individual images may carry their own licenses and attribution requirements, so please check the image's Commons page for details.

## Contributing

Contributions, suggestions, and ideas are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Author

Created by [@pingsabinbaral-ux](https://github.com/pingsabinbaral-ux)

## License

The code in this repository is released under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) (Creative Commons Zero), which dedicates it to the public domain. You can copy, modify, and distribute it, even for commercial purposes, without asking permission.
