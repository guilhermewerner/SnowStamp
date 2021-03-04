# ❄️ Snow-Stamp

I couldn't find a page anywhere that let you just paste in a Discord snowflake to get the timestamp.

So I made one.

❄️ https://pixelatomy.com/snow-stamp/

## Contribute

Pull requests and issues are welcome!

## Develop

`npm install && npm run dev`

### Epoch

You can use a custom epoch instead of [Discord's](https://discord.com/developers/docs/reference#snowflakes) by setting environment variable `SNOWFLAKE_EPOCH` to the desired number. You can create a `.env` file in root to set this variable.

## Deploy

`npm run build && npm start`

---

_Made with svelte_
