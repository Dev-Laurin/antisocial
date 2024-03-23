# antisocial
A (parody) social media site built around being the opposite of a social media site (anti-social). Instead of encouraging following and connecting with more people, the site encourages you to dis-associate with people through recommendations (you haven't DM'd this person in awhile, perhaps you should drop them from your friends list).

```mermaid
sequenceDiagram
    participant Anti
    participant Bob
    Anti->>John: John, you haven't spoken to Bob since his work-i-versary last year.
    John-->>Anti: I just don't message Bob on LinkedIn that often. I talk to him everyday at work though.
    loop FriendCheck
        John->>John: Is Bob a friend? Or just a co-worker?
    end
    Anti->>John: I know that. If I saw you browsing LinkedIn I would have assumed you were fired.
    Anti->>John: You have no chats with Bob on your Discord, which you frequent.
    John-->>Anti: Yes, but I do talk to Bob at work daily. He's vital to my everyday.
    Anti->>John: Do you only talk about work?
    John-->>Anti: Y-Yes...
    Anti->>John: Are you going to remove him from your friends list or should I?
```

## Design
[Design doc](/docs/Design.md)
