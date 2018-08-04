```yaml
      - id: Conventional
        url: "https://files.vexatos.com/Conventional/dev/Conventional-1.12.1-0.0.18.jar"
      - id: ConventionalChat
        url: "https://files.vexatos.com/Conventional/dev/ConventionalChat-1.12.1-0.0.5.jar"
    - feature:
        selected: true
        recommendation: starred
      entries:
        - id: FoamFix (Anarchy)
          provider: DIRECT
          url: https://asie.pl/files/mods/FoamFix/foamfix-0.9.9.1-1.12.2-anarchy.jar
          description: "Foamfix!"

    - side: CLIENT
      entries:
        - mumblelink
        - nonausea
        - feature:
            recommendation: starred
            selected: true
          entries:
            - id: toast-control
              description: "Removes Minecraft annoying Toasts."
            - id: journeymap
              description: "Minimap"
        - feature:
            selected: false
          entries:
            - id: worldeditcui-forge-edition-2
              description: "If you don't know what this is, I suggest not ticking it."
    - side: SERVER
      entries:
        - btfu-continuous-rsync-incremental-backup
        - id: MatterLink
          provider: DIRECT
          url: "https://ci.elytradev.com/job/elytra/job/MatterLink/job/master/lastSuccessfulBuild/artifact/1.12.2/build/libs/MatterLink-1.12.2-1.6.3-153.jar"
        - mtqfix
        - mybukkit-commands
        - unloader
        - worldedit
```