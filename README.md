Demo required to be able to customize the psvita.

* Original download demo url [http://ares.dl.playstation.net](http://ares.dl.playstation.net/cdn/JP0741/PCSG90096_00/xGMrXOkORxWRyqzLMihZPqsXAbAXLzvAdJFqtPJLAZTgOcqJobxQAhLNbgiFydVlcmVOrpZKklOYxizQCRpiLfjeROuWivGXfwgkq.pkg)

### **Downloaded demo and Splitter on Tar**:

* **split**
 ```sh
  split -b 99MB xGMrXOkORxWRyqzLMihZPqsXAbAXLzvAdJFqtPJLAZTgOcqJobxQAhLNbgiFydVlcmVOrpZKklOYxizQCRpiLfjeROuWivGXfwgkq.tar.xz "bitter.smile.pkg.part-"
  ```

* **merge**
 ```sh
  cat bitter.smile.pkg.part-* > merge.tar.gz
  ```

* **extract**

```sh
  tar -xzvf merge.tar.gz
  ```