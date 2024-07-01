#include <iostream>
#include <string>
#include <vector>

void printArt() {
    std::vector<std::string> art = {
        " /\\     /\\  _______  __      _________  _______ ",
        "(  \\   /  )(  __   )(  )    /  __    _)(  __   )",
        " \\ (_) /  || |  \\  || (    (  (  |  (  | |  \\  |",
        "  \\   /   || |  |  || |    | |  |  |  | |  |  |",
        "   ) (    || |__/  || (____/\\ |  |  |  | |__/  |",
        "   \\_/    (_______)(_______/(_______)(_______)",
        "  _____  _     _  _______  __    __  _______ ",
        " (  __ \\( \\   / )(  ___  )(  )  (  )(  ____ \\",
        " | (  \\ \\/ \\_/ / | (   ) ||  \\  /  || (    \\/",
        " | |   ) )     (  | |   | ||  (_/  || (_____ ",
        " | |   | | ( ) |  | |   | ||   _   |(_____  )",
        " | |   ) | | | |  | |   | ||  ( )  |      ) |",
        " | (__/  | | | |  | (___) ||  / \\  |/\\____) |",
        " (______/(_)(_)  (_______)(__/   \\_)\_______)"
    };

    for (const std::string &line : art) {
        std::cout << line << std::endl;
    }
}

void printPoem() {
    std::string poem = R"(
    In the twilight of the night,
    Velvet shadows softly creep,
    Whispering secrets of the deep,
    Embracing darkness with their light.

    Silent phantoms of the eve,
    Dancing in the moon's soft glow,
    Where the shadows dare to go,
    In their presence, we believe.
    )";

    std::cout << poem << std::endl;
}

int main() {
    printArt();
    std::cout << std::endl;
    printPoem();
    return 0;
}
