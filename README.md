# SwiftUI Flower Shape
This is a simple SwiftUI project that demonstrates how to create a custom flower shape using the Shape protocol. The flower is created by drawing several petals around a center point, and each petal is rotated around the center to create a symmetrical shape.
The Flower struct is responsible for creating the shape of the flower. It has two properties: petalOffset and petalWidth that control the offset and width of the petals respectively.
The path(in rect: CGRect) function is used to create the actual path of the flower. It uses a for loop to create each petal, and applies a rotation transform to each petal to create the symmetrical shape. The Path class is used to construct the actual path of each petal, and is then added to the path variable which is returned at the end.
The ContentView struct is responsible for displaying the flower and the sliders that control the petalOffset and petalWidth properties of the Flower struct. The @State property wrapper is used to create two state variables that control these properties, and the Slider view is used to allow the user to adjust these values.


https://github.com/Ktamim98/GraphicsDesignSwiftUI/assets/124142522/c5fc720e-df0a-4ad1-9b08-3a371ecc7d48


## Credits
This project was created by following the course of "100 Days of SwiftUi" by Paul Hudson.
