# noor-chat-message

Action send chat messages to a thread in [Noor](https://noor.to)

```
- name: Send Chat Message
  uses: jmunckhof/noor-chat-message@v1
  with:
    api-key: ${{ secrets.NOOR_API_KEY }}
    thread-name: "release-updates"
    space-id: <space-id>
    text: <text>
```
