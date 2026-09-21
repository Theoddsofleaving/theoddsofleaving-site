WEBSITE UPDATE FILES — TWO CHANNELS
====================================

Upload the  updates  folder so it lands at  public_html/updates/

    public_html/updates/versions.json        official channel
    public_html/updates/beta/versions.json   beta channel
    public_html/updates/builds/*.html        the builds both point at

IMPORTANT — REPLACE LAST TIME'S versions.json
  The file from the previous update listed 0.0.9 and 0.0.8 in the
  main versions.json. If you uploaded it, the official channel is
  currently offering beta builds to everyone. This set moves them to
  beta/versions.json. Replace it.

RELEASING
  Official release  -> add to the TOP of updates/versions.json
  Beta build        -> add to the TOP of updates/beta/versions.json
  Upload the .html to updates/builds/ first.

  Use a NEW id every time (0.0.9a, 0.1.0). The launcher only offers
  ids it does not already have — 0.0.8 and 0.0.9 are already inside
  the beta launcher, so re-uploading under those ids reaches nobody.
