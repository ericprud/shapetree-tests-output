# footprint-tests output

This repo captures the output of [footprint-tests](../../../footprint-tests).

## file tree

```
.
├── Apps
│   ├── CollisionTest
│   │   └── _self.ttl
│   ├── GhApp
│   │   └── _self.ttl
│   ├── GhApp2
│   │   └── _self.ttl
│   ├── MultiCalApp
│   │   └── _self.ttl
│   ├── NeverNoteApp
│   │   └── _self.ttl
│   ├── PhotoAlbumApp
│   │   └── _self.ttl
│   ├── PhotoApp
│   │   └── _self.ttl
│   └── _self.ttl
├── Cache
│   ├── httplocalhost12345albumPhotoAlbumBlueprintroot
│   ├── httplocalhost12345badBlueprintMissingSchemaroot
│   ├── httplocalhost12345badBlueprintMissingShaperoot
│   ├── httplocalhost12345badBlueprintNestedTwoStaticNamesroot
│   ├── httplocalhost12345badBlueprintNoShapePropertyroot
│   ├── httplocalhost12345badBlueprintTwoStaticNamesroot
│   ├── httplocalhost12345badPhotoAlbumBlueprintroot
│   ├── httplocalhost12345calCalendarBlueprintcalendar
│   ├── httplocalhost12345calGoogleBlueprinttop
│   ├── httplocalhost12345ghghBlueprintroot
│   ├── httplocalhost12345nevernoteNeverNoteBlueprintroot
│   ├── httplocalhost12345photoPhotoBlueprintroot
│   ├── httpsjaneirodigitalgithubioshapetreessolidAppsstaticRootnevernoteNeverNoteBlueprintttl
│   └── _self.ttl
├── collisionDir
│   ├── collision-2
│   │   ├── Events
│   │   │   └── _self.ttl
│   │   └── _self.ttl
│   └── _self.ttl
├── README.md
├── _self.ttl
├── Shared
│   ├── Albums2019
│   │   ├── ref-1.ttl
│   │   └── _self.ttl
│   ├── bad-malformed-blueprint-nested-two-names
│   │   └── _self.ttl
│   ├── bad-missing-shape-property
│   │   └── _self.ttl
│   ├── bad-nonconformant-posts
│   │   └── _self.ttl
│   ├── bad-nonexistent-shape
│   │   └── _self.ttl
│   ├── bad-unGETtable-shape
│   │   └── _self.ttl
│   ├── Calendar
│   │   ├── event1.ttl
│   │   └── _self.ttl
│   ├── Git
│   │   ├── repos
│   │   │   ├── ericprud
│   │   │   │   ├── jsg
│   │   │   │   │   ├── issues
│   │   │   │   │   │   ├── 1.ttl
│   │   │   │   │   │   └── _self.ttl
│   │   │   │   │   ├── labels
│   │   │   │   │   │   └── _self.ttl
│   │   │   │   │   ├── milestones
│   │   │   │   │   │   └── _self.ttl
│   │   │   │   │   └── _self.ttl
│   │   │   │   └── _self.ttl
│   │   │   └── _self.ttl
│   │   ├── _self.ttl
│   │   └── users
│   │       ├── alice
│   │       │   ├── followers
│   │       │   │   └── _self.ttl
│   │       │   ├── orgs
│   │       │   │   └── _self.ttl
│   │       │   ├── received_events
│   │       │   │   └── _self.ttl
│   │       │   ├── repos
│   │       │   │   └── _self.ttl
│   │       │   ├── _self.ttl
│   │       │   └── subscriptions
│   │       │       ├── _self.ttl
│   │       │       └── subscr1.ttl
│   │       ├── alice-1
│   │       │   ├── followers
│   │       │   │   └── _self.ttl
│   │       │   ├── orgs
│   │       │   │   └── _self.ttl
│   │       │   ├── received_events
│   │       │   │   └── _self.ttl
│   │       │   ├── repos
│   │       │   │   └── _self.ttl
│   │       │   ├── _self.ttl
│   │       │   └── subscriptions
│   │       │       └── _self.ttl
│   │       ├── Container
│   │       │   ├── followers
│   │       │   │   └── _self.ttl
│   │       │   ├── orgs
│   │       │   │   └── _self.ttl
│   │       │   ├── received_events
│   │       │   │   └── _self.ttl
│   │       │   ├── repos
│   │       │   │   └── _self.ttl
│   │       │   ├── _self.ttl
│   │       │   └── subscriptions
│   │       │       └── _self.ttl
│   │       └── _self.ttl
│   ├── Google
│   │   ├── Events
│   │   │   ├── 09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
│   │   │   ├── 19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
│   │   │   └── _self.ttl
│   │   └── _self.ttl
│   ├── NeverNotes
│   │   ├── note1
│   │   │   ├── img-M33_IR.jpg
│   │   │   ├── inc-M33_IR.ttl
│   │   │   └── _self.ttl
│   │   └── _self.ttl
│   ├── Photos2020-01
│   │   ├── m33.jpeg
│   │   └── _self.ttl
│   └── _self.ttl
└── some
    ├── deep
    │   ├── path
    │   │   ├── Albums2019
    │   │   │   ├── ref-1.ttl
    │   │   │   └── _self.ttl
    │   │   ├── Git
    │   │   │   ├── repos
    │   │   │   │   ├── ericprud
    │   │   │   │   │   ├── jsg
    │   │   │   │   │   │   ├── issues
    │   │   │   │   │   │   │   ├── 1.ttl
    │   │   │   │   │   │   │   └── _self.ttl
    │   │   │   │   │   │   ├── labels
    │   │   │   │   │   │   │   └── _self.ttl
    │   │   │   │   │   │   ├── milestones
    │   │   │   │   │   │   │   └── _self.ttl
    │   │   │   │   │   │   └── _self.ttl
    │   │   │   │   │   └── _self.ttl
    │   │   │   │   └── _self.ttl
    │   │   │   ├── _self.ttl
    │   │   │   └── users
    │   │   │       ├── alice
    │   │   │       │   ├── followers
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── orgs
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── received_events
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── repos
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── _self.ttl
    │   │   │       │   └── subscriptions
    │   │   │       │       ├── _self.ttl
    │   │   │       │       └── subscr1.ttl
    │   │   │       ├── alice-1
    │   │   │       │   ├── followers
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── orgs
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── received_events
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── repos
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── _self.ttl
    │   │   │       │   └── subscriptions
    │   │   │       │       └── _self.ttl
    │   │   │       ├── Container
    │   │   │       │   ├── followers
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── orgs
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── received_events
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── repos
    │   │   │       │   │   └── _self.ttl
    │   │   │       │   ├── _self.ttl
    │   │   │       │   └── subscriptions
    │   │   │       │       └── _self.ttl
    │   │   │       └── _self.ttl
    │   │   └── _self.ttl
    │   └── _self.ttl
    └── _self.ttl

81 directories, 108 files
```


