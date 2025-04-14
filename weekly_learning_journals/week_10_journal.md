# CP3402 Weekly Journal

## Week 10

### Learning activities and Resources
- Watched LinkedIn learning videos about developing secure sites - [Developing Secure Sites](https://www.linkedin.com/learning/wordpress-developing-secure-sites/welcome?u=2223545)

### Estimated hours

Around 3 hours

### Content insights
#### How to make a WordPress site more secure
- Use hosting providers that offer features like SSL support, regular backups, firewalls, and malware scanning to ensure your site has maximum security.
- Outdated plugins can increase the likelihood of attacks on your site.
  - When installing plugins, make sure they are from trusted authors to avoid security breaches.
  - Check reviews and last update date to make sure the plugin is secure and up to date.
- Back up your site regularly to help combat data loss and possible attacks.
- I learned about using reCAPTCHA and 2FA to protect the login screen from bots and brute-force attacks.
- Disabling file editing in the WordPress admin by adding ``define('DISALLOW_FILE_EDIT', true);`` in ``wp-config.php`` increases server security.
  - Using ``.htaccess`` rules to block access to sensitive areas like ``/wp-includes/`` or ``/xmlrpc.php`` can also improve security.
- Use authentication keys in the ``wp-config.php`` file, which can be regenerated via the WordPress.org secret key generator. This will improve the security of the WordPress user login process.
- Monitor changes to your WordPress files by using a plugin such as ``Website File Changes Monitor`` to address any suspicious activity.

#### Additional security tips
- Monitor errors
- Respond to incidents
- Don’t modify core files
- Work with a clean computer
- Use HTTPS
- Use SFTP
- Write secure code
- Explore plugins

### Career/Employability/Learning Insights
#### Weekly Journals
At first, I didn’t think the weekly journals would be that useful.  
They felt like just another task to tick off for weekly practicals.  
But looking back now, the experience and the lessons I gained from it were invaluable.

Naturally, I like to write things down as it helps me remember things easier.  
Writing the weekly journals helped me keep track of what I was learning.  
It forced me to stop and think about what I did, what I struggled with, and what actually helped.  
These journals enabled me to focus on my weaknesses, not just in CMS but in my personal life as well.  
Specifically with the learning experiments I did in [week 5](week_05_journal.md) and [week 8](week_08_journal.md).  
I would not have done these if it was not for these journals.

I have learned that reflecting on myself is a great way to track progress,  
build confidence and learn from my mistakes, which will help me become a better person.  
Going forward, I have decided to start using a personal diary to reflect and track my personal life.

#### Learning Insights
I started with just basic knowledge of HTML and CSS,  
but now I’ve worked with PHP and full workflows using Git, CI/CD, WordPress theme development,  
local environments like LocalWP, and tools like Sass and Gulp to automate styling.  
At the start of the subject, I had little to no knowledge of PHP.  
In [week 5](week_05_journal.md) I mentioned that I was struggling with PHP and I needed more practice.  
But now, having used PHP in our [group project](https://github.com/cp3402-students/project-2025-tr1-jcua-team4/tree/main) and the work  
done in [practicals](https://github.com/heshan8/CP3402_practicals_2025),  
I'm now feeling more confident in writing PHP for theme development.  
Specifically, writing functions for custom themes.

I also learned things like using child themes properly, managing a site across staging and production,  
and writing cleaner code, which are important skills that employers in web development look for.  
I feel that now I can work on real projects without breaking things,  
and that I understand how to test, deploy, and maintain a site.  
I also learned how to reflect on myself and what works for me, like breaking tasks down,  
using short breaks, and figuring out how to stay productive.  
This is something  
I will take with me beyond uni, especially for my career in the future  
because time and energy management are just as important as knowing how to write code.

### Career/Employability Insights
Even when things did not work *(like when I could not get Gulp fully configured in [Week 9 Journal](week_09_journal.md))*,  
I still gained confidence by going through the process.  
Whether it's LocalWP or Git or CI/CD pipelines,  
I now know what these tools do, how they fit into a workflow, and I’m a lot more comfortable using them in future projects.  
Looking back, I have learned not just CMS and PHP, I’ve learned how to work through problems,  
overcome challenges, meet deadlines and stay focused on tasks.  
That’s what’s going to help me when I'm applying for jobs in the future.
