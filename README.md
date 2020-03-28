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
│   ├── httplocalhost12345albumPhotoAlbumFootprintroot
│   ├── httplocalhost12345badFootprintMissingSchemaroot
│   ├── httplocalhost12345badFootprintMissingShaperoot
│   ├── httplocalhost12345badFootprintNestedTwoStaticNamesroot
│   ├── httplocalhost12345badFootprintNoShapePropertyroot
│   ├── httplocalhost12345badFootprintTwoStaticNamesroot
│   ├── httplocalhost12345badPhotoAlbumFootprintroot
│   ├── httplocalhost12345calCalendarFootprintcalendar
│   ├── httplocalhost12345calGoogleFootprinttop
│   ├── httplocalhost12345ghghFootprintroot
│   ├── httplocalhost12345photoPhotoFootprintroot
│   ├── httplocalhost46175albumPhotoAlbumFootprintroot
│   ├── httplocalhost46175badFootprintMissingSchemaroot
│   ├── httplocalhost46175badFootprintMissingShaperoot
│   ├── httplocalhost46175badFootprintNestedTwoStaticNamesroot
│   ├── httplocalhost46175badFootprintNoShapePropertyroot
│   ├── httplocalhost46175badFootprintTwoStaticNamesroot
│   ├── httplocalhost46175badPhotoAlbumFootprintroot
│   ├── httplocalhost46175calCalendarFootprintcalendar
│   ├── httplocalhost46175calGoogleFootprinttop
│   ├── httplocalhost46175ghghFootprintroot
│   ├── httplocalhost46175nevernoteNeverNoteFootprintroot
│   ├── httplocalhost46175photoPhotoFootprintroot
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
│   ├── bad-malformed-footprint-nested-two-names
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
│   │   │   ├── M33_IR.jpg
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

81 directories, 117 files
```


## test run output

```

> footprint-tests@0.0.0 test /home/eric/checkouts/janeirodigital/footprints
> npm run prepare-tests && nyc mocha --slow 200


> footprint-tests@0.0.0 prepare-tests /home/eric/checkouts/janeirodigital/footprints
> mkdir -p www && ls -d www/* | grep -v README.md | xargs rm -rf



  test/bad.test.js - installed in Shared
    initial state
      ✓ should GET /Shared/
      ✓ should !GET /Shared/bad-nonconformant-POST/
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
    create /Shared/bad-malformed-footprint-two-names/ hierarchy -- malformed footprint: two static names
      create /Shared/bad-malformed-footprint-two-names/
        ✓ should STOMP /Shared/bad-malformed-footprint-two-names
        ✓ should !GET /Shared/bad-malformed-footprint-two-names/
    create /Shared/bad-malformed-footprint-nested-two-names/ hierarchy -- malformed footprint: two nested static names
      create /Shared/bad-malformed-footprint-nested-two-names/
        ✓ should STOMP /Shared/bad-malformed-footprint-nested-two-names
        ✓ should GET /Shared/bad-malformed-footprint-nested-two-names/
      create /Shared/bad-malformed-footprint-nested-two-names/ref-1
        ✓ should POST /Shared/bad-malformed-footprint-nested-two-names/
        ✓ should !GET /Shared/bad-malformed-footprint-nested-two-names/ref-1.ttl
    create /Shared/bad-missing-shape-property/ hierarchy -- footprint step has no shape property
      create /Shared/bad-missing-shape-property/
        ✓ should STOMP /Shared/bad-missing-shape-property
        ✓ should GET /Shared/bad-missing-shape-property/
      create /Shared/bad-missing-shape-property/ref-1
        ✓ should POST /Shared/bad-missing-shape-property/
        ✓ should !GET /Shared/bad-missing-shape-property/ref-1.ttl

  test/cal.test.js installed in Shared
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

  test/gh-deep.test.js installed in Shared
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

  test/gh-deep.test.js installed in some/deep/path
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

  test/local.test.js
    appStoreServer
      ✓ should return on empty path
      ✓ should resolve full path
    Footprint.local
      ✓ should throw if not passed a URL
    Footprint.localContainer
      ✓ should throw if not passed a Container URL
      ✓ should throw if the Container URL doesn't end with '/'
      ✓ should throw if the footprint URL doesn't end with '/'
      ✓ should remove a Container directory
      ✓ should fail on an invalid footprint graph
    Footprint.remote
      ✓ should throw if not passed a URL
      ✓ should throw on a GET failure
    Footprint.validate
      ✓ should throw if footprint step is missing a shape
      ✓ should throw on malformed POST Turtle body
      ✓ should throw on malformed POST JSON-LD body
    Footprint misc
      ✓ should construct all errors
      ✓ should render RDFJS nodes
    STOMP
      ✓ should fail with bad Turtle
      ✓ should fail with bad JSON
      ✓ should fail with bad JSONLD
      ✓ should create a novel directory

  test/nevernote.test.js installid in Shared
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
        ✓ should !GET /Shared/NeverNotes/note1/M33_IR.jpg
      create /Shared/NeverNotes/note1/M33_IR.jpg
        ✓ should POST /Shared/NeverNotes/note1/
        ✓ should GET /Shared/NeverNotes/note1/M33_IR.jpg

  test/photo.test.js installid in Shared
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

  test/photoAlbum-shallow.test.js installed in Shared
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

  test/photoAlbum-shallow.test.js installed in some/deep/path
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


  158 passing (1s)

--------------------|---------|----------|---------|---------|-------------------
File                | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
--------------------|---------|----------|---------|---------|-------------------
All files           |     100 |      100 |     100 |     100 |                   
 footprints         |     100 |      100 |     100 |     100 |                   
  appStoreServer.js |     100 |      100 |     100 |     100 |                   
  ldpServer.js      |     100 |      100 |     100 |     100 |                   
 footprints/util    |     100 |      100 |     100 |     100 |                   
  constants.js      |     100 |      100 |     100 |     100 |                   
  footprint.js      |     100 |      100 |     100 |     100 |                   
--------------------|---------|----------|---------|---------|-------------------
```
