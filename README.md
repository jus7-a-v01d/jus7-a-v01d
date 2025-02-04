```rust

pub mod README {
  impl jus7-a-v01d {
    pub fn introduce_self() -> Self {
      jus7-a-v01d{
        name: "Void",
        age: 20,
        motiv: vec![Motivation::getExperience, Motivation::writeBetterCode],
        curr_os: Os::Debian,
      }
    }

    pub fn print_goals(&self) {
      println!("Learn about kernel modues and operating systems");
      println!("Find the perfect vimrc");
    }  

    pub fn opinion_on_language(lang: &str) -> Result<(), String> {
      match lang {
        "Rust" => Ok(()),
        "C++" => Ok(()),
        "Bash" => Ok(()),
        "C" => Err(String::from("Not enough practice")),
        "Python" => panic!("god please no"),
        _ => Err(String::from(" ¯\_(ツ)_/¯")),
      }
    }
  }
}
```
