# My Academic and Professional Profiles

<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">

<a href="https://scholar.google.com/citations?user=WCqPnS4AAAAJ&hl=en" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/Google_Scholar_logo.svg/2048px-Google_Scholar_logo.svg.png" alt="Google Scholar" style="width:50px;height:50px;">
</a>

<a href="https://www.researchgate.net/profile/M-Ahsan-Khodami" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/ResearchGate_icon_SVG.svg" alt="ResearchGate" style="width:50px;height:50px;">
</a>

<a href="https://github.com/Ahsankhodami" target="_blank">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" style="width:50px;height:50px;">
</a>

<a href="https://khodami.site" target="_blank">
  <img src="https://www.svgrepo.com/show/474749/broken-link.svg" alt="Website" style="width:50px;height:50px;">
</a>

</div>
<hr>


### Creating a Functional and Tested Demographics Form for JATOS Studies

When conducting online studies, collecting accurate demographic information is critical for analyzing participant data. This code provides a fully functional and tested solution for integrating a demographics form with the JATOS framework, ensuring smooth data storage and user redirection. 

#### **Functionality Overview**

The code captures participant details, including name, gender, age, handiness, and willingness to participate in future studies. Upon form submission, it saves the data directly to the JATOS server and redirects participants to the next stage of the study, specified as `next.html`. If you want to redirect participants to a different page, simply replace `next.html` with the desired URL in the `validateForm` function.

#### **Tested and Reliable**

This implementation has been tested with JATOS, guaranteeing proper data storage and redirection functionality. It ensures that participants' consent and form completion are validated before proceeding. The use of `jatos.submitResultData` and `jatos.endStudyAndRedirect` ensures seamless integration with JATOS workflows.

#### **Why This Approach is Important**

In online experiments, efficient data collection and participant navigation are essential for maintaining engagement and reducing drop-offs. By combining a user-friendly interface with backend reliability (via JATOS), this form simplifies the often-complex process of demographic data collection. Its clear design, error validation, and compatibility with the JATOS platform make it a robust choice for online studies.

#### **Key Points**
1. Tested and working with JATOS.
2. To customize the redirection, replace `next.html` with the desired page.
3. Enhances the online data collection process by validating and storing essential demographic data while guiding participants to the next step.

This code is not just a form—it's a streamlined gateway to more effective and organized online experimentation.

## Screenshots of the code

### Main page

![Main Style](misc/mainstyle.png)
### Policy text 
![policy](misc/policy.png)
### info 
![info](misc/info.png)