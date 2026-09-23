# Jastrisk Software Landing Website

Official modern landing page for **Jastrisk Software** (hosted at [jastrisksoftware.site](https://jastrisksoftware.site/)).

## About Jastrisk Software

Jastrisk Software is a software engineering studio based in Pyin Oo Lwin, specializing in custom enterprise software, scalable web & mobile applications, cloud DevOps, and UI/UX product design.

### Company Information
- **Location**: No.387, 4th Pyidawthar Ave., 5th Quarter, Pyin Oo Lwin
- **GPS Coordinates**: `22°01'11.5"N 96°28'05.2"E` (interactive Google Maps embed included)
- **Phone Lines**: `09252044554`, `09683444554` (`+95 9 252 044 554`, `+95 9 683 444 554`)
- **Email**: `aung.kk@jastrisksoftware.site`
- **Domain**: `jastrisksoftware.site`

## Project Structure

```
├── CNAME                  # Custom domain configuration (jastrisksoftware.site)
├── README.md              # Project documentation
├── index.html             # Main website landing page
└── assets/
    ├── css/
    │   └── style.css      # Modern dark-mode responsive design system
    ├── js/
    │   └── main.js        # Mobile navigation, inquiry handler, toast notifications
    └── images/
        ├── logo.png       # Official brand logo
        ├── logo.svg       # Scalable vector logo
        └── favicon.svg    # Vector favicon with J* mark
```

## Local Development & Preview

You can open `index.html` directly in any web browser, or serve it using Python's built-in HTTP server:

```bash
# Start a local preview server
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.
