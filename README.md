# isec6000-assignment1-task1

Creating the Kubernetes Cluster On GKE:

Listed below are the steps for hte creation of the Kubernetes Cluster on GKE that were followed. 

1. Logged into the GKR console, landing on the main page.
![Capture](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/afc3b751-9fb2-43e3-ab26-b67c8c2e7d34)

2. From the main page, clicked on the top left hand corner to open the menu options. "Kubernetes Engine" was selected from the options.
![Step 2](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/b389ce8c-1656-4183-b220-4fe4d0ca119d)

3. Clicked create a project listed on the right of the screen. This Project was named 'ISEC Assignment' with no location for organization. 
![Step 3](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/237f9544-51f3-4b81-870a-dd0322d4a860)

4. From within the main project page ISEC Assignment, the option of enabling the Kubernetes Engine API was clicked. This took several minutes to enable.  
![Step 4](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/392b007b-8827-4f38-a6a4-a9d2ba66349e)

5. Once enabled, the create cluster option was selected from the page displayed.
![Step 5](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/daefa59d-ba42-48fc-93be-f596f10a8056)

6. Cluster Basics: The cluster was named 'hello-cluster-1' and was configured with the region 'us-central1'. The 
![Step 6](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/e4803b5d-5314-4120-8782-4782bee6476e)

7. Network Settings: The network was left as default, as well as node subnet. The IPV4 network access was selected as public cluster.
The cluster defauly Pod address range was configured to be /17, with all other settings left blank.

![Step 7a](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/f850a3b2-67fb-459b-b074-0785ef80d3b3)

![Step 7b](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/62b57d29-f7a1-43d6-91ab-589de885b312)

8. Advanced Settings: The release channel was chosen as Regular channel (default), with all other settings left with default values.
![Step 8](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/927b6f31-2916-4500-a5b1-03b84c1f111e)

9. Review and Create: The Review and Creation. When create button clicked, takes several minutes to create the cluster.
![Step 9a](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/7f8b4086-92da-4afb-8528-34ed359ac5f0)

![Step 9b](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/f0501d08-6079-43d8-b78d-a66aeb62ce37)

10. The green tick to the left of the cluster indicates that it is activated and working.
![Step 10](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/59029bbe-36cc-4b24-86e3-b9b903c0b182)

Install and Configure Kubectl To Manage Kubernetes Cluster

Below is listed the steps to install and configure Kubectl to manage Kubernetes Cluster:

1. In the Kubernetes Engine > Clusters section, the right hand side of hte listed cluster option menu was opened. The 'Connect' button was clicked. 
![Step 11](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/49e5ec59-b651-4fd4-a8bc-9945c707b1a4)

2. Once Clicked, a pop up menu with two options appeared. The Command-Line Access option was chosen. This command was copied to the clipboard.
The command was as follows: gcloud container clusters get-credentials hello-cluster-1 --region australia-southeast1 --project isec-assignment
![Step 12](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/dd6d6aad-0832-4466-8c85-f9f0f6702d20)

3. Closing the pop-up window, the CLI button was clicked in the top right hand corner of the screen to enable CLI. The above command was pasted into the terminal. 
![Step 13](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/d76e3fa1-2de2-4dad-970c-9d97d8ad179e)

4. The command was run.
![Step 14](https://github.com/liamsutton601/isec6000-assignment1-task1/assets/130027096/3f4012aa-f5e2-4e43-baee-3cec619494c0)











