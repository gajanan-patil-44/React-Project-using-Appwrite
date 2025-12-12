# installed some pockeges which are required in project
- npm i @reduxjs/toolkit react-redux react-router-dom appwrite @tinymce/tinymce-react html-react-parser react-hook-

# conf.js file created which includes:- 
- "appwrite authentication service file created which included services like, authService, createAccount, login, getCurrentUser, logout etc. "

# config.js file created which includes 
- appwites databases, custom queries, and created some services like 
 ```>createPost
    >updatePost
    >deletePost
    >getPost
    >getPostsList
    >uploadFile
    >deleteFile
    >getFilePreview 
```
# Configured redux-toolkit 

- configured store, which included reducer named authReducer
- created authSlice, which includes initial state, reducers:- 1. login 2. logout (it can called actions)
- create const [loading, setLoading] = useState(true); and useEffect in app.jsx
- dispatch(login({user}))  and dispatch(logout()) in app.jsx

# Building Header.jsx 

- useSelector (to check status)
- useNavigate (to navigate according to slug)
- Binding inside Container complonent after importing it. 
## Designed Input.jsx (input field )
- forwardRef() to connect specific label with respect to there Input field.

# created react hooks 
- created Select.jsx (options are coming that can be in selected)
- PostCard.jsx (preview of post is displayed in home through getFilePreview() through appwriteService)
- - useForm() uses in further components
- created Login.jsx component (also it validate email and password)
- created Signup.jsx comenent (also it validate email and password)
- AuthLayout.jsx (to authenticate user at each time)