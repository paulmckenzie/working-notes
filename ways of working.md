# ways of working

## Email

I have already laid out a lot of my thoughts about email in an earlier text. I think the only thing to add is around archiving,
searching and retrieval. It's an email-heavy environment we live in and using Outlook with corporate storage allocations from
the year 2005, no useful tagging and woeful search, there's a problem with finding out what someone decided if it was more than three months ago. It's like we decided to have some kind of wilful corporate amnesia. So in the first week look at how the organisation has set up automatic archiving for Outlook. Make sure you can search your archives.

## Notes

Who do you contact about a MQ queue filling up? How do you request a new remote access token? What's the help desk number? Is a depot account at the ISIN level or not?  This is the stuff that I can never remember, and sometimes it is a little embarrassing.  The solution is to make plenty of notes.  But how/where?  Undoubtedly, the company has blocked access to Evernote, and it will also have policies about what you can store on personal wiki spaces. I think the answer is in plain text files or structured text files (markdown, by preference), backed-up to a personal, private git repo.  If the notes-repo is cloned into ~/Notes, then it will also be private on the PC.

Suggested files in ~/Notes:

* whoswho.txt -- an alphabetical list of the people in the organisation, with a brief description of their role and their contact details
* phones.txt -- common numbers like help desk, room reservations etc.
* aboutme.txt -- my less commonly used ids, my cost centre code etc.

## Markdown

Use (git-flavoured) markdown by preference, as it is displayed nicely in Git. Add a plugin to the browser to correctly view these and make the browser the default app to open ".md" files.

## Passwords

How come that companies make you use a multitude of passwords but discourage password keepers like 1Password?

## Browser Bookmarks

Keep a single root folder for all work URLs. This means that is you're lucky enough to be able to synch your bookmarks inside and outside the company then you can just delete that folder when you go. My current tree looks like:

```
  Work/
    Status/
    Team/
      Browsers/
        Gitlab
        Jira
      Documentation/
        Wiki
    Company/
       Browsers/
         Corporate Directory
```

## Work Journal

One of the things I struggle with most is remembering the details once the immediate task has been completed. I can work on a feature and it's all there in my head but two days after I have completed it, it's gone. Project documentation is not the solution as nobody does it anymore and it's always out of date. Keep a work journal. Write down stuff that seems stupidly obvious to you now, that you will always remember, because you won't

## Dot files

Keep these in your personal notes repo.

## Working From Home

The primary challenge with team members working from home is communication. If it takes more than a couple of seconds to contact someone then the natural impulse is to not bother. So we need to make getting in touch completely painless.

* Softphone or IP phone, e.g. IP Communicator
* Conference Bridge, aka Conference Line
* WebEx or similar
* Speed Dials
* Group Chat
