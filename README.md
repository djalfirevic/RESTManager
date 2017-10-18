# REST Manager

Easy to use REST manager for Swift

# Installation

Simply include RESTManager.swift inside your project and use it:

```
RESTManager.shared.loadData(from: "some_url", method: .post, parameters: ["parameter": 123], completion: { (success, response) in
   if let json = response as? JSON {
      print(json)
   }
})

```

Of course, if necessary, Error could be included in completion block very easily.