## test run output

```

> blueprint-tests@0.0.0 test:quiet /home/eric/checkouts/janeirodigital/footprintlib.js/footprints
> npm run prepare-tests && PORT=12345 nyc mocha --slow 200 --reporter mocha-slow-options --reporter-options useReporter=spec,mediumPercent=80


> blueprint-tests@0.0.0 prepare-tests /home/eric/checkouts/janeirodigital/footprintlib.js/footprints
> mkdir -p www && ls -d www/* | grep -v README.md | xargs rm -rf



  test/local.test.js
    appStoreServer
      ✓ should return on empty path
      ✓ should resolve full path
    Blueprint.local
      ✓ should throw if not passed a URL
    Blueprint.managedContainer
      ✓ should throw if not passed a Container URL
      ✓ should throw if the Container URL doesn't end with '/'
      ✓ should throw if the Container URL ends with '//'
      ✓ should throw if the blueprint parameter isn't a URL
      ✓ should remove a Container directory
      ✓ should fail on an invalid blueprint graph
    Blueprint.remote
      ✓ should throw if not passed a URL
      ✓ should throw on a GET failure
    Blueprint.validate
      ✓ should throw if blueprint step is missing a shape
      ✓ should throw on malformed POST Turtle body
      ✓ should throw on malformed POST JSON-LD body
    Blueprint misc
      ✓ should construct all errors
      ✓ should render RDFJS nodes
    STOMP
      ✓ should fail with bad Turtle
      ✓ should fail with bad JSON
      ✓ should fail with bad JSONLD
      ✓ should create a novel directory (183ms)
      create /collisionDir/collision-2/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z
        ✓ should POST /collisionDir/collision-2/Events/
        ✓ should GET /collisionDir/collision-2/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
        ✓ should !GET /collisionDir/collision-2/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
        ✓ should delete a file
        ✓ should delete the above novel directory

  initial state
    ✓ should GET /Shared/
    ✓ should !GET /Shared/NeverNotes/

  create /Shared/NeverNotes/ hierarchy
    create /Shared/NeverNotes/
      ✓ should STOMP /Shared/NeverNotes
      ✓ should GET /Shared/NeverNotes/
    create /Shared/NeverNotes/note1/
      ✓ should POST /Shared/NeverNotes/
      ✓ should GET /Shared/NeverNotes/note1/
      ✓ should !GET /Shared/NeverNotes/note2/
      ✓ should !GET /Shared/NeverNotes/note1/img-M33_IR.jpg
      ✓ should !GET /Shared/NeverNotes/note1/inc-M33_IR.ttl
    create /Shared/NeverNotes/note1/img-M33_IR.jpg
      ✓ should POST /Shared/NeverNotes/note1/
      ✓ should GET /Shared/NeverNotes/note1/img-M33_IR.jpg
    create /Shared/NeverNotes/note1/inc-M33_IR.ttl
      ✓ should POST /Shared/NeverNotes/note1/
      ✓ should GET /Shared/NeverNotes/note1/inc-M33_IR.ttl

  initial state
    ✓ should GET /Shared/
    ✓ should !GET /Shared/Photos2020-01/

  create /Shared/Photos2020-01/ hierarchy
    create /Shared/Photos2020-01/
      ✓ should STOMP /Shared/Photos2020-01
      ✓ should GET /Shared/Photos2020-01/
    create /Shared/Photos2020-01/m33
      ✓ should POST /Shared/Photos2020-01/
      ✓ should GET /Shared/Photos2020-01/m33.jpeg
      ✓ should !GET /Shared/Photos2020-01/m32.jpeg

  initial state
    ✓ should GET /Shared/
    ✓ should !GET /Shared/Albums2019/

  create /Shared/Albums2019/ hierarchy
    create /Shared/Albums2019/
      ✓ should STOMP /Shared/Albums2019
      ✓ should GET /Shared/Albums2019/
    create /Shared/Albums2019/ref-1
      ✓ should POST /Shared/Albums2019/
      ✓ should GET /Shared/Albums2019/ref-1.ttl
      ✓ should !GET /Shared/Albums2019/ref-2.ttl

  initial state
    ✓ should GET /Shared/
    ✓ should !GET /Shared/bad-nonconformant-POST/
    ✓ should fail to delete /
    ✓ should fail to delete /doesnotexist

  STOMP
    should fail with bad Turtle
      ✓ should STOMP /Shared/ShouldNotExist
      ✓ should !GET /Shared/ShouldNotExist/
    should fail with bad JSON
      ✓ should STOMP /Shared/ShouldNotExist
      ✓ should !GET /Shared/ShouldNotExist/
    should fail with bad JSONLD
      ✓ should STOMP /Shared/ShouldNotExist
      ✓ should !GET /Shared/ShouldNotExist/

  create /Shared/bad-nonexistent-shape/ hierarchy -- schema does not contain shape
    create /Shared/bad-nonexistent-shape/
      ✓ should STOMP /Shared/bad-nonexistent-shape
      ✓ should GET /Shared/bad-nonexistent-shape/
    create /Shared/bad-nonexistent-shape/ref-1
      ✓ should POST /Shared/bad-nonexistent-shape/
      ✓ should !GET /Shared/bad-nonexistent-shape/ref-1.ttl

  create /Shared/bad-unGETtable-shape/ hierarchy -- can't GET referenced shape
    create /Shared/bad-unGETtable-shape/
      ✓ should STOMP /Shared/bad-unGETtable-shape
      ✓ should GET /Shared/bad-unGETtable-shape/
    create /Shared/bad-unGETtable-shape/ref-1
      ✓ should POST /Shared/bad-unGETtable-shape/
      ✓ should !GET /Shared/bad-unGETtable-shape/ref-1.ttl

  create /Shared/bad-nonconformant-posts/ hierarchy -- POSTed data does not validate
    create /Shared/bad-nonconformant-posts/
      ✓ should STOMP /Shared/bad-nonconformant-posts
      ✓ should GET /Shared/bad-nonconformant-posts/
    create /Shared/bad-nonconformant-posts/malformed-ref-1
      ✓ should POST /Shared/bad-nonconformant-posts/
      ✓ should !GET /Shared/bad-nonconformant-posts/malformed-ref-1.ttl
    create /Shared/bad-nonconformant-posts/ref-invalid-2
      ✓ should POST /Shared/bad-nonconformant-posts/
      ✓ should !GET /Shared/bad-nonconformant-posts/ref-invalid-2.ttl
    create /Shared/bad-nonconformant-posts/ref-valid-3
      ✓ should POST /Shared/bad-nonconformant-posts/
      ✓ should !GET /Shared/bad-nonconformant-posts/ref-valid-3.ttl

  create /Shared/bad-malformed-blueprint-two-names/ hierarchy -- malformed blueprint: two static names
    create /Shared/bad-malformed-blueprint-two-names/
      ✓ should STOMP /Shared/bad-malformed-blueprint-two-names
      ✓ should !GET /Shared/bad-malformed-blueprint-two-names/

  create /Shared/bad-malformed-blueprint-nested-two-names/ hierarchy -- malformed blueprint: two nested static names
    create /Shared/bad-malformed-blueprint-nested-two-names/
      ✓ should STOMP /Shared/bad-malformed-blueprint-nested-two-names
      ✓ should GET /Shared/bad-malformed-blueprint-nested-two-names/
    create /Shared/bad-malformed-blueprint-nested-two-names/ref-1
      ✓ should POST /Shared/bad-malformed-blueprint-nested-two-names/
      ✓ should !GET /Shared/bad-malformed-blueprint-nested-two-names/ref-1.ttl

  create /Shared/bad-missing-shape-property/ hierarchy -- blueprint step has no shape property
    create /Shared/bad-missing-shape-property/
      ✓ should STOMP /Shared/bad-missing-shape-property
      ✓ should GET /Shared/bad-missing-shape-property/
    create /Shared/bad-missing-shape-property/ref-1
      ✓ should POST /Shared/bad-missing-shape-property/
      ✓ should !GET /Shared/bad-missing-shape-property/ref-1.ttl

  initial state
    ✓ should GET /some/deep/path/
    ✓ should !GET /some/deep/path/Albums2019/

  create /some/deep/path/Albums2019/ hierarchy
    create /some/deep/path/Albums2019/
      ✓ should STOMP /some/deep/path/Albums2019
      ✓ should GET /some/deep/path/Albums2019/
    create /some/deep/path/Albums2019/ref-1
      ✓ should POST /some/deep/path/Albums2019/
      ✓ should GET /some/deep/path/Albums2019/ref-1.ttl
      ✓ should !GET /some/deep/path/Albums2019/ref-2.ttl

  initial state
    ✓ should GET /Shared/
    ✓ should !GET /Shared/Calendar/

  create /Shared/Calendar/ hierarchy
    create /Shared/Calendar/
      ✓ should STOMP /Shared/Calendar
      ✓ should STOMP /Shared/Google
      ✓ should GET /Shared/Calendar/
    create /Shared/Calendar/event1
      ✓ should POST /Shared/Calendar/
      ✓ should GET /Shared/Calendar/event1.ttl
      ✓ should !GET /Shared/Calendar/event2.ttl
    create /Shared/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z
      ✓ should POST /Shared/Google/Events/
      ✓ should GET /Shared/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
      ✓ should !GET /Shared/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
    create /Shared/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z
      ✓ should POST /Shared/Google/Events/
      ✓ should GET /Shared/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
      ✓ should GET /Shared/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl

  initial state
    ✓ should GET /Shared/
    ✓ should !GET /Shared/Git/

  create /Shared/Git/
    ✓ should STOMP /Shared/Git
    ✓ should GET /Shared/Git/

  re-create /Shared/Container/
    ✓ should STOMP /Shared/-TBD-

  create /Shared/Git/users/alice/
    ✓ should POST /Shared/Git/users/
    ✓ should GET /Shared/Git/users/alice/
    ✓ should GET /Shared/Git/users/alice/subscriptions/
    ✓ should !GET /Shared/Git/users/alice-1/
    create /Shared/Git/users/alice/subscriptions/
      ✓ should POST /Shared/Git/users/alice/subscriptions/
      ✓ should GET /Shared/Git/users/alice/subscriptions/subscr1.ttl

  create /Shared/Git/users/alice-1/
    ✓ should POST /Shared/Git/users/
    ✓ should GET /Shared/Git/users/alice/
    ✓ should GET /Shared/Git/users/alice-1/

  create /Shared/Git/users/Container/
    ✓ should POST /Shared/Git/users/
    ✓ should GET /Shared/Git/users/alice-1/
    ✓ should GET /Shared/Git/users/Container/

  create /Shared/Git/repos/ericprud/ hiearchy
    create /Shared/Git/repos/ericprud/
      ✓ should POST /Shared/Git/repos/
      ✓ should GET /Shared/Git/repos/ericprud/
      ✓ should !GET /Shared/Git/repos/ericprud-1/
      ✓ should !GET /Shared/Git/repos/ericprud/jsg/
    create /Shared/Git/repos/ericprud/jsg/
      ✓ should POST /Shared/Git/repos/ericprud/
      ✓ should GET /Shared/Git/repos/ericprud/jsg/
      ✓ should GET /Shared/Git/repos/ericprud/jsg/issues/
      ✓ should GET /Shared/Git/repos/ericprud/jsg/labels/
      ✓ should GET /Shared/Git/repos/ericprud/jsg/milestones/
      ✓ should !GET /Shared/Git/repos/ericprud/jsg/issues/1.ttl
    create /Shared/Git/repos/ericprud/jsg/issues/1
      ✓ should POST /Shared/Git/repos/ericprud/jsg/issues/
      ✓ should GET /Shared/Git/repos/ericprud/jsg/issues/1.ttl
      ✓ should !GET /Shared/Git/repos/ericprud/jsg/issues/2.ttl

  initial state
    ✓ should GET /some/deep/path/
    ✓ should !GET /some/deep/path/Git/

  create /some/deep/path/Git/
    ✓ should STOMP /some/deep/path/Git
    ✓ should GET /some/deep/path/Git/

  re-create /some/deep/path/Container/
    ✓ should STOMP /some/deep/path/-TBD-

  create /some/deep/path/Git/users/alice/
    ✓ should POST /some/deep/path/Git/users/
    ✓ should GET /some/deep/path/Git/users/alice/
    ✓ should GET /some/deep/path/Git/users/alice/subscriptions/
    ✓ should !GET /some/deep/path/Git/users/alice-1/
    create /some/deep/path/Git/users/alice/subscriptions/
      ✓ should POST /some/deep/path/Git/users/alice/subscriptions/
      ✓ should GET /some/deep/path/Git/users/alice/subscriptions/subscr1.ttl

  create /some/deep/path/Git/users/alice-1/
    ✓ should POST /some/deep/path/Git/users/
    ✓ should GET /some/deep/path/Git/users/alice/
    ✓ should GET /some/deep/path/Git/users/alice-1/

  create /some/deep/path/Git/users/Container/
    ✓ should POST /some/deep/path/Git/users/
    ✓ should GET /some/deep/path/Git/users/alice-1/
    ✓ should GET /some/deep/path/Git/users/Container/

  create /some/deep/path/Git/repos/ericprud/ hiearchy
    create /some/deep/path/Git/repos/ericprud/
      ✓ should POST /some/deep/path/Git/repos/
      ✓ should GET /some/deep/path/Git/repos/ericprud/
      ✓ should !GET /some/deep/path/Git/repos/ericprud-1/
      ✓ should !GET /some/deep/path/Git/repos/ericprud/jsg/
    create /some/deep/path/Git/repos/ericprud/jsg/
      ✓ should POST /some/deep/path/Git/repos/ericprud/
      ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/
      ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/issues/
      ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/labels/
      ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/milestones/
      ✓ should !GET /some/deep/path/Git/repos/ericprud/jsg/issues/1.ttl
    create /some/deep/path/Git/repos/ericprud/jsg/issues/1
      ✓ should POST /some/deep/path/Git/repos/ericprud/jsg/issues/
      ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/issues/1.ttl
      ✓ should !GET /some/deep/path/Git/repos/ericprud/jsg/issues/2.ttl


  169 passing (5s)

------------------------|---------|----------|---------|---------|-------------------
File                    | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
------------------------|---------|----------|---------|---------|-------------------
All files               |     100 |      100 |   97.65 |     100 |                   
 footprints             |     100 |      100 |     100 |     100 |                   
  appStoreServer.js     |     100 |      100 |     100 |     100 |                   
  ldpServer.js          |     100 |      100 |     100 |     100 |                   
 footprints/ecosystems  |     100 |      100 |     100 |     100 |                   
  simple-apps.js        |     100 |      100 |     100 |     100 |                   
 footprints/filesystems |     100 |      100 |     100 |     100 |                   
  fs-promises-utf8.js   |     100 |      100 |     100 |     100 |                   
 footprints/util        |     100 |      100 |   95.45 |     100 |                   
  blueprint.js          |     100 |      100 |   95.45 |     100 |                   
  constants.js          |     100 |      100 |     100 |     100 |                   
------------------------|---------|----------|---------|---------|-------------------
```
