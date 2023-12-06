## Liveness Detection

**Project description:** 
An API to detect liveness from a short videos / set of images. This service can be used in a KYC (Know Your Customer) process to verify that the customer is a real person.

Liveness we attempt to detect:
- Blinking
- Looking to the left side
- Looking to the right side

### 1. Input
- A short video, OR
- Set of images
```python
if (isAwesome){
  return true
}
```

### 2. Process
- Detect face / head from images
- Identify if the object of interest (person) show liveness
- Calculate the probability of each acation

```javascript
if (isAwesome){
  return true
}
```

### 3. Output
- API response in json 

### 4. Demo

<img src="images/dummy_thumbnail.jpg?raw=true"/>


