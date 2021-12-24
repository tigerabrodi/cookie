# Cookies

- Cookies are small strings of data that are stored directly in the browser.

- We can use `dokument.cookie` to get the cookies.

- We can write to a cookie, we need to set `name=value`

- If you have cookie name or values that contain spaces then you would have to use `encodeURIComponent` to encode them.

- `path:` Makes cookie accessible for pages under that path (starting with that path).

- `domain:` Defines where the cookie is accessible. Allows making cookies accessible on sub domains.

- `expires`, `max-age`: Cookies by default are gone when browsers close, these options are necessary to keep them on the site when the browser gets opened again.

- `secure:` cookie is only accessible on `https://`.

- `samesite:` used to protect from XSRF, cross-fire request forgery attacks. `strict` or `lax`. lax is more a relaxed.

- `httpOnly:` cookie is not visible when trying to be accessed via `document.cookie`.
