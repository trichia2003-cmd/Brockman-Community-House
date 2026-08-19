# Staff PDF Management

This site uses Decap CMS so approved staff can manage PDFs without editing HTML.

## Hosting requirement

The site must be deployed through Netlify with the repository connected. Netlify Identity and Git Gateway provide the staff login and secure publishing workflow.

## One-time owner setup

1. Deploy this repository to Netlify.
2. In Netlify, open **Identity** and select **Enable Identity**.
3. Under **Identity > Registration**, choose **Invite only**.
4. Under **Identity > Services**, enable **Git Gateway**.
5. Under **Identity > Emails**, configure the site email settings if required.
6. Invite staff members from **Identity > Invite users**.

## Staff workflow

1. Visit `https://your-site.netlify.app/admin/`.
2. Sign in with the invited staff account.
3. Open **Community Documents**.
4. Upload a replacement PDF in the matching field.
5. Click **Publish**.

The public links on the home page read from `documents/documents.json`, so staff changes appear without editing `index.html`.

## Important

Do not make registration public. Only invited staff should receive accounts. Keep PDFs free of passwords or confidential information unless the organisation has approved their public publication.
