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
│   ├── GhFlat
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
│   ├── httplocalhost12345albumPhotoAlbum
│   ├── httplocalhost12345albumPhotoAlbumShapeTree
│   ├── httplocalhost12345badPhotoAlbum
│   ├── httplocalhost12345badPhotoAlbumShapeTree
│   ├── httplocalhost12345badShapeTreeMissingSchema
│   ├── httplocalhost12345badShapeTreeMissingShape
│   ├── httplocalhost12345badShapeTreeNestedTwoStaticNames
│   ├── httplocalhost12345badShapeTreeNoShapeProperty
│   ├── httplocalhost12345badShapeTreeTwoStaticNames
│   ├── httplocalhost12345calCalendar
│   ├── httplocalhost12345calCalendarShapeTree
│   ├── httplocalhost12345calGoogleCalendar
│   ├── httplocalhost12345calGoogleShapeTree
│   ├── httplocalhost12345gh-deepgh-deep-Schema
│   ├── httplocalhost12345gh-deepgh-deep-ShapeTree
│   ├── httplocalhost12345gh-deepgh-deep-ShapeTreettl
│   ├── httplocalhost12345gh-deepgh-deep-ShapeTreetxt
│   ├── httplocalhost12345gh-flatgh-flat-Schema
│   ├── httplocalhost12345gh-flatgh-flat-ShapeTree
│   ├── httplocalhost12345nevernoteNeverNote
│   ├── httplocalhost12345nevernoteNeverNoteShapeTree
│   ├── httplocalhost12345photoPhotoShapeTree
│   └── _self.ttl
├── Data
│   ├── Albums2019
│   │   ├── ref-1.ttl
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
│   │       ├── ericprud
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
│   │       └── _self.ttl
│   ├── Git-Comments
│   │   └── _self.ttl
│   ├── Git-Events
│   │   └── _self.ttl
│   ├── Git-Issues
│   │   ├── issue1.ttl
│   │   └── _self.ttl
│   ├── Git-Labels
│   │   └── _self.ttl
│   ├── Git-Milestones
│   │   └── _self.ttl
│   ├── Git-Orgs
│   │   ├── _self.ttl
│   │   └── shapetrees.ttl
│   ├── Git-Repos
│   │   ├── jsg.ttl
│   │   ├── libxml-annot.ttl
│   │   ├── _self.ttl
│   │   └── shapetree.js.ttl
│   ├── Git-Users
│   │   ├── ericprud.ttl
│   │   └── _self.ttl
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
├── no-slug
│   ├── Container
│   │   ├── repos
│   │   │   └── _self.ttl
│   │   ├── _self.ttl
│   │   └── users
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
│   └── _self.ttl
├── README.md
├── _self.ttl
└── shape-trees.test
    ├── _self.ttl
    ├── ShapeMaps-malformed-shapeTree-nested-two-names
    │   └── _self.ttl
    ├── ShapeMaps-missing-shape-property
    │   └── _self.ttl
    ├── ShapeMaps-nonconformant-posts
    │   └── _self.ttl
    ├── ShapeMaps-nonexistent-shape
    │   └── _self.ttl
    ├── ShapeMaps-unGETtable-shape
    │   └── _self.ttl
    ├── some
    │   ├── deep
    │   │   ├── path
    │   │   │   ├── _self.ttl
    │   │   │   ├── ShapeMaps-malformed-shapeTree-nested-two-names
    │   │   │   │   └── _self.ttl
    │   │   │   ├── ShapeMaps-missing-shape-property
    │   │   │   │   └── _self.ttl
    │   │   │   ├── ShapeMaps-nonconformant-posts
    │   │   │   │   └── _self.ttl
    │   │   │   ├── ShapeMaps-nonexistent-shape
    │   │   │   │   └── _self.ttl
    │   │   │   ├── ShapeMaps-unGETtable-shape
    │   │   │   │   └── _self.ttl
    │   │   │   └── Unmanaged
    │   │   │       ├── Ericprud
    │   │   │       │   └── _self.ttl
    │   │   │       ├── issues
    │   │   │       │   ├── 1.ttl
    │   │   │       │   └── _self.ttl
    │   │   │       ├── m33.jpeg
    │   │   │       └── _self.ttl
    │   │   └── _self.ttl
    │   └── _self.ttl
    └── Unmanaged
        ├── Ericprud
        │   └── _self.ttl
        ├── issues
        │   ├── 1.ttl
        │   └── _self.ttl
        ├── m33.jpeg
        └── _self.ttl

70 directories, 113 files
```


## test run output

```

