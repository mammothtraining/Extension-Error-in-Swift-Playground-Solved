# Extension-Error-in-Swift-Playground-Solved

[![Video](https://img.youtube.com/vi/84PyXXByuGg/maxresdefault.jpg)](https://www.youtube.com/watch?v=84PyXXByuGg)

Source code coming soon.

Are you getting an error “No such module UIKit” or similar? Or perhaps an error about an extension not being recognized in your Swift Playground? UIKit or Extension Error in Swift Playground with Alexandra Kropova from Team Mammoth.

Solution

Swift Playgrounds can have trouble recognizing files in different folders because of how a Swift Playground is run/compiled. To enable the extension, put the extension directly in the Swift Playground file, instead of putting the extension in a separate file.

Still not working?

Other tips that may help include:

    Move the extension and the file where you use the extension into the same subfolder.
    Click on the top-level Playground file. Open Xcode’s right-hand sidebar. Make sure your target is iOS if you are using an iOS class like UIImage. Some classes are only available in iOS or macOS but not both.

Toolkit:

    Xcode 13
    Swift 5.5
    SwiftUI 3
    iOS 15

Read the blog post version - https://mammothinteractive.com/uikit-or-extension-error-in-swift-playgrounds-hacking-swift-5-5-xcode-13-and-ios-15/
