``` swift

import UIKit
import WebKit

class ViewController: UIViewController {
    @IBOutlet weak var webView: WKWebView!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        
        if let webURL = URL(string: "https://www.apple.com") {
            let request = URLRequest(url: webURL)
            webView.load(request)
        }

    }
}
``` 

<p align="center">
    <img src="https://github.com/carlos-santiago-2017/LoadingAwebSiteWithWebKitView/blob/master/1.png" width="375">
</p>
