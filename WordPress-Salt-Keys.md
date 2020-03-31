WordPress is the biggest platform for blogs and websites of all niche. It is a free open-source content management system(CMS) that you can install on your own web host to create a website. To secure your website, WordPress uses Slat Keys. Salt keys can be changed both manually or through a plugin. In cryptography, “Salt” is arbitrary data that is used to secure your login credentials. WordPress Salt Keys are random strings of data containing eight variables that encode your credentials. They are codes added to your password to further secure your WordPress login information. This makes your passwords immune to hacks.

Therefore, it is very important to update salt keys from time to time to reduce risk and every time the salt keys are changed, all user accounts will be logged out, including your own.

Your WordPress Salt Keys are stored in your wp-config.php file in the public_html folder of your WordPress site.

How to change Salt Keys Manually?

To change them manually, you need to use any FTP client tools (e.g. Filezilla, WinSCP, etc) and connect to your WordPress site. Connect to Public HTML, www, or the same as your website, then edit the wp-config.php file.
