# DiviX-Public

:warning: *The source code of DiviX project is private, this repository is a public and simple documentation used for my resume*

## Supervisors

**Jose Pablo Baraybar Do Carmo** : Conceiver of the project, Ph.D., anthropologist at the International Committee of the Red Cross (ICRC) - Paris Regional Delegation, Forensic Department - [Contact : jpbaraybar@icrc.org](mailto:jpbaraybar@icrc.org)

**Pierre François** : Student supervisor, Ph.D., researcher and professor at INSA Lyon - [Contact : pierre.francois@insa-lyon.fr](mailto:pierre.francois@insa-lyon.fr)

## Presentation

DiviX project is a set of tools used for victims identification in war, migration and distaster zones accros the world.
Initiated at INSA Lyon in collaboration with the International Committee of the Red Cross (based in Geneva), the DiviX project is composed of :

- **Dividoc (Disaster Victim Documentation)** : An Android app (XML and Java) designed to assist with the documentation of dead bodies
in the field. The application produces a password-secured archive containing basic
information collected by the first responder, namely a set of pictures of the body associated
with its geolocation, as well as a unique identification tag allowing correlation with the
information registered during the burial/disposal process.

- **Divimap (Disaster Victim Mapping)** : An Android app (XML and Java) which records the case number prior to disposal and, like Dividoc, also produces geolocation and
a password-secured archive of the pictures taken. The ultimate goal of the operation is to
assist with victim traceability from discovery to disposal.

- **DiviX-Server** : A web server (NodeJS, VueJS, MySQL, Docker) that collects the data gathered by the Android applications and allows to filter and sort cases (victims) by age, sex, date or location, displays the cases location on a map (OpenStreetMap) and automatically extracts password-protected archives and populate the database. This sub-project is no longer maintened and was never deployed due to potential security issues that were not examined.

<p align="center">
<i>Screenshots of Dividoc, from left to right : Main menu, victim identification form and photo gallery view</i>
</p>
<p align="center">
  <img src="/images/main_menu.png" width="200" />
  <img src="/images/tag_form.png" width="200" /> 
  <img src="/images/photo_gallery_view.png" width="200" />
</p>

## Personal contribution

Dividoc and Divimap were started by 7 students in third-year university (from the upper promotion, in 2020) and many of the specifications were respected. The year after, my professor asked me to continue the project with 6 other students of my choice. During 3 months, I worked with other as the group leader, focusing on :
- Correcting existings bugs
- Adding new features
- Creating the web server

At the end of this, we had a solid project but not good enough to go to a production.
Six months later (march 2022), I decided to do, alone and on my free time, a complete refactoring of the Android apps. Then I focused on :
- Totally rethinking and re-implementing the programming logic of applications
- Remodeling and implementing the UI, based on Material Design and the basic principles of the UI field
- Suppressing warnings and deprecated functions
- Commenting the code and correcting bugs

## Timeline

*End of July 2022 :* First tests in the field using Dividoc in Afghanistan (heroin overdoses due to poverty)
