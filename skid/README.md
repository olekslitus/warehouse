# Skid - CLI

```
app --help

app build "heheh" "kcekenk" "nkecnkec"

app hello "Oleks"
```


```cpp

template<class Command>
class App {

}


struct App : skid::App {
    auto commands() -> skid::Commands {
        return 
    }
}





auto build() -> void {

}

struct BuildCommand: cli::Command<"Help info..."> {
    std::string filename = "default.txt";
}

struct App: cli::App {
    BuildCommand build;
}


void app() {

}

auto main() -> int {
    Skid.run();
    return 0;
}
```


## Alternatives
- https://github.com/CLIUtils/CLI11