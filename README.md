# Content Security Policy Playground

Useful for mucking about with CSP policies.


## How to make this go
1. Install node.js >= v0.10.8 
2. Clone this repo ```git clone git@github.com:evilpacket/csp-playground.git```
3. Install dependencies 

```
cd csp-playground
npm i
```

4. Launch the playground ```node app```
5. 
Which should yield a result something like

```
Server running on port 3000
```

## Edit Policy
You can use the edit policy section to modify the helmet CSP policy that's defined. 
![](http://cl.ly/image/1k1Q1f0L2e3d/Screen%20Shot%202013-06-23%20at%202.28.08%20PM.png)


## Edit Template
Modify your test case template. Add in script, images, whatever.

## Test Page
View your test template with the defined CSP policy. 

## Resources
- [Content Security Policy 1.1 Specification](https://dvcs.w3.org/hg/content-security-policy/raw-file/tip/csp-specification.dev.html)
- https://developer.mozilla.org/en-US/docs/Security/CSP
- [Helmet](https://github.com/evilpacket/helmet)

