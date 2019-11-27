# SwiftUI Charts

Build custom charts with SwiftUI

<center>
<img src="Resources/chart1.png"/>
</center>

Open `/Examples/ChartsExamples.xcodeproj` for more examples for iOS, macOS

## Styles

### LineChartStyle
```swift
Chart(data: [0.1, 0.3, 0.2, 0.5, 0.4, 0.9, 0.1])
    .chartStyle(
        LineChartStyle(.quadCurve, lineColor: .blue, lineWidth: 5)
    )
```

### AreaChartStyle
```swift
Chart(data: [0.1, 0.3, 0.2, 0.5, 0.4, 0.9, 0.1])
    .chartStyle(
        AreaChartStyle(.quadCurve, fill:
            LinearGradient(gradient: .init(colors: [Color.blue.opacity(0.2), Color.blue.opacity(0.05)]), startPoint: .top, endPoint: .bottom)
        )
    )
```

## SDKs
- iOS 13+
- Mac Catalyst 13.0+
- macOS 10.15+
- watchOS 6+
- Xcode 11.0+

## Roadmap
-  Bar chart style

## Code Contibutions
Feel free to contribute via fork/pull request to master branch. If you want to request a feature or report a bug please start a new issue.

## Coffee Contibutions
If you find this project useful please consider becoming a sponsor.
