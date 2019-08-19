# Naming
 * `my` for instance class fields
 * `our` for static class fields
  ```java
  public class SomeClass 
  {
    public static final ourMaxValue = 100;
    
    private int myIntValue;
  }
  ```
 * class instance field 
   * **static** + **final**
   * `INSTANCE` name
  ```java
  public class Service
  {
    public static final Service INSTANCE = new Service();
  }
  ```
 * logging field
   * **static** + **final**
   * `LOG` name
  ``` java
  public class SomeClass
  {
    private static final Logger LOG = Logger.getInstance(SomeClass.class);
  }
  ```
