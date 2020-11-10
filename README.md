# elizabeth-harmon-tribute

A tribute to the great Elizabeth Harmon project from the [FreeCodeCamp Responsive Web Design Projects - Tribute Page](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) that must fulfill the user stories.

## User Stories:

- [x] #1: An element with a corresponding `id="main"`, which contains all other elements
- [x] #2: An element with a corresponding `id="title"`, which contains a string that describes the subject of the tribute page
- [x] #3: `div` element with a corresponding `id="img-div"`
- [x] #4: Within the `img-div` element, an `img` element with a corresponding `id="image"`
- [x] #5: Within the `img-div` element, an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `img-div`
- [x] #6: An element with a corresponding `id="tribute-info"`, which contains textual content describing the subject
- [x] #7: An `a` element with a corresponding `id="tribute-link"`, which links to an outside site that contains additional information about the subject of the tribute page
- [ ] #8: `img` element should responsively resize, relative to the width of its parent element, without exceeding its original size.
- [ ] #9: `img` element should be centered within its parent element

## Solutions

### #1: An element with a corresponding `id="main"`, which contains all other elements.

![image](https://user-images.githubusercontent.com/22828458/98626219-2a5a9c00-234c-11eb-8082-c4839782516e.png)

![image](https://user-images.githubusercontent.com/22828458/98626238-3a727b80-234c-11eb-931f-5cb035445d94.png)

```
<main id="main"><h1>Tribute Page</h1></main>
```

### #2: An element with a corresponding `id="title"`, which contains a string that describes the subject of the tribute page

![image](https://user-images.githubusercontent.com/22828458/98628829-68f35500-2352-11eb-92f5-d877e18ed2d5.png)

![image](https://user-images.githubusercontent.com/22828458/98628846-70b2f980-2352-11eb-83bf-33b4bd416ba2.png)

```
<h1 id="title">Elizabeth Harmon</h1>
```

### #3: `div` element with a corresponding `id="img-div"`

![image](https://user-images.githubusercontent.com/22828458/98631447-6dbb0780-2358-11eb-863e-ee562fd850db.png)

![image](https://user-images.githubusercontent.com/22828458/98631464-77dd0600-2358-11eb-9e32-f653de48b33a.png)

```
<div id="img-div"></div>
```

### #4: Within the `img-div` element, an `img` element with a corresponding `id="image"`

![image](https://user-images.githubusercontent.com/22828458/98631829-37ca5300-2359-11eb-865e-9e432d1eb21b.png)

![image](https://user-images.githubusercontent.com/22828458/98631865-46b10580-2359-11eb-858d-cfb9c91f7919.png)

```
<div id="img-div">
    <img
        id="image"
        src="https://decider.com/wp-content/uploads/2020/10/queens-gambit-2.jpg"
        alt="Elizabeth Harmon"
    />
</div>
```

### #5: Within the `img-div` element, an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `img-div`

![image](https://user-images.githubusercontent.com/22828458/98632542-a825a400-235a-11eb-883e-73da5b07e6f1.png)

![image](https://user-images.githubusercontent.com/22828458/98632556-b07ddf00-235a-11eb-8aea-790fb8820e7a.png)

```
<div id="img-div">
    <figure>
        <img
        id="image"
        src="https://decider.com/wp-content/uploads/2020/10/queens-gambit-2.jpg"
        alt="Elizabeth Harmon"
        />
        <figcaption id="img-caption">
        Elizabeth Harmon in the Mexico City Invitational Chess
        </figcaption>
    </figure>
    </div>
```

### #6: An element with a corresponding `id="tribute-info"`, which contains textual content describing the subject

![image](https://user-images.githubusercontent.com/22828458/98636313-9398da00-2361-11eb-8834-6456cfb7614e.png)

![image](https://user-images.githubusercontent.com/22828458/98636335-9b587e80-2361-11eb-9fc9-d9db297278a2.png)

```
<article id="tribute-info">
    <p>
        Elizabeth "Beth" Harmon is a chess prodigy and the main character in
        the Netflix miniseries, The Queen's Gambit.
    </p>
</article>
```

### #7: An `a` element with a corresponding `id="tribute-link"`, which links to an outside site that contains additional information about the subject of the tribute page

![image](https://user-images.githubusercontent.com/22828458/98636772-744e7c80-2362-11eb-8685-4a76b1242bd9.png)

![image](https://user-images.githubusercontent.com/22828458/98636794-7d3f4e00-2362-11eb-92d3-25fc5571c979.png)

```
<a
    id="tribute-link"
    href="https://the-queens-gambit.fandom.com/wiki/Beth_Harmon#Biography"
    target="_blank"
>
    Know more about Beth Harmon
</a>
```

## Running Tests Locally

Add the [CDN link](https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js) just above the `</body>` tag:

```
  <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</body>
```
