
# UniversalAdapter (UAdap)

UniversalAdapter is a single abstract adapter that implements common AWT/Swing listeners so users can extend one class and override only the callbacks they need.

Author: **Vaibhav Bodade (UAdap)**  
GitHub: [vaibhavdb14](https://github.com/vaibhavdb14)  

---

## 🚀 Quick start (download JAR)

1. Go to the **[Releases](https://github.com/vaibhavdb14/UniversalAdapter/releases)** page of this repository.  
2. Download `universal-adapter.jar`.  
3. Add it to your project (example assumes `lib/` folder):  

# compile
javac -cp universal-adapter.jar -d out examples/TestApp.java

# run
java -cp "out;universal-adapter.jar" TestApp   # Windows
java -cp out:universal-adapter.jar TestApp     # Mac/Linux


