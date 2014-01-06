
Clone of [Box2D](http://www.box2d.org), stripped of anything other than library code. Includes an Xcode project to build as a static library for iOS, and can be used as a git submodule.

Box2D is a 2D physics engine for games, created by Erin Catto. For help with Box2D, please visit http://www.box2d.org. There is a forum there where you may post your questions.

####Version History (From Erin Catto)

2.3.0
* Polygon creation now computes the convex hull. Vertices no longer need to be ordered.
* The convex hull code will merge vertices closer than dm_linearSlop. This may lead to failure on very small polygons.
* Added b2MotorJoint.
* Bug fixes.