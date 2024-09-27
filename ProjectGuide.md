# Deign, Flow and archeticture

### Features:
- Authentication system (signin, login)
- Forget pass (resetPass)
- update (updatePass)
- addToChart (addOrder)
- deleteFromCart(deleteOrder)
- checkOut (CheckOut(Paying system))
- Profile (profile)(update)(favorites)(currentOrder)(stateOfOrder)(historyOfPayement)
- addToFav (addtofav)
- Search (search) 
- review table
  	- bookid
	- Comment (addComment)
	- rate

- Users can sell his books with lower price
- admin:
    - CURD

### DataBase architecture
- **Users**:
    - Id:
    - firstName:
    - lastName:
    - password
    - Gmail:
    - Address:
    - PhoneNumber:
	- FAVs
- **Books**:
    - Id:
    - Name:
    - Photo:
    - price:
-   **Orders**:
    - userId
    - order_Id
    - User_id
    - Price
    - Address
    - deliveryDate
