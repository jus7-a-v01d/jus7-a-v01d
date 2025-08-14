```rust

pub mod README {
  impl jus7-a-v01d {
    pub fn introduce_self() -> Self {
      jus7-a-v01d{
        name: String::from("Void"),
        age: 21,
        motiv: vec![Motivation::getExperience, Motivation::writeBetterCode],
        curr_os: Os::Debian,
      }
    }

    pub fn print_goals(&self) {
      println!("Learn about kernel modules and operating systems");
      println!("Find the perfect vimrc");
    }  

    pub fn opinion_on_language(&self, lang: &str) -> Result<(), String> {
      match lang {
        "Rust" => Ok(()),
        "C++" => Ok(()),
        "Bash" => Ok(()),
        "C" => Err(String::from("Not enough practice")),
        "Typescript" => Err(String::from("Do not like")),
        "Python" => panic!("god please no"),
        _ => Err(String::from(r" ¯\_(ツ)_/¯")),
      }
    }
  }
}
```
