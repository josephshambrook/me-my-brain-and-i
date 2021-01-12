[![Netlify Status](https://api.netlify.com/api/v1/badges/bbf28a84-4bdb-407b-a2fa-32628d27fa3d/deploy-status)](https://app.netlify.com/sites/eleventy-netlify-boilerplate/deploys)

# Me, My Brain, and I

UK based blog about lived experience with epilepsy. Posts and wisdom by Louise Shambrook, developed and open-sourced by Joseph Shambrook.

Built on [Eleventy](https://www.11ty.io/) using the [Eleventy Netlify Boilerplate](https://github.com/danurbanowicz/eleventy-netlify-boilerplate), and deployed on Netlify.

## Local development

1. Clone the and install dependencies locally

```bash
git clone [url under that big green button above]
cd me-my-brain-and-i
npm i
```

2. Run the site

```
npx @11ty/eleventy
```

Or build automatically when a template changes:

```
npx @11ty/eleventy --watch
```

Or in debug mode:

```
DEBUG=* npx @11ty/eleventy
```

## Bug reports, feature requests, etc

This is an ongoing project and I welcome contributions and suggestions! Feel free to submit a PR.

If you need any help with setting up Netlify CMS, you can reach out to the Netlify team in the [Netlify CMS Gitter](https://gitter.im/netlify/netlifycms).
