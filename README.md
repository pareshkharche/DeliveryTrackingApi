
# DeliveryAPI

DeliveryAPI is a project that provides RESTful APIs for managing delivery tracking. It is built using Django for the backend and ReactJS for the frontend.

## Technologies Used

- Django
- Django REST framework
- ReactJS

## Setup Instructions

### Backend (Django)

1. Navigate to the backend directory:

   ```bash
   cd fedxtrackerdjango
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the migrations and start the server:

   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

### Frontend (ReactJS)

1. Create a new Vite project
npm create vite@latest

2. Navigate to your project directory and select the React template
cd your-project-name
select react
select javascript

3. Navigate to the specific directory (if needed)
cd ../fedxtrackerreactui

4. Install the required packages
npm install

5. Start the React development server
npm run dev


## Screenshots
##OUTPUT
![ss1](https://github.com/pareshkharche/DeliveryTrackingApi/assets/80632983/ea31f7f2-4e57-4d48-9a65-5022ec28eeaf)
![ss2](https://github.com/pareshkharche/DeliveryTrackingApi/assets/80632983/30a601aa-7e97-4625-8fe4-23b375c8bd0e)
![ss3](https://github.com/pareshkharche/DeliveryTrackingApi/assets/80632983/32efe83a-eda0-442c-81e9-dd193ccce553)
![ss4](https://github.com/pareshkharche/DeliveryTrackingApi/assets/80632983/73b967fc-90f7-4bd1-b474-40ec51602795)


## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
