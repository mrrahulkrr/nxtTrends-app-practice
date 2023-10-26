In this project, I am working on **Nxt Trendz** app with authentication.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-authentication-output-v2.gif" alt="nxt trendz authentication desktop output" style="max-width:90%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px), Small (Size >= 576px), and Medium (Size >= 768px)](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-authentication-sm-outputs.png)
- [Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-authentication-lg-login-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-authentication-lg-home-output.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must will have the following functionalities

- When invalid credentials are provided in the login form and **Login** button is clicked, then the respective error message from the response should be displayed
- When the **username** and **password** are provided correctly and **Login** button is clicked, then the page should navigate to Home Route

</details>

<details>

<summary>API Requests & Responses</summary>
<br/>

**loginApiUrl**

#### API: `https://apis.ccbp.in/login`

#### Method: `POST`

#### Description:

Returns a response based on the credentials provided

#### Sample Success Response

```json
{
  "jwt_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6InJhaHVsIiwicm9sZSI6IlBSSU1FX1VTRVIiLCJpYXQiOjE2MTk2Mjg2MTN9.nZDlFsnSWArLKKeF0QbmdVfLgzUbx1BGJsqa2kc_21Y"
}
```

#### Sample Failure Response

```json
{
  "status_code": 404,
  "error_msg": "Username is not found"
}
```

</details>

<details>
<summary>Components Structure</summary>
<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-authentication-login-component-structure-breakdown.png" alt="nxt trendz authentication login component structure breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-authentication-home-component-structure-breakdown.png" alt="nxt trendz authentication home component structure breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>
</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to see the complete implementation:

- `src/App.js`
- `src/components/LoginForm/index.js`
- `src/components/LoginForm/index.css`
- `src/components/Home/index.js`
- `src/components/Home/index.css`
- `src/components/Header/index.js`
- `src/components/Header/index.css`
</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for authentication**

- `Home` route should consist of `/` in the URL path
- `Login` route should consist of `/login` in the URL path
- User credentials

  ```text
   username: rahul
   password: rahul@2021
  ```

</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-logo-img.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-logo-img.png) alt should be **website logo**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-login-img.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-login-img.png) alt should be **website login**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-home-img.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-home-img.png) alt should be **clothes that get you noticed**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-log-out-img.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-log-out-img.png) alt should be **nav logout**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-home-icon.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-home-icon.png) alt should be **nav home**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-products-icon.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-products-icon.png) alt should be **nav products**
- [https://assets.ccbp.in/frontend/react-js/nxt-trendz-cart-icon.png](https://assets.ccbp.in/frontend/react-js/nxt-trendz-cart-icon.png) alt should be **nav cart**

</details>

<details>
<summary>Colors</summary>

<br/>
<div style="background-color: #1e293b; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #475569; width: 150px; padding: 10px; color: white">Hex: #475569</div>
<div style="background-color: #e6f6ff; width: 150px; padding: 10px; color: black">Hex: #e6f6ff</div>
<div style="background-color: #d7dfe9; width: 150px; padding: 10px; color: black">Hex: #d7dfe9</div>
<div style="background-color: #e2e8f0; width: 150px; padding: 10px; color: black">Hex: #e2e8f0</div>
<div style="background-color: #64748b; width: 150px; padding: 10px; color: white">Hex: #64748b</div>
<div style="background-color: #0b69ff; width: 150px; padding: 10px; color: white">Hex: #0b69ff</div>
<div style="background-color: #ff0b37; width: 150px; padding: 10px; color: white">Hex: #ff0b37</div>
<div style="background-color: #0967d2; width: 150px; padding: 10px; color: white">Hex: #0967d2</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>
