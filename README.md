# GitHub and Git Workshop
This is a website hosted on [GitHub Pages](https://pages.github.com) which serves as an accompaniment to the introductory workshop on [git](https://git-scm.com/) and [GitHub](https://github.com).

## Adding a Participant
To add yourself under the Participant list, first add your image in `img/participants` folder, then open the file `participants.yml` in `_data` folder and please maintain the following format *EXACTLY* (replacing values where indicated):

```yaml
- name: Participant's name
  github: Participant's Github username
  image: Participant's image
  twitter: Participant's Twitter id
  facebook: Participant's Facebook id
  Linkedin: Participant's Linkedin Page

  Geolocation (city or country: optional)
  lat: Participant's latitude
  lng: Participant's longitude
```
**IMPORTANT:**
- All images must be optimized before uploaded to the repository via commit or Pull Request. You may use any image optimizer of your choice.
- All images must be in `img/participants`.
- The images must be 240 x 240 pixels.
- If you do not want to include your social media accounts or coordinates, just skip that field.
- Avoid using contractions such as *can't, don't,* etc. If there is no choice (e.g. the name has single quote mark) put double quotes (`"`) around that part.

### :octocat:
