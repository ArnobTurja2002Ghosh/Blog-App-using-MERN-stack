# Blog App using MERN Stack

Welcome to the Blog App repository! This application is built using the MERN (MongoDB, Express, React, Node.js) stack and comes with various functionalities to manage and share your blogs.

also visit [E-commerce_website-using-React-Redux](https://github.com/khushi2706/E-commerce-website-using-React-Redux)

## Functionalities

- **Authentication:** Secure user authentication system to protect your blogs.
- **Create Blog:** Easily create and publish your blogs with a user-friendly interface.
- **Delete Blog:** Remove unwanted blogs with a simple delete option.
- **Update Blog:** Edit and update your blogs as your content evolves.
- **View Other User Blogs:** Explore and read blogs published by other users.

## Screenshots

![Screenshot 1](https://user-images.githubusercontent.com/67452985/172217325-4378400e-60a0-4364-aadb-89e900886a1c.png)

![Screenshot 2](https://user-images.githubusercontent.com/67452985/172217368-76264e6e-8373-484d-9cd0-3af5920754b1.png)

![Screenshot 3](https://user-images.githubusercontent.com/67452985/172217649-238abde0-1b29-40fe-a46e-1b5bb03678c8.png)

## Getting Started

To get started with this project, follow these steps:

1. Fork this repository

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/Blog-App-using-MERN-stack.git
```

2. Install the required dependencies for both the backend and frontend:

```bash
cd Blog-App-using-MERN-stack
cd server && npm install
cd ../client && npm install
```

3. Configure the database connection in the backend. You can use MongoDB Atlas or a local MongoDB server.

4. Start the backend server:

```bash
cd server && npm start
```

5. Start the frontend application:

```bash
cd client && npm start
```


6. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).

## Arnob's Contribution
The image below is a visual representation of some of the flaws and bugs in the original project:

![Screenshot 2](https://user-images.githubusercontent.com/67452985/172217368-76264e6e-8373-484d-9cd0-3af5920754b1.png)

- Why is there a colon preceding "desc of blog is here"? Turns out, on the left of the colon, the name of the user who posted the blog was expected to appear, but because of a bug the name was not appearing. Fixed.
- There should be an edit and a delete button on the top-right corner of every blog posted by the user currently signed in. Why? Because **update blog** and **delete blog** are claimed to be two of the functionalities of the original project. Added this feature.

## Contributing

We welcome contributions from the community. If you'd like to contribute to this project, please feel free to open an issue and make a pull request to this forked repository because this repository is ahead of the original one. The owner of the original repository [Khushi Patel](https://github.com/khushi2706) is neither attending to issues and pull requests, nor responding to messages (tried to contact through LinkedIn) and the original project looks inactive for weeks. If the original repo gets active later at some point, since this repo is forked from the original, your contributions here can be merged to the original anyway.


## Acknowledgments

We would like to thank all contributors and the open-source community for their support.

---

Feel free to explore the codebase and start creating and sharing your blogs with the world! If you have any questions or need assistance, please don't hesitate to reach out.

Happy blogging!
