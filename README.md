# Eagle Army Docs
A documentation project created for Eagle Army 3488 because everyone with experience keeps graduating. If anyone wants to add random stuff here feel free, I really don't know what else to type :p

## Important Organizational / Project Notes
- All project related documents are located inside of `docs/_admin` folder
- Feature requests that require / required a bit more extra work to implement should be noted inside `info/features.md`. (This is mainly so we know what extra extended features we added so we can potentially utilize them in subsequent sections, e.g. comments right on code, maybe special stuff for embedding certain files, etc.)
- PLEASE KEEP IN MIND THE GUIDELINES FOR WRITING AS NOTED IN `info/guidelines.md`
- See `info/weekly-notes/timeline.md` for some info on how we're trying to pace this project (or use the webpage version while hosting the website locally)

## Requirements
- `git` (duh)
- `python>=3.7.x`
- `pip`
- (Optional) `virtualenv`

## Getting Started
1. Clone the repository into your desired working directory and `cd` into the project.

```bash
git clone https://github.com/jrecera0/EagleArmyDocs.git
cd EagleArmyDocs
```

2. (Optional) Create a new virtual python environment for this project and activate it. It'll keep libraries and required dependencies isolated from your main python install and in general is just good for organizational purposes. DO NOT COMMIT YOUR VIRTUAL ENVIRONMENT TO THIS REPO.

```bash
# Try python3 if python doesn't work
python -m virtualenv .venv # or whatever name you'd like to give your environment

# Unix
source .venv/bin/activate

# Windows
.\.venv\Scripts\activate

# To deactivate your virtual environment:
deactivate
```
3. Install `mkdocs-material`:

```bash
pip install mkdocs-material
```

4. Run the live server using `mkdocs serve`. Changes made will be reflected immediately upon saving files.

Congratulations! Hopefully from here you now have a working documentation site running at `127.0.0.1:8000`. Did I need to type all this? Probably not! But it's here if you need it!

## FAQ
### Q: Why isn't git cloning this repository?
A: fix your git configuration >:3c On a more serious note, you do need to make sure your GitHub account is actually linked up properly because this is a private repository.

### Q: Okay cool the server is running, but how do I edit files?
A: Go into the `docs` directory to find all the markdown files to edit for each individual webpage. Webpages and endpoints are configured in `mkdocs.yml`, see library documentation for more info.

### Q: My vscode environment is broken, what do I do
A: idk lmao

### Q: Why did you type out this entire README.md when there's literally only 3 of us working on this project?
A: Honestly, I don't know but it gives me some sense of organization and I thought it'd be fun.

### Q: Furries?
A: Furries.

### Q: I have a question not listed here and I need help!
A: ~~cry about it~~ DM the group chat, we'll figure it out and try to fix whatever issue you're running into!
