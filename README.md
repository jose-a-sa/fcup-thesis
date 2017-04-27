# FCUP thesis layout 

Latex version of the thesis layout available at [http://sigarra.up.pt/fcup](https://sigarra.up.pt/fcup/pt/web_base.gera_pagina?p_pagina=*admiss%c3%a3o%20a%20provas%20acad%c3%a9micas).
All rights go to Faculdade de Ciências da Universidade do Porto.

## Customizable parameters in `vars.tex` 

#### `\thesistype{arg1}` 

- **arg1:** [ `msc` | `phd` ] (default: `msc`)

This argument allows to change the layout between PhD (Doctor of Philosophy) and MSc (Master of Science)


#### `\spinewidth{arg1}` 

- **arg1:** _title of the thesis for the front page_ (default: 15mm, minimum: 8mm)

This allows to change the width of the spine of the book cover


#### `\fronttitle{arg1}` and `\spinetitle{arg1}` 

- **arg1:**  _title of the thesis for the front page/book spine_

This allows to change the titles used in the document


#### `\authorname[href]{arg1}` 

- **href:** _hyperlink used on the author field_ (optional)
- **arg1:** _name of the author_

Changes the author name. For the **href** can be used a website of a mail, using `mailto:mail@univ.edu` as hyperlink.
The **href** argument is optional, i.e. can be used `\authorname{arg1}` as well.

#### `\otheraffiliation[href]{arg1}{arg2}{agr3}` and `\extraaffiliation[href]{arg1}{arg2}{agr3}`

- **href:** _hyperlink used on the University2/University3 field_ (optional)
- **arg1:** _relative path to the logo of the University2/University3_
- **arg2:** _initials of the University2/University3_
- **arg3:** _fullname of the University2/University3_

Sets up the pages to incorporate fullname/logo/initials for the University2/University3 field.
The **href** argument is optional, i.e. can be used `\otheraffiliation{arg1}{arg2}{agr3}` as well.

#### `\degreename{arg1}` 

- **arg1:** _fullname of the degree_

#### `\degreename{arg1}` 

- **arg1:** _name of the scientific area of the thesis_

#### `\supervisor[href]{arg1}` and `\cosupervisor[href]{arg1}`

- **href:** _hyperlink used on the supervisor/cosupervisor field_ (optional)
- **arg1:** _name of the supervisor/cosupervisor_

Commenting the `\cosupervisor` field hides the field in the titlepage

#### `\supervisorposition{arg1}` and `\cosupervisorposition{agr1}`

- **arg1:** _position of the supervisor/cosupervisor_

This fields can be commented out separately.

#### `\supervisoraffiliation[href]{arg1}` and `\cosupervisoraffiliation[href]{arg1}`

- **href:** _hyperlink used on the supervisor/cosupervisor affiliation university_ (optional)
- **arg1:** _name of the supervisor/cosupervisor university_