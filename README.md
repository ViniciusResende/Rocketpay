<h1 align="center">
  <img alt="Elixir" src="https://elixir-lang.org/images/logo/logo.png" width="400px" />
</h1>
<p align= "center">:man_astronaut: An repository visioning the development of an API using Elixir that will create users and accounts to those users :man_astronaut:</p>

<h4 align="center"> 
	:construction:  Next Level Week 4 | Elixir Trail by Rocketseat  :rocket: | | In development  :construction:
</h4>

<p align="center">
  <a href="#desktop_computer-about-the-project">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-working-of-the-api">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-using-the-api">Lauching the app</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#man_technologist-used-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#raising_hand_man-developer">Developer</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#trophy-acknowledgment">Acknowledgment</a> 
</p>

</br>
</br>

## :desktop_computer: About the project:

:comet: Next Level Week 4 | Elixir Trial - Is a course that intend to develop an ability in the API development, in 5 videos you will learn how to develop an API that create users and assign account to its users, the users can deposit ou withdraw a certain quantitty of money and also tranfer money to another user.

:rocket: The project was developed with the purpose of being an greate oportunity to develop my skills and know more about API's.

:chart_with_upwards_trend: The project was an essential opportunity to develop skills with [Elixir](https://elixir-lang.org/), [Phoenix](https://phoenixframework.org/) and [Ecto](https://hexdocs.pm/ecto/Ecto.html).  

</br>

## :gear: Working of the API:

### Creating a User:
 <img alt="NLW4" src="https://res.cloudinary.com/viniciusalvesdefaria/image/upload/v1630880000/NLW4/Screenshot_from_2021-09-05_19-13-02_cvxshh.png">
 
### Depositing a Value:
 <img alt="NLW" src="https://res.cloudinary.com/viniciusalvesdefaria/image/upload/v1630879879/NLW4/Screenshot_from_2021-09-05_19-10-59_fdio3p.png">
 
 ### Withdrawing a Value:
 <img alt="NLW" src="https://res.cloudinary.com/viniciusalvesdefaria/image/upload/v1630879910/NLW4/Screenshot_from_2021-09-05_19-11-34_qe6bl3.png">
 
 ### Transfering money between users: 
 <img alt="NLW" src="https://res.cloudinary.com/viniciusalvesdefaria/image/upload/v1630879782/NLW4/Screenshot_from_2021-09-05_19-05-45_q9muh5.png">
 
</br>
</br>

## :rocket: Using the API:

The application only has a backend part:

:bulb: So, is required that you have some way to do HTTP requests.
:warning: To make requests to /api/accounts/* you will need to provide a Basic authorization header with username: 'banana' and password 'nanica123', you can change this on [config](./config/config.exs) file.

### Pre requirements
#### Before start, you should need have installed in your computer those following tools:
<img align="center" alt="GIT" height="25" width="35" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" style="max-width:100%;">  [Git](https://git-scm.com)</img>
</br>
<img align="center" alt="Elixir" height="25" width="35" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/elixir/elixir-original.svg" style="max-width:100%;"> [Elixir](https://elixir-lang.org/)</img>
</br>
<img align="center" alt="PostgresSQL" height="25" width="35" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" style="max-width:100%;"> [PostgresSQL](https://www.postgresql.org/)</img>

:warning: To run the project, you should have you local postgres set with default username and password 'postgres', you can also change this in the [dev](./config/dev.exs) file.

#### You will need a way to make HTTP requests, my recommendation is: 
<img align="center" alt="Insomnia" height="25" width="25" src="https://user-images.githubusercontent.com/38081852/87548811-6a05c580-c683-11ea-99ad-465f97fc0e60.png" style="max-width:100%;"> [Insomnia](https://support.insomnia.rest/)</img>
</br>


#### It is also recommended a good code editor, for example: 
<img align="center" alt="VisualStudioCode" height="25" width="35" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/visualstudio/visualstudio-plain.svg" style="max-width:100%;"> [VSCode](https://code.visualstudio.com/)</img>
</br>

### :gear: Starting the App:

 ```bash

 # Clone the Repository
 $ git clone https://github.com/ViniciusResende/Rocketpay.git
 
 # Enter the poject folder in the Terminal
 $ cd Rocketpay
 
 # Install all the dependencies
 $ mix deps.get
 
 # Create and migrate your database
 $ mix ecto.setup
 
 # Execute the appliction with this command
 $ mix phx.server
 
 # The server will start in the port:4000
 # So, you can access the API routes using http://localhost:4000/api/*route*
 
 
 ```
 
 ---
 
## :man_technologist: Used Technologies:

Those following tools were used in the project development:

### **API**  ([Elixir](https://elixir-lang.org/))

-   **[Phoenix](https://phoenixframework.org/)**
-   **[Ecto](https://hexdocs.pm/ecto/Ecto.html)**
-   **[Credo](https://hex.pm/packages/credo)**
-   **[bcrypt_elixir](https://hex.pm/packages/bcrypt_elixir)**
-   **[reflect-metadata](https://www.npmjs.com/package/reflect-metadata)**
-   **[excoveralls](https://github.com/parroty/excoveralls)**

</br>

## :raising_hand_man: Developer

<a href="https://github.com/ViniciusResende">
 	<img src="https://res.cloudinary.com/viniciusalvesdefaria/image/upload/v1613257612/foto_perfil_rounded_mv1cpi.png" width="100px;" alt=""/>
 <br />
 	<b>Vinícius Alves</b></a> <a href="https://github.com/ViniciusResende" title="Vinícius Alves"></a>
 <br />
 
 ## :trophy: Acknowledgment

<a href="https://rocketseat.com.br/">
 	<img src="https://pbs.twimg.com/profile_images/1291682473592659968/sEorc6oh.jpg" width="200px" alt="freeCodeCamp-logo"/>
 </a> 
 <br />
 	<p>Course ministered by: <a href="https://www.linkedin.com/in/rafaelcamarda/"><b>Rafael Camarda</b></a></p>
 <br />
