[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=11521212)
# Sphinx Profile Page

This is is a template for a resume/ personal portfolio, built with Sphinx! Based on [Chris Holdgraf's personal site](https://github.com/choldgraf/choldgraf.github.io)

This template is designed for use in the URI CS TD SSP. 


## Tips for Updating the Content of this site

- sidebar variables are defined in `info-.yml` 
- sidebar formatting for sidebar is in `_templates/hello.html` 
- variables are used via `html_context`
- get social links back by removing setting to `navbar_end` in `conf.py` and set values by [example](https://github.com/choldgraf/choldgraf.github.io/blob/main/conf.py#L41)


## To work with this repo offline (or in codespaces)

**This requires having python installed then installs a package that helps build the website**

The easiest way to build the website is to use `nox`, which handles all of the environment generation automatically.
To do so, follow these steps:

1. Install `nox`.

   ```shell
   pip install -U nox
   ```
2. To run a live webserver that will auto-build and reload when you make changes, run:

```shell
nox -s docs-live
```

If on Codespaces, use accept the port forwarding and open the forwarded port in a new browser tab to preview your site while you work. 

<!-- 
Run `nox`

   ```shell
   nox -s docs
   ```

this should install a Sphinx environment and build the site, putting the output files in `_build/html`. -->

# Profile Website

Welcome to my profile webiste, Professors and peers
<!-- enter your target audience after the comma above -->

Since you're here, you might be: 
- Comiado man: Comiado man is a student at URI who is struggling with his coding homework. He knows I am done with it and would like some help with it. Therefore, he wants to visit my site to get my contact information.
- Senior Gusto: He is the manager at Gusto Incorporated and he wants to know what work I have done in the past to help him make his decision to hire me or not.
- Mungdall: Mungdall is a TD alumni who also went for computer science. He wants to see what the future generation is up to as his computer science career failed and he is now a world class chef.
<!-- make a bulleted list of 3 fictional visitors to your site. Include a few detials about them that could impact how you design for them. For each visitor, assign a task or goal they have for visiting your profile website -->

## Design

I will optimize the message I'm trying to send through my website by making the design clean and organized. By using headers, sub-headers, links to diffrent parts of the site will make it easier for the reader to naviagate.

## Accessibility

My site will be accessible in these ways.
- Images with Alt text
- Accessibility options like font sizing
- Be conscious of color and contrast
I can use an online website accessibility checker to test if my site is in good standing or needs some changes.
