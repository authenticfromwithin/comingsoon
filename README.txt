AFW — Coming Soon (minimal, add your own logo.png)

How to use:
1) Put your logo image in this folder and name it **logo.png** (transparent PNG, 1500–2500 px wide).
   - Tip: Aim for < 800 KB for fast load. Use tinypng.com to compress if needed.
2) Vercel → New Project → Upload this folder → Deploy.
3) Project Settings → Domains → Add both yourdomain.com and www.yourdomain.com
   • Set one as Primary → enable redirect on the other.
   • Detach the domain from any old/private project to avoid 404.
4) Squarespace DNS can remain: @ A 76.76.21.21, www CNAME cname.vercel-dns.com
5) Test: /any/path should still show this page (vercel.json handles it).
