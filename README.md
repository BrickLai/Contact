
<h2>My contacts</h2>

<li>Introduction - the aim of the webpage</li>
<li>Technologies</li>
<li>Key Code</li>
<li>Launch</li>

<h3>Introduction - the project's aim</h3>
<p>
    This page aims to save contacts' information, including their names, cities and emails.  
</p>


<h3>Technologies</h3>
<li>HTML5</li>
<li>CSS3</li>
<li>Git</li>

<h3>key Code</h3>

```
  if(inputName.length === 0) {
        alert('Name is required');
    } else if (inputCity.length === 0) {
        alert('City is required');
    } else if (inputEmail.length === 0) {
        alert('Email is  required')
    } else if (!emailRegex.test(inputEmail)) {
        alert('A valid email is  required')
    } else {
      for(let i = 0; i < arr.length; i++) {
        contact.innerHTML = `Name:${arr[i - 2]}<br>City:${arr[i - 1]}<br>Email:${arr[i]}`;
        contacts.insertBefore(contact, contacts.children[0]);
       } 
    }
})
```

<h3>Launch</h3>
<p>This webpage is prepared to launch, users can click the link to preview it.</p>
<a href="https://bricklai.github.io/Contact/index.html">Click here</a> to view the contact webpage


