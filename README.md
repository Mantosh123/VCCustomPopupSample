# Native IOS Popup Sample
VCCustomPopupSample is the used to show native view controller popup.

## Usage

### Get Bluetooth status

```swift
        let storyboard = UIStoryboard(name: "Main", bundle: .main)
        let vCtr = storyboard.instantiateViewController(withIdentifier: "PopupViewController")
        vCtr.modalPresentationStyle = .overCurrentContext
        present(vCtr, animated: true)
```


## License

VCCustomPopupSample is public to use.
