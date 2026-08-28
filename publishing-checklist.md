# Publishing Checklist

Use this checklist before pushing the portfolio or source snapshots to GitHub.

## Do Not Publish

- Real `.env` files
- Real `appsettings.json` secrets or database connection strings
- API keys, webhook secrets, JWT secrets, OAuth secrets
- Chrome user data, cookies, browser profiles, storage states
- Real Facebook group URLs, customer accounts, screenshots, HTML captures
- Real Excel workbooks with post text, customer names, orders, or phone numbers
- SQL dumps with business or customer data
- `node_modules`, `bin`, `obj`, `dist`, packaged runtime folders
- Large `.exe`, `.zip`, `.dll`, `.pdb`, generated installers
- Internal company documents that should not be public

## Safe To Publish

- Sanitized README files
- Architecture diagrams
- Synthetic demo data
- Example config files with fake values
- Source code after secret scan and business-name review
- Screenshots made from fake accounts or local demo state
- Migration notes that do not expose private database content

## Recommended GitHub Flow

1. Keep this portfolio repo as a documentation-first showcase.
2. Publish code-heavy projects separately only after sanitizing each source repo.
3. Pin the best 3-5 repositories on GitHub profile.
4. Use neutral repo names if original company names should not be public.
5. Add screenshots only after confirming they contain no internal data.

## Suggested Repo Names

- `arille-operations-automation-portfolio`
- `ibirdy-saas-commerce-api`
- `ibirdy-merchant-operations-console`
- `invoice-value-center-saas-console`
- `jj-auto-listing-publisher`
- `legacy-php-groupbuy-python-port`

## Final Manual Review

Before public release, search for:

```text
password
secret
token
apikey
api_key
connectionstring
localhost
facebook.com/groups
chrome user data
```

Also search for phone numbers, real customer names, internal hostnames, and real company account names.

