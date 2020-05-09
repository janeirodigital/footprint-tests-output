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
│   ├── httplocalhost12345ghghSchema
│   ├── httplocalhost12345ghghShapeTree
│   ├── httplocalhost12345ghghShapeTreettl
│   ├── httplocalhost12345ghghShapeTreetxt
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
│   ├── _self.ttl
│   ├── ShapeMaps-malformed-shapeTree-nested-two-names
│   │   └── _self.ttl
│   ├── ShapeMaps-missing-shape-property
│   │   └── _self.ttl
│   ├── ShapeMaps-nonconformant-posts
│   │   └── _self.ttl
│   ├── ShapeMaps-nonexistent-shape
│   │   └── _self.ttl
│   ├── ShapeMaps-unGETtable-shape
│   │   └── _self.ttl
│   └── Unmanaged
│       ├── Alice
│       │   └── _self.ttl
│       ├── m33.jpeg
│       └── _self.ttl
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
    │   │   │       └── _self.ttl
    │   │   └── _self.ttl
    │   └── _self.ttl
    └── _self.ttl

78 directories, 113 files
```


## test run output

```

> shape-tree@0.0.0 test:quiet /home/eric/checkouts/shapetrees/test-suite
> npm run prepare-tests && PORT=12345 nyc mocha --slow 300 --reporter mocha-slow-options --reporter-options useReporter=spec,mediumPercent=100 test/*.test.js test/apps/*.test.js


> shape-tree@0.0.0 prepare-tests /home/eric/checkouts/shapetrees/test-suite
> mkdir -p www && ls -d www/* | grep -v README.md | xargs rm -rf



  ✓ LDP server should serve /
  ✓ AppStore server should serve /
  test/local.test.js
    LDP server
      handle POSTs to unmanaged Containers
        create /Data/Unmanaged/
          ✓ should POST /Data/Unmanaged
          ✓ should GET /Data/Unmanaged/
        create /Data/Unmanaged/Alice/
          ✓ should POST /Data/Unmanaged/Alice
          ✓ should GET /Data/Unmanaged/Alice/
        create /Data/Unmanaged/m33.jpeg
          ✓ should POST /Data/Unmanaged/m33.jpeg
          ✓ should GET /Data/Unmanaged/m33.jpeg
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

  test/shape-trees.test.js - installed in Data
    initial state
      ✓ should GET /Data/
      ✓ should !GET /Data/ShapeMaps-nonconformant-POST/
      ✓ should fail to delete /
      ✓ should fail to delete /doesnotexist
    PLANT
      should fail with bad Turtle
        ✓ should PLANT /Data/ShouldNotExist
        ✓ should !GET /Data/ShouldNotExist/
      should fail with bad JSON
        ✓ should PLANT /Data/ShouldNotExist
        ✓ should !GET /Data/ShouldNotExist/
      should fail with bad JSONLD
        ✓ should PLANT /Data/ShouldNotExist
        ✓ should !GET /Data/ShouldNotExist/
      create /Data/ShapeMaps-PUT-tests/
        ✓ should PLANT /Data/ShapeMaps-PUT-tests
        ✓ should GET /Data/ShapeMaps-PUT-tests/
        create /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z
          ✓ should POST /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
          ✓ should GET /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
          ✓ should !GET /Data/ShapeMaps-PUT-tests/Events/19abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
          - successful PUT to replace managed LDPC
          - successful PUT to create managed LDPC
          - successful PUT to replace instance root LDPC
          successful PUT to replace LDPR
            ✓ should PUT /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
            ✓ should GET /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z.ttl
          successful PUT to create LDPR
            ✓ should PUT /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z-new.ttl
            ✓ should GET /Data/ShapeMaps-PUT-tests/Events/09abcdefghijklmnopqrstuvwx_20200107T140000Z-new.ttl
          successful DELETE of LDPR
            ✓ should delete a file
            ✓ successful DELETE of instance root LDPC
    create /Data/ShapeMaps-nonexistent-shape/ hierarchy -- schema does not contain shape
      create /Data/ShapeMaps-nonexistent-shape/
        ✓ should PLANT /Data/ShapeMaps-nonexistent-shape
        ✓ should GET /Data/ShapeMaps-nonexistent-shape/
      create /Data/ShapeMaps-nonexistent-shape/ref-1
        ✓ should POST /Data/ShapeMaps-nonexistent-shape/ref-1.ttl
        ✓ should !GET /Data/ShapeMaps-nonexistent-shape/ref-1.ttl
    create /Data/ShapeMaps-unGETtable-shape/ hierarchy -- can't GET referenced shape
      create /Data/ShapeMaps-unGETtable-shape/
        ✓ should PLANT /Data/ShapeMaps-unGETtable-shape
        ✓ should GET /Data/ShapeMaps-unGETtable-shape/
      create /Data/ShapeMaps-unGETtable-shape/ref-1
        ✓ should POST /Data/ShapeMaps-unGETtable-shape/ref-1.ttl
        ✓ should !GET /Data/ShapeMaps-unGETtable-shape/ref-1.ttl
    create /Data/ShapeMaps-nonconformant-posts/ hierarchy -- POSTed data does not validate
      create /Data/ShapeMaps-nonconformant-posts/
        ✓ should PLANT /Data/ShapeMaps-nonconformant-posts
        ✓ should GET /Data/ShapeMaps-nonconformant-posts/
      create /Data/ShapeMaps-nonconformant-posts/malformed-ref-1 -- Does not match available ShapeTree steps
        ✓ should POST /Data/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
        ✓ should !GET /Data/ShapeMaps-nonconformant-posts/malformed-ref-1.ttl
      create /Data/ShapeMaps-nonconformant-posts/ref-invalid-2 -- misspelled caption property
        ✓ should POST /Data/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
        ✓ should !GET /Data/ShapeMaps-nonconformant-posts/ref-invalid-2.ttl
      create /Data/ShapeMaps-nonconformant-posts/ref-valid-3 -- type link is Container when Resource expected
        ✓ should POST /Data/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
        ✓ should !GET /Data/ShapeMaps-nonconformant-posts/ref-valid-3.ttl
    create /Data/ShapeMaps-malformed-shapeTree-two-names/ hierarchy -- malformed shapeTree: two static names
      create /Data/ShapeMaps-malformed-shapeTree-two-names/
        ✓ should PLANT /Data/ShapeMaps-malformed-shapeTree-two-names
        ✓ should !GET /Data/ShapeMaps-malformed-shapeTree-two-names/
    create /Data/ShapeMaps-malformed-shapeTree-nested-two-names/ hierarchy -- malformed shapeTree: two nested static names
      create /Data/ShapeMaps-malformed-shapeTree-nested-two-names/
        ✓ should PLANT /Data/ShapeMaps-malformed-shapeTree-nested-two-names
        ✓ should GET /Data/ShapeMaps-malformed-shapeTree-nested-two-names/
      create /Data/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1
        ✓ should POST /Data/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
        ✓ should !GET /Data/ShapeMaps-malformed-shapeTree-nested-two-names/ref-1.ttl
    create /Data/ShapeMaps-missing-shape-property/ hierarchy -- shapeTree step has no shape property
      create /Data/ShapeMaps-missing-shape-property/
        ✓ should PLANT /Data/ShapeMaps-missing-shape-property
        ✓ should GET /Data/ShapeMaps-missing-shape-property/
      create /Data/ShapeMaps-missing-shape-property/ref-1
        ✓ should POST /Data/ShapeMaps-missing-shape-property/ref-1.ttl
        ✓ should !GET /Data/ShapeMaps-missing-shape-property/ref-1.ttl

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
    create /Data/Git/users/alice/
      ✓ should POST /Data/Git/users/alice
      ✓ should GET /Data/Git/users/alice/
      ✓ should GET /Data/Git/users/alice/subscriptions/
      ✓ should !GET /Data/Git/users/alice-1/
      create /Data/Git/users/alice/subscriptions/
        ✓ should POST /Data/Git/users/alice/subscriptions/subscr1.ttl
        ✓ should GET /Data/Git/users/alice/subscriptions/subscr1.ttl
    create /Data/Git/users/alice-1/
      ✓ should POST /Data/Git/users/alice
      ✓ should GET /Data/Git/users/alice/
      ✓ should GET /Data/Git/users/alice-1/
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

  test/apps/gh-deep.test.js installed in some/deep/path
    initial state
      ✓ should GET /some/deep/path/
      ✓ should !GET /some/deep/path/Git/
    create /some/deep/path/Git/
      ✓ should PLANT /some/deep/path/Git
      ✓ should GET /some/deep/path/Git/
    create /some/deep/path/Git/users/alice/
      ✓ should POST /some/deep/path/Git/users/alice
      ✓ should GET /some/deep/path/Git/users/alice/
      ✓ should GET /some/deep/path/Git/users/alice/subscriptions/
      ✓ should !GET /some/deep/path/Git/users/alice-1/
      create /some/deep/path/Git/users/alice/subscriptions/
        ✓ should POST /some/deep/path/Git/users/alice/subscriptions/subscr1.ttl
        ✓ should GET /some/deep/path/Git/users/alice/subscriptions/subscr1.ttl
    create /some/deep/path/Git/users/alice-1/
      ✓ should POST /some/deep/path/Git/users/alice
      ✓ should GET /some/deep/path/Git/users/alice/
      ✓ should GET /some/deep/path/Git/users/alice-1/
    create /some/deep/path/Git/repos/ericprud/ hiearchy
      create /some/deep/path/Git/repos/ericprud/
        ✓ should POST /some/deep/path/Git/repos/ericprud
        ✓ should GET /some/deep/path/Git/repos/ericprud/
        ✓ should !GET /some/deep/path/Git/repos/ericprud-1/
        ✓ should !GET /some/deep/path/Git/repos/ericprud/jsg/
      create /some/deep/path/Git/repos/ericprud/jsg/
        ✓ should POST /some/deep/path/Git/repos/ericprud/jsg
        ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/
        ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/issues/
        ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/labels/
        ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/milestones/
        ✓ should !GET /some/deep/path/Git/repos/ericprud/jsg/issues/1.ttl
      create /some/deep/path/Git/repos/ericprud/jsg/issues/1
        ✓ should POST /some/deep/path/Git/repos/ericprud/jsg/issues/1.ttl
        ✓ should GET /some/deep/path/Git/repos/ericprud/jsg/issues/1.ttl
        ✓ should !GET /some/deep/path/Git/repos/ericprud/jsg/issues/2.ttl

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

  test/apps/photoAlbum-shallow.test.js installed in some/deep/path
    initial state
      ✓ should GET /some/deep/path/
      ✓ should !GET /some/deep/path/Albums2019/
    create /some/deep/path/Albums2019/ hierarchy
      create /some/deep/path/Albums2019/
        ✓ should PLANT /some/deep/path/Albums2019
        ✓ should GET /some/deep/path/Albums2019/
      create /some/deep/path/Albums2019/ref-1
        ✓ should POST /some/deep/path/Albums2019/ref-1.ttl
        ✓ should GET /some/deep/path/Albums2019/ref-1.ttl
        ✓ should !GET /some/deep/path/Albums2019/ref-2.ttl


  184 passing (5s)
  3 pending

-------------------------|---------|----------|---------|---------|-------------------
File                     | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
-------------------------|---------|----------|---------|---------|-------------------
All files                |   99.48 |    97.12 |   98.36 |   99.47 |                   
 filesystems             |     100 |      100 |     100 |     100 |                   
  fetch-self-signed.js   |     100 |      100 |     100 |     100 |                   
  fs-promises-utf8.js    |     100 |      100 |     100 |     100 |                   
 servers                 |    98.7 |    93.55 |     100 |   98.67 |                   
  AppStore.js            |     100 |      100 |     100 |     100 |                   
  LDP.js                 |   98.29 |       92 |     100 |   98.26 | 158-160           
 shapetree.js/ecosystems |     100 |      100 |     100 |     100 |                   
  simple-apps.js         |     100 |      100 |     100 |     100 |                   
 shapetree.js/lib        |     100 |      100 |   96.61 |     100 |                   
  prefixes.js            |     100 |      100 |     100 |     100 |                   
  rdf-errors.js          |     100 |      100 |     100 |     100 |                   
  shape-tree.js          |     100 |      100 |   95.83 |     100 |                   
-------------------------|---------|----------|---------|---------|-------------------
```
