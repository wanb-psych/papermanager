
# Zotero managing
- This is the automatically sync between zotero desk-app and papership/zotero ios-app using a severless way

1. Using WebDav to save zotero files cloudly (for me, I am using 'Koofr')
2. Before that, create WebDav app password (the third party will use this password) in Koofr settings/preference
3. Because papership can sync when recognizing the file 'lastsync.txt' is a new one even blank (have to create every time manually)
4. So this *.yml run can automatically create this file in our cloud working directory for zotero. (In the script, GMT+0, 4 and 16 are the updating time)
5. After submitting the *.yml script, don't forget to create the DAVEMAIL (usually your login email) and DAVPASS the corresponding values in settings <- secrets
6. The DAVEMAIL and DAVPASS are not only used in Zotero desk-app but also in papership ios-app.
