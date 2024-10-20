# PERISTOCH

Simulation results of the PDE model.

We check &eta; dependency for the periodic behavior below.

## &eta; dependency

## Video
[Simulation movie 1](https://github.com/Hiro06190/PERISTOCH/assets/40862678/92f34e80-03e5-4d86-8d3e-c3d5ca80b48b)


### PDF Document
[Elec-M Phase Portrait](slow_fast_ep0.01_eta100.pdf)

### Descriptions
- **Video**: simulation movie with &epsilon;=0.01, &eta;=0.01.
- **PDF**: Elec-M phase portrait.

## Video
[Simulation movie 2](https://github.com/Hiro06190/PERISTOCH/assets/40862678/d2976c9d-f213-48ef-9b67-75ece7d73795)


### PDF Document
[Elec-M Phase Portrait](slow_fast_ep0.01_eta10.pdf)

### Descriptions
- **Video**: simulation movie with &epsilon;=0.01, &eta;=0.1.
- **PDF**: Elec-M phase portrait.

## Video
[Simulation movie 3](https://github.com/Hiro06190/PERISTOCH/assets/40862678/51490627-9cd2-44e3-b23f-a47f848dede7)


### PDF Document
[Elec-M Phase Portrait](slow_fast_ep0.01_eta1.pdf)

### Descriptions
- **Video**: simulation movie with &epsilon;=0.01, &eta;=1.
- **PDF**: Elec-M phase portrait.

## Some initial conditions

We simulate the PDE model with different initial conditions to show profile contractions. The first movie is for &epsilon;=0.02. The second movie is for &epsilon;=0.1.

## Video
[Simulation movie 4](https://github.com/Hiro06190/PERISTOCH/assets/40862678/47afa198-25f6-4300-80a0-a03226de2fb9)

### Descriptions
- **Video**: simulation movie with &epsilon;=0.02. x-axis is system size L=10, y-axis is u.

## Video
[Simulation movie 4](https://github.com/Hiro06190/PERISTOCH/assets/40862678/7f1b796e-ed89-48c2-866c-306ad33df234
)

### Descriptions
- **Video**: simulation movie with &epsilon;=0.1. x-axis is system size L=10, y-axis is u.


## Other simulations

We simulate the PDE model with the initial condition including two shocks.

Also, we simulate the PDE model with shifted initial conditions that take different points from L/2.


## Video
[Simulation movie 5](https://github.com/Hiro06190/PERISTOCH/assets/40862678/50eca45f-f7ae-43ca-b75d-bff9dfe219db
)

[Simulation movie 6](https://github.com/Hiro06190/PERISTOCH/assets/40862678/bdfa4a16-c072-4f13-a1b9-e713d24e85ce
)

### Descriptions
- **Video**: simulation movie with piece wise linear initial conditions and &epsilon;=0.02.


## Video
[Simulation movie 7](https://github.com/Hiro06190/PERISTOCH/assets/40862678/2d2da78c-55a3-44b4-9fcc-5d01b92f6885
)

[Simulation movie 8](https://github.com/Hiro06190/PERISTOCH/assets/40862678/a5449fe2-4c75-4fa4-91df-74b9fd029438
)

### Descriptions
- **Video**: simulation movie with piece wise linear initial conditions and &epsilon;=0.02. The initial profiles are shifted from x=L/2.

## Periodic flux, (sin(kt)+c&epsilon;)(1-n)n
Simulation results of the PDE model with periodic flux.

The following function gives the initial condition used in all simulations:  
**(tanh(x - L / 2) + 1) * 0.5**, where L is the system size.

We explore the behavior of the profile and its midpoint of the derivative under different values of the parameter `c`.
The flux is given by (sin(kt)+c&epsilon;)(1-n)n.
Here, &epsilon;=0.1 and k =10

### c=0
#### Video
[Watch the simulation movie for c=0](https://github.com/Hiro06190/PERISTOCH/blob/main/animation_u_a_t_flux_c%3D0.mp4)

#### Image
![Derivative plot for c=0](https://github.com/Hiro06190/PERISTOCH/blob/main/derivative_plot_c%3D0.jpg)

### c=1
#### Video
[Watch the simulation movie for c=1](https://github.com/Hiro06190/PERISTOCH/blob/main/animation_u_a_t_flux_c%3D1.mp4)

#### Image
![Derivative plot for c=1](https://github.com/Hiro06190/PERISTOCH/blob/main/derivative_plot_c%3D1.jpg)

### c=2
#### Video
[Watch the simulation movie for c=2](https://github.com/Hiro06190/PERISTOCH/blob/main/animation_u_a_t_flux_c%3D2.mp4)

#### Image
![Derivative plot for c=2](https://github.com/Hiro06190/PERISTOCH/blob/main/derivative_plot_c%3D2.jpg)

### c=5
#### Video
[Watch the simulation movie for c=5](https://github.com/Hiro06190/PERISTOCH/blob/main/animation_u_a_t_flux_c%3D5.mp4)

#### Image
![Derivative plot for c=5](https://github.com/Hiro06190/PERISTOCH/blob/main/derivative_plot_c%3D5.jpg)


## Coupled model, a_{±}(M)(1-n)n
Simulation results for the coupled model.
Here,
a_{±}(M) = sign(M) =
    a   if M > 0
    -a  if M <= 0

The following function gives the initial condition used in all simulations:  
**(tanh(x - L / 2) + 1) * 0.5**, where L is the system size.

We explore the profile's behavior and derivative midpoint under different parameters c1 and c2 values.


### c1=5, c2=-5, a=1
#### Video
[Watch the simulation movie (c1=5, c2=-5, a=1)](https://private-user-images.githubusercontent.com/40862678/378142856-af9d4001-47d9-41aa-b46b-cf16f71bb142.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjkzOTMzMzgsIm5iZiI6MTcyOTM5MzAzOCwicGF0aCI6Ii80MDg2MjY3OC8zNzgxNDI4NTYtYWY5ZDQwMDEtNDdkOS00MWFhLWI0NmItY2YxNmY3MWJiMTQyLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEwMjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMDIwVDAyNTcxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTZmZWYwYjkxNmY4MDRlOTlmZjJhYTY0OGI4YmRjYWE0MjQzNGYyYmY4NGViNGZkODE5MDE5MGI1ZDRmOTI4OTQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.eFWCdP7KXKOPi0YvpkYBmOVmuDhEuJrl2RIMUdHRLVo)

#### Image
![Derivative plot for c1=5, c2=-5, a=1](https://private-user-images.githubusercontent.com/40862678/378142868-45e61d22-fc88-48d1-a25c-82d559ca8ec5.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjk0MjQ0NjEsIm5iZiI6MTcyOTQyNDE2MSwicGF0aCI6Ii80MDg2MjY3OC8zNzgxNDI4NjgtNDVlNjFkMjItZmM4OC00OGQxLWEyNWMtODJkNTU5Y2E4ZWM1LmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEwMjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMDIwVDExMzYwMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWY1MzIwNjEzYjZmNmQ1NTA5NjIxZjk1NmU2ODlhMWEzMzY5NmRjMDVkZDM1MzRmOWZmNTYxYmIxNTlhNTg3ZDYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.5fuiNHz8ftV7FdCOheprYe8RYjMmW8X9rLgNB2cmQbA)




