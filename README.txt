
. BUILD FOR PROD
~$ hugo server --disableFastRender
~$ hugo --minify

~$ cd public
~$ python3 -m http.server 8000

. DEPLOY STATIC SSG
~$ tar zcvf public.tgz public.tgz

Upload public.tgz and extract it inside "public_html/" on CPanel
