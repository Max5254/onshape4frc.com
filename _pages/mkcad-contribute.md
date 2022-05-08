---
layout: page
title: Contribute To MKCad
comments: false
hidden: true
---

MKCad is an FRC COTS parts library run and maintained by the community. As such, it’s important to recognize that there may often be missing, misplaced, or mislabeled parts that the contributors haven’t gotten around to fixing or are unaware of. If you ever encounter an issue like this, or have any suggestions, we’d appreciate your feedback!

## Report Form

In the event that you encounter a mistake or a missing COTS part within MKCad, or have any suggestions, please fill out the `Report Form` below. Alternatively, you may leave a response in <a href='https://www.chiefdelphi.com/t/mkcad-2021-requests-and-updates/390651?u=jacktervay' target='_blank'>this thread</a> or contact one of us directly.

<a href="https://docs.google.com/forms/d/e/1FAIpQLSczAoCgL3ohHIl2EJZ8f5oukM8DuxikSeJilVhivM6_PXLfvw/viewform?usp=sf_link" class="btn btn-primary">MKCad Report Form</a>

## Want to become a contributor?

If you’d like to help keep MKCad up-to-date and become an active contributor, please fill out the form below.

<a class="mb-2 btn btn-primary" href="https://docs.google.com/forms/d/e/1FAIpQLSeUg7zRBHvhQUD0r5VbuFPFpGAC6dObvhsAVnXXayOVBM67GA/viewform?usp=sf_link" >MKCad Contributor Form</a>

# For Contributors

## How to Contribute

When contributing to MKCad, you have direct edit access to all of the production-level documents. Consequently, it’s important to follow best practices in an effort to avoid any potential headaches or annoyances for MKCad users. 
Below are some general guidelines that should be followed when contributing to MKCad, as well as a more in-depth example to demonstrate those guidelines in use and how to push changes to the public.

### General Guidelines

<h5 class="mb-2">Use the MKCad Trello Board to track what you’re doing.</h5>
This helps the team prioritize and document tasks and keeps us more organized in general. When completed, make sure to mark a task as “done”.

<h5 class="mb-2">Assign part properties.</h5>
- Material and/or an accurate overridden mass.
- Appropriate appearance(s).
- A part number in both the part studio’s and the solid body’s properties.

<h5 class="mb-2">Name the part studio and the parts.</h5>
Each separate COTS part should live in its own part studio. This makes it easier for users to identify parts quickly when accessing. If it’s a part that requires multiple bodies, make sure to use a composite part. This composite part will be the one that shows up in the app.


<h5 class="mb-2">Remain consistent across groups of similar parts.</h5>
When naming parts and assigning part properties, it's important to stay consistent. If there are already similar parts to what you’re adding in MKCad, refer to their names and properties to stay consistent.

<h5 class="mb-2">Generally, use <a target='_blank' rel="noopener noreferrer" href='https://www.onshape.com/en/resource-center/tech-tips/tech-tip-using-composite-parts'>composite parts</a> over assemblies.</h5>
Assemblies as a top-level part should only be used when there are flexible parts, or when it’s a convenience assembly of multiple COTS parts like UltraPlanetary or VersaPlanetary.

<h5 class="mb-2">Add a comment/commit message when creating a version covering what changed.</h5>
Adding a meaningful commit message helps everyone know what changed and when.

<h5 class="mb-2"><a target='_blank' rel="noopener noreferrer" href='https://docs.google.com/document/d/1-wasIVj0pzTFBKEsjuQRL-ST5nMl3vg11-taW8xnR9Q/edit?usp=sharing'>Update the MKCad app</a> after making a version.</h5>
If you added a new part, make sure that it’s visible (slider switch turned to blue).

### Example: Adding or editing a part within MKCad

For this example, we’ll be adding a 2” omni wheel from WCP to the `MKCad - Wheels` document. To do so:

1. **Identify the appropriate document for the part to reside in.**
2. **Navigate to the appropriate folder/location within the document and import the part’s CAD model.**
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/import_part.png" width="55%" />

3. **Rename the part studio’s name and the part’s name to the same name.**
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/rename_part.png" width="55%" />

4. **Add the vendor-provided part number in part properties.**
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/part_properties.png" width="55%" />
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/part_properties_2.png" width="55%" />

5. **Assign the vendor-provided weight.** To do so, click the scale icon in the bottom right and then select the part. Then, check `Override` and input the provided weight.
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/mass_override.png" width="55%" />

6. **If not already appropriate, edit the part’s appearance to resemble the real life product.**

7. **When your changes are finalized and ready to be made public, create a new version - this new version will prompt MKCad users to update their document and your newly made changes will then be seen by them.** Make sure to include a comment/commit message highlighting the changes that you’ve made for this new version.
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/create_version.png" width="55%" />
<img class="img-fluid lazyimg" src="assets/images/mkcad/mkcad-contribute/version_comment_and_commit.png" width="55%" />
