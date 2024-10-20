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


### c1=-5.0, c2=10.0, a=1, time average of a_{\pm}=-1.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/d4aafaa0-c9f8-40a8-89f5-7b752a014779)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/572516a4-46c9-45d4-9a11-338780efdef0)
---

### c1=-10.0, c2=5.0, a=1, time average of a_{\pm}=1.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/3bec2327-1c0d-449e-8d94-59abd1a83a6c)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/ec6b1330-262f-43d4-88e9-e59b132b2a0b)
---

### c1=5.0, c2=-5.0, a=1
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/c04a2413-3320-42a6-9118-e998c14a0475)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/6d6a694d-aa9c-4ef2-9823-a1fd395a2d44)
---

### c1=5.0, c2=-5.0, a=0.5, time average of a_{\pm}=0.417759.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/2596e615-ee90-4bab-a2dd-12e3d7314182)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/dc97924b-1102-4f35-8123-5959d9772885)
---

### c1=5.0, c2=-10.0, a=2, time average of a_{\pm}=0.822467.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/2c79da72-128a-407b-b22c-16a620cd9fa2)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/46e5ebd9-0711-4f82-b827-59e3d7670189)
---

### c1=5.0, c2=-10.0, a=1, time average of a_{\pm}=0.825859.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/e80a318e-cc04-41fb-9112-01b65401adbc)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/9abf55c5-e364-467b-87d4-a081414b1019)
---

### c1=5.0, c2=-12.0, a=1, time average of a_{\pm}=0.984861.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/90138b02-f471-4079-893d-15e9044bfb87)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/f0eef70e-8923-4308-9a0e-7e98da8615e5)
---

### c1=10.0, c2=-5.0, a=1, time average of a_{\pm}=0.008034.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/d1ca263d-87a1-4853-b4f2-df807be1cdb1)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/e3a66abd-c289-4da5-813e-980ec2115d56)
---

### c1=10.0, c2=-10.0, a=1, time average of a_{\pm}=0.417759.
#### Video
[Watch the simulation movie](https://github.com/user-attachments/assets/d2208935-2535-4655-b1de-935606309191)
#### Image
![Derivative plot](https://github.com/user-attachments/assets/95dc414b-1c37-4fa5-8dfd-65365e87b210)
---






