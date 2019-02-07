Java Docker image
This image is based on Alpine Linux image, which is only a 5MB image, and contains Java runtime (JRE) and Java development kit (JDK) conveniently packaged into separate Docker tags.

You must accept the Oracle Binary Code License Agreement for Java SE to use this image (see issue #6 for details).

JDK bundle contains lots of unnecessary for Docker image stuff, so it was cleaned up. There are 3 tags: *-full (only src tarballs get removed), *-cleaned (desktop parts get cleaned), *-slim (everything but compiler and jvm is removed). master branch refers to jdk8-slim tag, but latest tag points to jdk8-cleaned.
