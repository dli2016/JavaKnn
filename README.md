# JavaKnn
KNN search using flann in JavaCV.

References:
https://github.com/bytedeco/javacv/blob/master/src/main/java/org/bytedeco/javacv/ObjectFinder.java
https://searchcode.com/codesearch/view/92290750/
http://docs.opencv.org/2.4/modules/flann/doc/flann_fast_approximate_nearest_neighbor_search.html#flann-index-t-knnsearch

Compile:
mvn package -Dmaven.test.skip.exec

Run:
mvn exec:java -Dexec.mainClass="org.cripac.isee.knn.JavaKnn"
