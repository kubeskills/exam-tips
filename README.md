# exam-tips
Preparing for a Kubernetes Exam


### Prerequisites

<details><summary>show</summary>
<p>

- Linux 
    - Navigate the command line
    - move around directoies
    - use vim to edit files
    - use system services, 
    - use /var/log and view logs (grep logs)
- Docker
    - create container, 
    - list running containers 
    - use crictl, 
    - expose ports on container

- [Linux and Docker Fundamentals Course w/Exercises](https://youtu.be/EUu1E_YKGTw)

</p>
</details>

---

### What to focus on

<details><summary>show</summary>
<p>

- [Join a book club](https://www.santana.dev/book-club)
- [My list of books](https://learning.oreilly.com/playlists/8bb568ff-25aa-4c51-8823-9fb70091459a/)
- stick to a course
    - [KodeKloud w/labs (best and lowest price)](https://kodekloud.com/)
    - [Techworld with Nana](https://www.techworld-with-nana.com/)
    - [ACG w/free instances](https://acloudguru.com/)
- Overall, just pick a course that has a lot of demonstrations. courses that have a majority slides and text are no good. 
- Also, choose a course that has practice labs (like the one that comes with the exam purchase by [Killer.sh](https://killer.sh))
- make sure you're used to racing the clock (time yourself)
- don't fall into trap of building your own cluster (use [Killercoda](https://killercoda.com) instead)
- learn how to use shortcuts to create yaml (e.g. `k run nginx --image nginx --dry-run=client -o yaml > pod.yaml`)
- use `k -n ckjd0018` to autocomplete names of namespaces and resources within
- Make sure you are in the right cluster (each exam task will show you how to change context)
- if you ssh into a node, always go back to candidate VM (e.g. prompt will say `candidate@vm1: ~` not `root@control-plane-node: ~`)
- Make sure you're on the control plane node in order to reach `/etc/kubernetes/manifests`
- Practice, Practice, Practice
    - [Exercises](https://github.com/chadmcrowell/CKA-Exercises)
    - [More Exercises](https://github.com/dgkanatsios/CKAD-exercises)
    - [Always backup etcd this way (will save time)](https://killercoda.com/chadmcrowell/scenario/kubernetes-backup-etcd)
- You're not allowd to use bookmarked sites anymore (get used to searching in kubernetes.io/docs)
- [Exam Environment Preview](https://youtu.be/9UqkWcdy140)
- [Updated Exam Environment](https://youtu.be/1fSxM0_dtac)

</p>
</details>

---

### How to prepare

<details><summary>show</summary>
<p>

- Build Habits
    - Give 2 hours in the morning everyday to study. You are most refreshed and able to retain information. If you wait, you'll get distracted and tired and push it off to another day.
    - Take notes, and after go back through your notes and customize that for you (fleeting note and permanent note)
    - [How to take permanent notes](https://youtu.be/Cn6Kol5uZ2o)
    - [How to organize everything you read](https://ryanholiday.net/the-notecard-system-the-key-for-remembering-organizing-and-using-everything-you-read/)
    - [Keep a commonplace book](https://ryanholiday.net/how-and-why-to-keep-a-commonplace-book/)

</p>
</details>


---

### Summary

<details><summary>show</summary>
<p>

- Prereqs
- Linux
- Docker
- Vim
- Focus only on what you need to know
- use shortcuts as often as you can
- build a body of knowledge that you can teach to others
- build a good study habit
- use the power of community

</p>
</details>






