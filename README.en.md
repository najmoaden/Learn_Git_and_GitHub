<p align="center">
  <img width="500" src="./Logo.png" alt="Learn Git and GitHub">
</p>
<h1 align="center">Learn Git & GitHub</h1>
<p align="left">
  This repository is intended for students and junior developers to learn how to use the Git making it easier for you to connect to your  repositories from Github Account. If you don't have prior knowledge of Git, no problem I will teach you all about it here. If you don't  already have an account, go create an account now by clicking -> <a href="https://github.com/" target="_blank">GitHub</a>.
</p>

## What is Git & GitHub?

Imagine yourself with a team with whom you are doing a project called `Online Registration` and you are assigned with a specific task. How would you work with that group and write a code when all of you share the same code for the same project you are supposed to work simultaneously avoiding any conflict. Well, that's where Git and GitHub or GitLab, come in.

- What is `Git`?
<p align="left">
Git is a Version Control System, that actually works as a subsystem in a local format.
</p>

- What is `GitHub` ama `GitLab`?
<p align="left">
It is an online system which is designed to be store and monitored software projects that can give accesss to many developers who can work together on the project and use the Git system to share the project wherever it is maintained.
</p>

## <h1 align="left">Benefits of Using Git and GitHub</h1>

- It makes it easier for you to follow/track any changes made in your project.
- That you can work with a team of developers in a shared project.
- That you can connect to your own repository through CLI (Command Line Interface) also do push/pull to the GitHub repository.

<h3 align="left">What is Repository?</h3>
It is a place to store your project.

## <h1 align="left">Amarada aasaasiga ah ee Git</h1>

- `git config` waxa uu Git-ka baraa qafka aad tahay, asaga oo keydinaya magaacaga iyo email kaaga si loogu istcmaalo `git commits` kaaga.
- `git init` waxaa lugu abuura Git repository cusub.
- `git clone` waxa uu soo dajiyaa copy-ga project remote repository(sida `GitHub` ama `GitLab`) saaran.
- `git add` hal file ama ka badan ayuu ku daraa meesha diyaarinta(staging area).
- `git commit` waxa uu si taxana ah `Git` ka ugu keydiyaa faylasha isbadaka lugu sameeyay.
- `git status` waxa uu soo tixaa faylasha aad wax ka badashay iyo kuwa aadan wali `git add` ama `git commit` ku sameyn.
- `git push` faylasha aad soo commit gareysay ayuu remote repository(sida `GitHub` ama `GitLab`) saaraa.
- `git remote` local repository-ga ayuu remote repository (sida `GitHub` ama `GitLab`) ku xiraa.
- `git branch` waxa uu kuu sahlaa in aad projecti-gaaga laamo u qeybiso si ay developers-ka ugu fududaato in midkastaahi shaqadiisa
  si madaxbanaan u qabsado. `git branch` waxaa lugu abuurikaraa, arkikaraa ama tirikaraa laamaha projectiga.
- `git checkout` waxaa loo isticmaala sameynta branch cusub iyo in asaga loo wareego, sidookale branches horay u jiray ayaa la isaga gudbi karaa.
- `git pull` waxaa lugu helaa update-yadii u dambeeyay ee ka dhacay remote repository-ga.
- `git merge` isbadalada brach ka dhaca ayuu branch kale u gudbiyaa, tusaale: developers-ka shaqooyinka ay branch-yada kaladuwan ku soo qabtaan
  ugu dambeyn Main-ka ayey ku soo wareejiyaan.
- `git log` waxa uu soo bandhigaa branch-ga markaas la joogo commits-ka laga sameeyay.

## <h1 align="left">Sidee loogu Shubtaada Git Computer kaaga</h1>

### windows

- Si'aad u setup gareyso git waxaad u baahantahay in aad lasoo dagto programkan hadii aad isticmaalayso window adiga oo raacaya [Link]('https://git-scm.com/downloads').

### mac

- Si'aad u setup gareyso git waxaad u baahantahay in aad isticmaahso `HomeBrew` oo ku fududeynaayo in aad ku shubato `git` marka hore hobi in ow kugu jiro `brew` hadii ow san kugu jirin soo dagso [Home Brew]('https://brew.sh/') ama isticmaal command kan si aad ugu shubato:

```terminal
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

kadib ku shubo `git`:

```terminal
brew install git
```

### Linux

isticmaal Command-gan soosocdo si aad ugu shubato `git` linux-kaaga:

```terminal
sudo apt install git-all
```

# How to upload a local project to Github or GitLab using git commands

- First you need to open `Terminal` or `Command-Line Interface` by going to the Project / `Folder directory' and then use the following git commands.
- Write the commands in this order:
  - `git init` to create new repository.
  - `git add ` use the fullstop sign `.` when executing this command. The function of it is add all the files in repository at once. If you have already used the command and want to add invidual files you can do this by writing this way: `git add file.js`. Thsi command allows you to add the only one file at a time to your repository.
  - Kadib samey commit adiga oo adegsanaya commad-gan `git commit -m 'waxa aad samaysay ku qeexaya halkan'`
  - hadii aadan hore ugu link-gareysnayn github link-gaaga ama gitLab kaaga isticmaal command-gan `git remote add <git URL>`.
    -kadib push garey adiga oo adeegsanaya command-ga `git push origin main` hadii repositery-gaaga `master` yahay kubadal meesha `main` adiga oo qoraya sidan `git push origin Master`.

## Contribute to the project

To recap what you have learned so far, I want you to do the following:

- Fork the project to your Github account.
- Make a JSON file in the directory of contributers writing it in this format `./contributers/{your_name}.json`.

```json
{
  "name": "Your name",
  "university": "University your enrolled in or graduated from",
  "description": "Write a bit description here"
}
```

## Thank you all! (Contributers)

<a href = "https://github.com/abdorizak/Learn_Git_and_GitHub/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=abdorizak/Learn_Git_and_GitHub"/>
</a>

<h4 align="center">© 2022 Abdorizak, iOS Engineer || Mohamud A. Abshir, Front-End Engineer || Samir Samawade, Mobile Developer </h4>