> shape-tree@0.0.0 test:quiet /home/eric/checkouts/shapetrees/test-suite
> npm run prepare-tests && npm run test:client-silent && npm run prepare-tests && npm run test:server-no-clean


> shape-tree@0.0.0 prepare-tests /home/eric/checkouts/shapetrees/test-suite
> mkdir -p www && ls -d www/* | grep -v README.md | xargs rm -rf


> shape-tree@0.0.0 test:client-silent /home/eric/checkouts/shapetrees/test-suite
> SHAPETREE=fetch PORT=12345 nyc --silent mocha --slow 1000 --reporter mocha-slow-options --reporter-options useReporter=spec,mediumPercent=100 test/shape-trees.test.js



  test/shape-trees.test.js - installed in shape-trees.test
    initial state
      ✓ should GET /shape-trees.test/
      ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-POST/
      ✓ should fail to delete /
      ✓ should fail to delete /doesnotexist
    PLANT
      should fail with bad Turtle
        ✓ should !PLANT /shape-trees.test/ShouldNotExist
        ✓ should !GET /shape-trees.test/ShouldNotExist/
      should fail with bad JSON
        ✓ should !PLANT /shape-trees.test/ShouldNotExist
        ✓ should !GET /shape-trees.test/ShouldNotExist/
      should fail with bad JSONLD
        ✓ should !PLANT /shape-trees.test/ShouldNotExist
        ✓ should !GET /shape-trees.test/ShouldNotExist/
      PUT tests
        plant /shape-trees.test/ShapeMaps-PUT-tests/
          ✓ should PLANT /shape-trees.test/ShapeMaps-PUT-tests
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/
        post /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
          ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
          ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud-1/
          post /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
        post /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud-1/
          ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud-1/
        create /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/ hiearchy
          - successful PUT to replace instance root LDPC
          post /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud-1/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          post /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/labels/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/milestones/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          post /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/2.ttl
          successful PUT to replace managed LDPR
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          successful PUT to create managed LDPR
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
          successful PUT to replace managed LDPC
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          successful PUT to create managed LDPC
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/labels/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/milestones/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/1.ttl
          handle POSTs to unmanaged Containers
            post /shape-trees.test/Unmanaged/
              ✓ should POST /shape-trees.test/Unmanaged
              ✓ should GET /shape-trees.test/Unmanaged/
            post /shape-trees.test/Unmanaged/Ericprud/
              ✓ should POST /shape-trees.test/Unmanaged/Ericprud
              ✓ should GET /shape-trees.test/Unmanaged/Ericprud/
            post /shape-trees.test/Unmanaged/m33.jpeg
              ✓ should POST /shape-trees.test/Unmanaged/m33.jpeg
              ✓ should GET /shape-trees.test/Unmanaged/m33.jpeg
          handle PUTs to unmanaged Containers
            successful PUT to create unmanaged LDPC
              ✓ should PUT /shape-trees.test/Unmanaged/issues/
              ✓ should GET /shape-trees.test/Unmanaged/issues/
            successful PUT to replace unmanaged LDPC
              ✓ should PUT /shape-trees.test/Unmanaged/issues/
              ✓ should GET /shape-trees.test/Unmanaged/issues/
            successful PUT to create unmanaged LDPR
              ✓ should PUT /shape-trees.test/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/Unmanaged/issues/1.ttl
            successful PUT to replace unmanaged LDPR
              ✓ should PUT /shape-trees.test/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/Unmanaged/issues/1.ttl
          successful DELETE of LDPR
            ✓ should delete a file
            ✓ successful DELETE of instance root LDPC
    create /shape-trees.test/ShapeMaps-nonexistent-shape/ hierarchy -- schema does not contain shape
      plant /shape-trees.test/ShapeMaps-nonexistent-shape/
        ✓ should PLANT /shape-trees.test/ShapeMaps-nonexistent-shape
        ✓ should GET /shape-trees.test/ShapeMaps-nonexistent-shape/
      post /shape-trees.test/ShapeMaps-nonexistent-shape/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-nonexistent-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonexistent-shape/ref-1.ttl
    create /shape-trees.test/ShapeMaps-unGETtable-shape/ hierarchy -- can't GET referenced shape
      plant /shape-trees.test/ShapeMaps-unGETtable-shape/
        ✓ should PLANT /shape-trees.test/ShapeMaps-unGETtable-shape
        ✓ should GET /shape-trees.test/ShapeMaps-unGETtable-shape/
      post /shape-trees.test/ShapeMaps-unGETtable-shape/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-unGETtable-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-unGETtable-shape/ref-1.ttl
    create /shape-trees.test/ShapeMaps-nonconformant-posts/ hierarchy -- POSTed data does not validate
      plant /shape-trees.test/ShapeMaps-nonconformant-posts/
        ✓ should PLANT /shape-trees.test/ShapeMaps-nonconformant-posts
        ✓ should GET /shape-trees.test/ShapeMaps-nonconformant-posts/
      post /shape-trees.test/ShapeMaps-nonconformant-posts/malformed-ref-1 -- Does not match available ShapeTree steps
        ✓ should !POST /shape-trees.test/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
      post /shape-trees.test/ShapeMaps-nonconformant-posts/ref-invalid-2 -- misspelled caption property
        ✓ should !POST /shape-trees.test/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
      post /shape-trees.test/ShapeMaps-nonconformant-posts/ref-valid-3 -- type link is Container when Resource expected
        ✓ should !POST /shape-trees.test/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
    create /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names/ hierarchy -- malformed shapeTree: two static names
      plant /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names/
        ✓ should !PLANT /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names
        ✓ should !GET /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names/
    create /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ hierarchy -- malformed shapeTree: two nested static names
      plant /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/
        ✓ should PLANT /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names
        ✓ should GET /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/
      post /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
    create /shape-trees.test/ShapeMaps-missing-shape-property/ hierarchy -- shapeTree step has no shape property
      plant /shape-trees.test/ShapeMaps-missing-shape-property/
        ✓ should PLANT /shape-trees.test/ShapeMaps-missing-shape-property
        ✓ should GET /shape-trees.test/ShapeMaps-missing-shape-property/
      post /shape-trees.test/ShapeMaps-missing-shape-property/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-missing-shape-property/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-missing-shape-property/ref-1.ttl

  test/shape-trees.test.js - installed in shape-trees.test/some/deep/path
    initial state
      ✓ should GET /shape-trees.test/some/deep/path/
      ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-POST/
      ✓ should fail to delete /
      ✓ should fail to delete /doesnotexist
    PLANT
      should fail with bad Turtle
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShouldNotExist
        ✓ should !GET /shape-trees.test/some/deep/path/ShouldNotExist/
      should fail with bad JSON
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShouldNotExist
        ✓ should !GET /shape-trees.test/some/deep/path/ShouldNotExist/
      should fail with bad JSONLD
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShouldNotExist
        ✓ should !GET /shape-trees.test/some/deep/path/ShouldNotExist/
      PUT tests
        plant /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/
          ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/
        post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
          ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
          ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud-1/
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
        post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud-1/
          ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud-1/
        create /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/ hiearchy
          - successful PUT to replace instance root LDPC
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud-1/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/labels/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/milestones/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/2.ttl
          successful PUT to replace managed LDPR
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          successful PUT to create managed LDPR
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
          successful PUT to replace managed LDPC
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          successful PUT to create managed LDPC
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/labels/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/milestones/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/1.ttl
          handle POSTs to unmanaged Containers
            post /shape-trees.test/some/deep/path/Unmanaged/
              ✓ should POST /shape-trees.test/some/deep/path/Unmanaged
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/
            post /shape-trees.test/some/deep/path/Unmanaged/Ericprud/
              ✓ should POST /shape-trees.test/some/deep/path/Unmanaged/Ericprud
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/Ericprud/
            post /shape-trees.test/some/deep/path/Unmanaged/m33.jpeg
              ✓ should POST /shape-trees.test/some/deep/path/Unmanaged/m33.jpeg
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/m33.jpeg
          handle PUTs to unmanaged Containers
            successful PUT to create unmanaged LDPC
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/
            successful PUT to replace unmanaged LDPC
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/
            successful PUT to create unmanaged LDPR
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
            successful PUT to replace unmanaged LDPR
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
          successful DELETE of LDPR
            ✓ should delete a file
            ✓ successful DELETE of instance root LDPC
    create /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ hierarchy -- schema does not contain shape
      plant /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/
      post /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ref-1.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ hierarchy -- can't GET referenced shape
      plant /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/
      post /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ref-1.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ hierarchy -- POSTed data does not validate
      plant /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/
      post /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/malformed-ref-1 -- Does not match available ShapeTree steps
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
      post /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-invalid-2 -- misspelled caption property
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
      post /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-valid-3 -- type link is Container when Resource expected
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names/ hierarchy -- malformed shapeTree: two static names
      plant /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names/
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names/
    create /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ hierarchy -- malformed shapeTree: two nested static names
      plant /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/
      post /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ hierarchy -- shapeTree step has no shape property
      plant /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/
      post /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ref-1.ttl


  178 passing (18s)
  2 pending


> shape-tree@0.0.0 prepare-tests /home/eric/checkouts/shapetrees/test-suite
> mkdir -p www && ls -d www/* | grep -v README.md | xargs rm -rf


> shape-tree@0.0.0 test:server-no-clean /home/eric/checkouts/shapetrees/test-suite
> PORT=12345 nyc --no-clean mocha --slow 300 --reporter mocha-slow-options --reporter-options useReporter=spec,mediumPercent=100 test/*.test.js test/apps/*.test.js



  ✓ LDP server should serve /
  ✓ AppStore server should serve /
  test/local.test.js
    LDP server
      ✓ should return on empty path
    AppStore server
      ✓ should return on empty path
      ✓ should resolve full path
    ShapeTree.local
      ✓ should throw if not passed a URL
    ShapeTree.ManagedContainer
      ✓ should throw if not passed a Container URL
      ✓ should throw if the Container URL doesn't end with '/'
      ✓ should throw if the Container URL ends with '//'
      ✓ should throw if the shapeTree parameter isn't a URL
      ✓ should remove a Container directory
      ✓ should fail on an invalid shapeTree graph
    ShapeTree.remote
      ✓ should throw if not passed a URL
      ✓ should throw on a GET failure
      ✓ should parse turtle
      ✓ should throw on bad media type
    ShapeTree.validate
      ✓ should throw if shapeTree step is missing a shape
      ✓ should throw on malformed POST Turtle body
      ✓ should throw on malformed POST JSON-LD body
    ShapeTree misc
      ✓ should construct all errors
      ✓ should render RDFJS nodes
    PLANT
      ✓ should fail with bad Turtle
      ✓ should fail with bad JSON
      ✓ should fail with bad JSONLD
      ✓ should create a novel directory
      ✓ should delete the parent directory
    handle PLANTs and POSTs with no Slug header
      create /no-slug/Container/
        ✓ should PLANT /no-slug/-TBD-
        ✓ should GET /no-slug/Container/
      re-create /no-slug/Container/
        ✓ should PLANT /no-slug/999
        ✓ should !GET /no-slug/999/
      create /no-slug/Container/users/Container/
        ✓ should POST /no-slug/Container/users/-TBD-
        ✓ should GET /no-slug/Container/users/Container/

  test/shape-trees.test.js - installed in shape-trees.test
    initial state
      ✓ should GET /shape-trees.test/
      ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-POST/
      ✓ should fail to delete /
      ✓ should fail to delete /doesnotexist
    PLANT
      should fail with bad Turtle
        ✓ should !PLANT /shape-trees.test/ShouldNotExist
        ✓ should !GET /shape-trees.test/ShouldNotExist/
      should fail with bad JSON
        ✓ should !PLANT /shape-trees.test/ShouldNotExist
        ✓ should !GET /shape-trees.test/ShouldNotExist/
      should fail with bad JSONLD
        ✓ should !PLANT /shape-trees.test/ShouldNotExist
        ✓ should !GET /shape-trees.test/ShouldNotExist/
      PUT tests
        plant /shape-trees.test/ShapeMaps-PUT-tests/
          ✓ should PLANT /shape-trees.test/ShapeMaps-PUT-tests
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/
        post /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
          ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
          ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud-1/
          post /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
        post /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud-1/
          ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/users/ericprud-1/
        create /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/ hiearchy
          - successful PUT to replace instance root LDPC
          post /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud-1/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          post /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/labels/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/milestones/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          post /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should POST /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/2.ttl
          successful PUT to replace managed LDPR
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          successful PUT to create managed LDPR
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
          successful PUT to replace managed LDPC
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          successful PUT to create managed LDPC
            ✓ should PUT /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/labels/
            ✓ should GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/milestones/
            ✓ should !GET /shape-trees.test/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/1.ttl
          handle POSTs to unmanaged Containers
            post /shape-trees.test/Unmanaged/
              ✓ should POST /shape-trees.test/Unmanaged
              ✓ should GET /shape-trees.test/Unmanaged/
            post /shape-trees.test/Unmanaged/Ericprud/
              ✓ should POST /shape-trees.test/Unmanaged/Ericprud
              ✓ should GET /shape-trees.test/Unmanaged/Ericprud/
            post /shape-trees.test/Unmanaged/m33.jpeg
              ✓ should POST /shape-trees.test/Unmanaged/m33.jpeg
              ✓ should GET /shape-trees.test/Unmanaged/m33.jpeg
          handle PUTs to unmanaged Containers
            successful PUT to create unmanaged LDPC
              ✓ should PUT /shape-trees.test/Unmanaged/issues/
              ✓ should GET /shape-trees.test/Unmanaged/issues/
            successful PUT to replace unmanaged LDPC
              ✓ should PUT /shape-trees.test/Unmanaged/issues/
              ✓ should GET /shape-trees.test/Unmanaged/issues/
            successful PUT to create unmanaged LDPR
              ✓ should PUT /shape-trees.test/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/Unmanaged/issues/1.ttl
            successful PUT to replace unmanaged LDPR
              ✓ should PUT /shape-trees.test/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/Unmanaged/issues/1.ttl
          successful DELETE of LDPR
            ✓ should delete a file
            ✓ successful DELETE of instance root LDPC
    create /shape-trees.test/ShapeMaps-nonexistent-shape/ hierarchy -- schema does not contain shape
      plant /shape-trees.test/ShapeMaps-nonexistent-shape/
        ✓ should PLANT /shape-trees.test/ShapeMaps-nonexistent-shape
        ✓ should GET /shape-trees.test/ShapeMaps-nonexistent-shape/
      post /shape-trees.test/ShapeMaps-nonexistent-shape/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-nonexistent-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonexistent-shape/ref-1.ttl
    create /shape-trees.test/ShapeMaps-unGETtable-shape/ hierarchy -- can't GET referenced shape
      plant /shape-trees.test/ShapeMaps-unGETtable-shape/
        ✓ should PLANT /shape-trees.test/ShapeMaps-unGETtable-shape
        ✓ should GET /shape-trees.test/ShapeMaps-unGETtable-shape/
      post /shape-trees.test/ShapeMaps-unGETtable-shape/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-unGETtable-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-unGETtable-shape/ref-1.ttl
    create /shape-trees.test/ShapeMaps-nonconformant-posts/ hierarchy -- POSTed data does not validate
      plant /shape-trees.test/ShapeMaps-nonconformant-posts/
        ✓ should PLANT /shape-trees.test/ShapeMaps-nonconformant-posts
        ✓ should GET /shape-trees.test/ShapeMaps-nonconformant-posts/
      post /shape-trees.test/ShapeMaps-nonconformant-posts/malformed-ref-1 -- Does not match available ShapeTree steps
        ✓ should !POST /shape-trees.test/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
      post /shape-trees.test/ShapeMaps-nonconformant-posts/ref-invalid-2 -- misspelled caption property
        ✓ should !POST /shape-trees.test/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
      post /shape-trees.test/ShapeMaps-nonconformant-posts/ref-valid-3 -- type link is Container when Resource expected
        ✓ should !POST /shape-trees.test/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
    create /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names/ hierarchy -- malformed shapeTree: two static names
      plant /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names/
        ✓ should !PLANT /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names
        ✓ should !GET /shape-trees.test/ShapeMaps-malformed-shapeTree-two-names/
    create /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ hierarchy -- malformed shapeTree: two nested static names
      plant /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/
        ✓ should PLANT /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names
        ✓ should GET /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/
      post /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
    create /shape-trees.test/ShapeMaps-missing-shape-property/ hierarchy -- shapeTree step has no shape property
      plant /shape-trees.test/ShapeMaps-missing-shape-property/
        ✓ should PLANT /shape-trees.test/ShapeMaps-missing-shape-property
        ✓ should GET /shape-trees.test/ShapeMaps-missing-shape-property/
      post /shape-trees.test/ShapeMaps-missing-shape-property/ref-1
        ✓ should !POST /shape-trees.test/ShapeMaps-missing-shape-property/ref-1.ttl
        ✓ should !GET /shape-trees.test/ShapeMaps-missing-shape-property/ref-1.ttl

  test/shape-trees.test.js - installed in shape-trees.test/some/deep/path
    initial state
      ✓ should GET /shape-trees.test/some/deep/path/
      ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-POST/
      ✓ should fail to delete /
      ✓ should fail to delete /doesnotexist
    PLANT
      should fail with bad Turtle
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShouldNotExist
        ✓ should !GET /shape-trees.test/some/deep/path/ShouldNotExist/
      should fail with bad JSON
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShouldNotExist
        ✓ should !GET /shape-trees.test/some/deep/path/ShouldNotExist/
      should fail with bad JSONLD
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShouldNotExist
        ✓ should !GET /shape-trees.test/some/deep/path/ShouldNotExist/
      PUT tests
        plant /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/
          ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/
        post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
          ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
          ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud-1/
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/subscriptions/subscr1.ttl
        post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud-1/
          ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud/
          ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/users/ericprud-1/
        create /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/ hiearchy
          - successful PUT to replace instance root LDPC
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud-1/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/labels/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/milestones/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          post /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should POST /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/2.ttl
          successful PUT to replace managed LDPR
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1.ttl
          successful PUT to create managed LDPR
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/issues/1-new.ttl
          successful PUT to replace managed LDPC
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg/
          successful PUT to create managed LDPC
            ✓ should PUT /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/labels/
            ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/milestones/
            ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-PUT-tests/repos/ericprud/jsg-put/issues/1.ttl
          handle POSTs to unmanaged Containers
            post /shape-trees.test/some/deep/path/Unmanaged/
              ✓ should POST /shape-trees.test/some/deep/path/Unmanaged
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/
            post /shape-trees.test/some/deep/path/Unmanaged/Ericprud/
              ✓ should POST /shape-trees.test/some/deep/path/Unmanaged/Ericprud
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/Ericprud/
            post /shape-trees.test/some/deep/path/Unmanaged/m33.jpeg
              ✓ should POST /shape-trees.test/some/deep/path/Unmanaged/m33.jpeg
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/m33.jpeg
          handle PUTs to unmanaged Containers
            successful PUT to create unmanaged LDPC
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/
            successful PUT to replace unmanaged LDPC
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/
            successful PUT to create unmanaged LDPR
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
            successful PUT to replace unmanaged LDPR
              ✓ should PUT /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
              ✓ should GET /shape-trees.test/some/deep/path/Unmanaged/issues/1.ttl
          successful DELETE of LDPR
            ✓ should delete a file
            ✓ successful DELETE of instance root LDPC
    create /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ hierarchy -- schema does not contain shape
      plant /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/
      post /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonexistent-shape/ref-1.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ hierarchy -- can't GET referenced shape
      plant /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/
      post /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-unGETtable-shape/ref-1.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ hierarchy -- POSTed data does not validate
      plant /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/
      post /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/malformed-ref-1 -- Does not match available ShapeTree steps
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
      post /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-invalid-2 -- misspelled caption property
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
      post /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-valid-3 -- type link is Container when Resource expected
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names/ hierarchy -- malformed shapeTree: two static names
      plant /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names/
        ✓ should !PLANT /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-two-names/
    create /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ hierarchy -- malformed shapeTree: two nested static names
      plant /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/
      post /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
    create /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ hierarchy -- shapeTree step has no shape property
      plant /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/
        ✓ should PLANT /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property
        ✓ should GET /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/
      post /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ref-1
        ✓ should !POST /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ref-1.ttl
        ✓ should !GET /shape-trees.test/some/deep/path/ShapeMaps-missing-shape-property/ref-1.ttl

  test/apps/cal.test.js installed in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/Calendar/
    create /Data/Calendar/ hierarchy
      create /Data/Calendar/
        ✓ should PLANT /Data/Calendar
        ✓ should PLANT /Data/Google
        ✓ should GET /Data/Calendar/
      create /Data/Calendar/event1
        ✓ should POST /Data/Calendar/event1.ttl
        ✓ should GET /Data/Calendar/event1.ttl
        ✓ should !GET /Data/Calendar/event2.ttl
      create /Data/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z
        ✓ should POST /Data/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
        ✓ should GET /Data/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
        ✓ should !GET /Data/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
      create /Data/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z
        ✓ should POST /Data/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
        ✓ should GET /Data/Google/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
        ✓ should GET /Data/Google/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl

  test/apps/gh-deep.test.js installed in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/Git/
    create /Data/Git/
      ✓ should PLANT /Data/Git
      ✓ should GET /Data/Git/
    create /Data/Git/users/ericprud/
      ✓ should POST /Data/Git/users/ericprud
      ✓ should GET /Data/Git/users/ericprud/
      ✓ should GET /Data/Git/users/ericprud/subscriptions/
      ✓ should !GET /Data/Git/users/ericprud/subscriptions/subscr1.ttl
      ✓ should !GET /Data/Git/users/ericprud-1/
      create /Data/Git/users/ericprud/subscriptions/
        ✓ should POST /Data/Git/users/ericprud/subscriptions/subscr1.ttl
        ✓ should GET /Data/Git/users/ericprud/subscriptions/subscr1.ttl
    create /Data/Git/repos/ericprud/ hiearchy
      create /Data/Git/repos/ericprud/
        ✓ should POST /Data/Git/repos/ericprud
        ✓ should GET /Data/Git/repos/ericprud/
        ✓ should !GET /Data/Git/repos/ericprud-1/
        ✓ should !GET /Data/Git/repos/ericprud/jsg/
      create /Data/Git/repos/ericprud/jsg/
        ✓ should POST /Data/Git/repos/ericprud/jsg
        ✓ should GET /Data/Git/repos/ericprud/jsg/
        ✓ should GET /Data/Git/repos/ericprud/jsg/issues/
        ✓ should GET /Data/Git/repos/ericprud/jsg/labels/
        ✓ should GET /Data/Git/repos/ericprud/jsg/milestones/
        ✓ should !GET /Data/Git/repos/ericprud/jsg/issues/1.ttl
      create /Data/Git/repos/ericprud/jsg/issues/1
        ✓ should POST /Data/Git/repos/ericprud/jsg/issues/1.ttl
        ✓ should GET /Data/Git/repos/ericprud/jsg/issues/1.ttl
        ✓ should !GET /Data/Git/repos/ericprud/jsg/issues/2.ttl

  test/apps/gh-flat.test.js installed in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/GitFlat/
    create /Data/Git-Orgs/
      ✓ should PLANT /Data/Git-Orgs
      ✓ should GET /Data/Git-Orgs/
    create /Data/Git-Users/
      ✓ should PLANT /Data/Git-Users
      ✓ should GET /Data/Git-Users/
    create /Data/Git-Repos/
      ✓ should PLANT /Data/Git-Repos
      ✓ should GET /Data/Git-Repos/
    create /Data/Git-Issues/
      ✓ should PLANT /Data/Git-Issues
      ✓ should GET /Data/Git-Issues/
    create /Data/Git-Comments/
      ✓ should PLANT /Data/Git-Comments
      ✓ should GET /Data/Git-Comments/
    create /Data/Git-Events/
      ✓ should PLANT /Data/Git-Events
      ✓ should GET /Data/Git-Events/
    create /Data/Git-Labels/
      ✓ should PLANT /Data/Git-Labels
      ✓ should GET /Data/Git-Labels/
    create /Data/Git-Milestones/
      ✓ should PLANT /Data/Git-Milestones
      ✓ should GET /Data/Git-Milestones/
    create /Data/Git-Orgs/shapetrees.ttl
      ✓ should POST /Data/Git-Orgs/shapetrees.ttl
      ✓ should GET /Data/Git-Orgs/shapetrees.ttl
      ✓ should !GET /Data/Git-Orgs/shapetrees-1.ttl
    create /Data/Git-Users/ericprud.ttl
      ✓ should POST /Data/Git-Users/ericprud.ttl
      ✓ should GET /Data/Git-Users/ericprud.ttl
      ✓ should !GET /Data/Git-Users/ericprud-1.ttl
    create /Data/Git-Repos/ members
      create /Data/Git-Repos/shapetree.js
        ✓ should POST /Data/Git-Repos/shapetree.js.ttl
        ✓ should GET /Data/Git-Repos/shapetree.js.ttl
        ✓ should !GET /Data/Git-Repos/shapetree.js-1.ttl
        add shapetree.js repository to /Data/Git-Orgs/shapetrees
          ✓ should PATCH /Data/Git-Orgs/shapetrees.ttl
          ✓ should GET /Data/Git-Orgs/shapetrees.ttl
      create /Data/Git-Repos/jsg/
        ✓ should POST /Data/Git-Repos/jsg.ttl
        ✓ should GET /Data/Git-Repos/jsg.ttl
        ✓ should !GET /Data/Git-Issues/1.ttl
        add jsg repository to /Data/Git-Users/ericprud
          ✓ should PATCH /Data/Git-Users/ericprud.ttl
          ✓ should GET /Data/Git-Users/ericprud.ttl
        add jsg subscription to /Data/Git-Users/ericprud
          ✓ should PATCH /Data/Git-Users/ericprud.ttl
          ✓ should GET /Data/Git-Users/ericprud.ttl
      create /Data/Git-Repos/libxml-annot/
        ✓ should POST /Data/Git-Repos/libxml-annot.ttl
        ✓ should GET /Data/Git-Repos/libxml-annot.ttl
        ✓ should !GET /Data/Git-Issues/1.ttl
        add libxml-annot repository to /Data/Git-Users/ericprud
          ✓ should PATCH /Data/Git-Users/ericprud.ttl
          ✓ should GET /Data/Git-Users/ericprud.ttl
      create /Data/Git-Issues/issue1
        ✓ should POST /Data/Git-Issues/issue1.ttl
        ✓ should GET /Data/Git-Issues/issue1.ttl
        ✓ should !GET /Data/Git-Issues/issue2.ttl
        add issue issue1 to /Data/Git-Users/ericprud
          ✓ should PATCH /Data/Git-Users/ericprud.ttl
          ✓ should GET /Data/Git-Users/ericprud.ttl
    shapetree navigation
      ✓ should traverse shapetree references (walkReferencedTrees)
      ✓ should traverse referenced shapetree instance members (walkReferencedResources(start))

  test/apps/nevernote.test.js installid in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/NeverNotes/
    create /Data/NeverNotes/ hierarchy
      create /Data/NeverNotes/
        ✓ should PLANT /Data/NeverNotes
        ✓ should GET /Data/NeverNotes/
      create /Data/NeverNotes/note1/
        ✓ should POST /Data/NeverNotes/note1
        ✓ should GET /Data/NeverNotes/note1/
        ✓ should !GET /Data/NeverNotes/note2/
        ✓ should !GET /Data/NeverNotes/note1/img-M33_IR.jpg
        ✓ should !GET /Data/NeverNotes/note1/inc-M33_IR.ttl
      create /Data/NeverNotes/note1/img-M33_IR.jpg
        ✓ should POST /Data/NeverNotes/note1/img-M33_IR.jpg
        ✓ should GET /Data/NeverNotes/note1/img-M33_IR.jpg
      create /Data/NeverNotes/note1/inc-M33_IR.ttl
        ✓ should POST /Data/NeverNotes/note1/inc-M33_IR.ttl
        ✓ should GET /Data/NeverNotes/note1/inc-M33_IR.ttl

  test/apps/photo.test.js installid in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/Photos2020-01/
    create /Data/Photos2020-01/ hierarchy
      create /Data/Photos2020-01/
        ✓ should PLANT /Data/Photos2020-01
        ✓ should GET /Data/Photos2020-01/
      create /Data/Photos2020-01/m33
        ✓ should POST /Data/Photos2020-01/m33.jpeg
        ✓ should GET /Data/Photos2020-01/m33.jpeg
        ✓ should !GET /Data/Photos2020-01/m32.jpeg

  test/apps/photoAlbum-shallow.test.js installed in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/Albums2019/
    create /Data/Albums2019/ hierarchy
      create /Data/Albums2019/
        ✓ should PLANT /Data/Albums2019
        ✓ should GET /Data/Albums2019/
      create /Data/Albums2019/ref-1
        ✓ should POST /Data/Albums2019/ref-1.ttl
        ✓ should GET /Data/Albums2019/ref-1.ttl
        ✓ should !GET /Data/Albums2019/ref-2.ttl


  323 passing (7s)
  2 pending

-------------------------|---------|----------|---------|---------|---------------------------------
File                     | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s               
-------------------------|---------|----------|---------|---------|---------------------------------
All files                |   96.15 |    90.51 |   95.03 |   96.25 |                                 
 servers                 |   98.84 |    94.05 |   95.45 |   98.82 |                                 
  AppStore.js            |     100 |      100 |     100 |     100 |                                 
  LDP.js                 |   98.53 |    93.06 |   92.31 |    98.5 | 227,232,245                     
 shapetree.js/ecosystems |     100 |      100 |     100 |     100 |                                 
  simple-apps.js         |     100 |      100 |     100 |     100 |                                 
 shapetree.js/lib        |   98.22 |    93.53 |   96.77 |   98.18 |                                 
  mutex.js               |     100 |      100 |     100 |     100 |                                 
  prefixes.js            |     100 |      100 |     100 |     100 |                                 
  rdf-errors.js          |     100 |      100 |     100 |     100 |                                 
  shape-tree-fetch.js    |   93.28 |    81.63 |   92.31 |   93.18 | 68,150,154,166,167,188-190,229  
  shape-tree.js          |     100 |      100 |   96.83 |     100 |                                 
 shapetree.js/storage    |   86.06 |    73.33 |   89.13 |    86.7 |                                 
  fetch-self-signed.js   |     100 |      100 |     100 |     100 |                                 
  fs-promises.js         |   97.03 |       84 |    96.3 |   97.94 | 18,245                          
  ldp-proxy.js           |   74.51 |    52.94 |   76.47 |   75.25 | ...,198,200,218,220,221,263,284 
-------------------------|---------|----------|---------|---------|---------------------------------
```
