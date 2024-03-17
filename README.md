# LWC-Multi-Org-Data-Communication-and-Sharing-Records

**I have engineered an organization-to-organization (org-to-org) integration framework facilitating seamless data exchange through REST API integration. This communication is orchestrated through the following components:**

**1. Integration Components:** These components feature Lightning Web Components (LWC) equipped with picklists to select object types (including both standard and custom objects), alongside buttons for object selection. Additionally, a multi-select picklist is provided to choose fields for display on object records.

**2. Parent-to-Child Communication:** Selected object records are displayed in another component through parent-to-child communication. Each record is accompanied by a checkbox, enabling users to select and transmit them to the designated organization.

**3. Child Component Functionality:** The child component showcases records along with checkboxes for selection. It incorporates a 'Select Org' button, empowering users to specify the target organization for record transmission. Furthermore, it offers functionality to display detailed information about the selected organization and facilitates the acquisition of a new ACCESS TOKEN via the 'Request Token' button, initiating an email to the organization owner for seamless communication.

**4. Record Transmission:** Upon selection of the target organization and activation of the 'Share Record' button, the chosen records are dispatched to the respective organization's users.

**5. Targeted Organization Operations:** In the recipient organization, the received records are inserted into the appropriate objects utilizing the **POST API** method.

This comprehensive integration solution ensures efficient and secure data transmission between organizations, enhancing collaboration and productivity."


**Demo**
![Sharing Org Recording](https://github.com/Shreyashurk/LWC-Advanced-AI-powered-Text-to-Image-Speech-Chat-Application/assets/145257222/4b322ffb-22b7-4ed3-89ab-10008784183a)
