# dtc-potw-docker-1

Data Talk Club DIY activity on a proposed topic

The proposed topic of this week (18 oct - 25 oct 2023) is learning about Docker - part 1. This is a Do It Yourself learning activity, whose daily plan can be found [here](https://github.com/DataTalksClub/project-of-the-week/blob/main/2023-10-18-docker-1.md).

Plan of Day 1

1. Check the first 20 mins of [Nana’s Docker tutorial](https://www.youtube.com/watch?v=pg19Z8LL06w):
2. Install Docker Desktop from [https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)
3. Suggestion: Run `docker start` in your terminal. Note: The requirements for running this command successfully differentiate on each OS.
4. Read the Introduction of Docker Documentation: [https://docker-curriculum.com/](https://docker-curriculum.com/)
5. Create a GitHub repository.


My takeaways from day 1

benefits in development and in deployment of docker containers (each service of the app in a container): simplified installations (on developers machines and on the server), reduced communication overhead between dev team and ops team. 
differences of docker containers and Virtual Machines: VM images include OS kernel layer of virtualization (virtualization of the hardware), they are heavier. On the contrary, docker images only include OS application layer. this could be a problem, as docker containers created in Linux do not work on a Windows system. This is solved making use of Docker Desktop (that add an Hypervisor layer with a subtle Linux Kernel to let linux based images be executed on Windows, or Mac) 

 