# `.github` repo for the **ukwebmarketing** org

This is the special **`.github`** repo for GitHub's `ukwebmarketing` org.

Anything you put in `profile/README.md` renders **on the public org page** at <https://github.com/ukwebmarketing>.

## How this got here

1. `ukwebmarketing` org created at <https://github.com/organizations/new>
2. New public repo on the org named **exactly** `.github`
3. This local repo (`~/clients/ukwebmarketing-org-profile/`) pushed up as the org's `.github` repo
4. GitHub auto-renders `profile/README.md` on the org's public page

## File layout

```
.github/
└── profile/
    └── README.md   ← the public org-page content
```

## Editing

Edit `profile/README.md`, commit, push. Cache propagates within minutes.

---

Repos under the org are private by default. This `.github` repo is the only public face.
