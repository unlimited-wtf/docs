---
description: Welcome to the Jobs-Management!
---

# 🗃 Jobs

To create a job in FiveM it is normally neccessary to have root-access and some development knowledge. You always need to restart your job-script after you edited the config files.

This belongs belongs to the past from now on!

With **Spectre** you gain the ability to manage your jobs like never before and in the most easiest way. Editing a job will also be synchronized LIVE with your gameserver! You don't need to restart any job-connected script anymore!

## How to manage Jobs

Navigate to the Development - Jobs section. You get a list of all jobs from your Shared/Jobs.lua file in `qb-core`. You will get access to a list of all your active jobs, showing several usefull information like the amount of grades and the job-label. All information are editable.&#x20;

{% hint style="info" %}
Dynamicly registered jobs from any other script (e.g. job-creators) wont get displayed!
{% endhint %}

<figure><img src="../.gitbook/assets/jobs.PNG" alt=""><figcaption><p>Job List (Sample)</p></figcaption></figure>

## Adding/Edit Jobs

To manage or add an specific job, click on "Create Job" or choose an existing job from the list to get access on the job settings.&#x20;

<figure><img src="../.gitbook/assets/createuser.PNG" alt=""><figcaption><p>Job options (Sample)</p></figcaption></figure>

| Configurable Information             | Configurable Functions                              |
| ------------------------------------ | --------------------------------------------------- |
| <ul><li>name</li><li>label</li></ul> | <ul><li>default duty</li><li>off duty pay</li></ul> |

## Custom Variables

We also provide the option to create custom variables. Supported datatypes are `String`, `Number` and `Boolean`. Spectre checks for duplicated keys and wont allow them. [Default keys](jobs.md#adding-edit-jobs) are also protected.

<figure><img src="../.gitbook/assets/job_custom_vars.PNG" alt=""><figcaption><p>Job custom variables (Sample)</p></figcaption></figure>

## Grades

Add/Delete job grades. With the left drag handle you can reorder your grades fast and effortless. Each job needs at least one grade.

By clicking the "Boss"-button you set the boss rank to a grade. This status is limited to one grade only.&#x20;

<figure><img src="../.gitbook/assets/job_grades.PNG" alt=""><figcaption><p>Job grades (Sample)</p></figcaption></figure>

## Delete a Job

If you want to delete a specific job, just search for it an select it. You will find a "DELETE"-button in the right buttom corner. This options requires the `Job:Edit` permission.\
\
After you clicked it, you need to confirm the removal. The job will be removed live from your Gameserver!\
\
**Beware:** Since you do the changes live on your server, deleting a job might can cause some troubles. If you delete a stash or garage you might delete items or avoid access to cars.

<figure><img src="../.gitbook/assets/delete.PNG" alt=""><figcaption><p>Delete a job</p></figcaption></figure>
