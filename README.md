## Native IOS Popup Sample
VCCustomPopupSample is the used to show native view controller popup.

### Usage

```swift
    let storyboard = UIStoryboard(name: "Main", bundle: .main)
    let vCtr = storyboard.instantiateViewController(withIdentifier: "PopupViewController")
    vCtr.modalPresentationStyle = .overCurrentContext
    present(vCtr, animated: true)
```
https://github.com/user-attachments/assets/36f72a36-8b0e-4727-b4bf-6e8f5b7f37e1

### License

VCCustomPopupSample is public to use.
