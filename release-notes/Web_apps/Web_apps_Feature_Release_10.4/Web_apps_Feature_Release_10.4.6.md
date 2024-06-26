---
uid: Web_apps_Feature_Release_10.4.6
---

# DataMiner web apps Feature Release 10.4.6 – Preview

> [!IMPORTANT]
> We are still working on this release. Some release notes may still be modified or moved to a later release. Check back soon for updates!

> [!TIP]
> For release notes for this release that are not related to the web applications, see [General Feature Release 10.4.6](xref:General_Feature_Release_10.4.6).

## Highlights

*No highlights have been selected yet.*

## New features

*No new features have been added yet.*

## Changes

### Enhancements

#### Web apps: Improved startup performance because of waffle menu enhancements [ID_39208]

<!-- MR 10.3.0 [CU15] / 10.4.0 [CU3] - FR 10.4.6 -->

Because of a number of enhancements made to the waffle menu, overall performance has increased when opening a web app.

### Fixes

#### Dashboards app & Low-Code Apps - Template editor: Save button would not become available when you enabled a setting in an override [ID_39290]

<!-- MR 10.3.0 [CU15] / 10.4.0 [CU3] - FR 10.4.6 -->

When, after adding an override, you saved and re-opened the template editor, the *Save* button would not become available when you enabled one of the settings in the override. The *Save* button would incorrectly only become available after you had changed the value of the setting you enabled.

#### Dashboards app & Low-Code Apps - Template editor: Save button would incorrectly be available when opening the template editor [ID_39297]

<!-- MR 10.3.0 [CU15] / 10.4.0 [CU3] - FR 10.4.6 -->

When you made a change in the template editor, saved the template, and opened the editor again, up to now, the *Save* button would incorrectly be available. When you then closed the template editor without making any changes, a popup window would appear, saying that there were unsaved changes.

From now on, when you open the template editor, the *Save* button will be unavailable by default. Only after have made a change will this button become available.

#### Dashboards app - Time range component: Custom quick pick buttons would no longer be visible after you had refreshed the dashboard [ID_39298]

<!-- MR 10.3.0 [CU15] / 10.4.0 [CU3] - FR 10.4.6 -->

When a *Time range* component had custom quick pick buttons configured, up to now, those buttons would no longer be visible after you had refreshed the dashboard using the *Refresh* button in the dashboard subheader.

#### Dashboards app & Low-Code Apps - Node edge graph component: Data would incorrectly get fetched multiple times [ID_39299]

<!-- MR 10.3.0 [CU15] / 10.4.0 [CU3] - FR 10.4.6 -->

When a *Node edge graph* component contained multiple queries, including one that was linked to a feed, in some rare cases, the data would incorrectly get fetched multiple times.

Also, when a *Node edge graph* component was rendered for the first time, the edge arrows would incorrectly not appear.
