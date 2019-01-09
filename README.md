# The Lambda School Git Flow

1. Student will create OWN version of Repo ---> (Fork)

2. Student will add PM as collaborator

   **on GitHub:**

   _Settings_ -> _Collaborators_ -> _Add Collaborator (use your PM's handle)_</br>
   _(I'd suggest grabbing the invite tag and DM it to your PM on Slack at this point)_

3. Student then will Clone Repo

   **back on your machine:**  
   `git clone <your-repo-address>`

4. Student will then create a branch (on which the student will implement the project)

   `cd <repo directory>`</br>
   `git checkout -b 'firstname-lastname'`

5)  Student will then submit their PR into the new branch.
    Student will use their own student fork as the base (compare across forks).

    `git push origin firstname-lastname`

    **on GitHub:**

    Compare & Pull Request -> Base: YOUR MASTER (Not the Lambda Master)  
     compare fork: YOUR FORK

    Then click on _Reviewers_. If your PM has accepted your invite, then you should be able to select them here. If not, then they haven't accepted the invite, and come back later...

6)  Student will add their PM as a reviewer on the PR
    PM then will count the HW as done by merging the HW back into master "STUDENT FORK".

    On the _'Open a Pull Request'_ page click on _Reviewers_. If your PM has accepted your invite, then you should be able to select them here. If not, then they haven't accepted the invite, and come back later...

    Your PM will merge the work into your Master fork when they have reviewed and approved it.
