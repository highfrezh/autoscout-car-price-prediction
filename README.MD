### About Dataset
This dataset provides comprehensive details on used car listings, including vehicle specifications, features, pricing, and more. It's valuable for analyzing car prices, trends, and customer preferences in the automotive market.

### Columns Description

- `make_model:` The brand and model of the vehicle (e.g., 'Audi A1').
- `body_type:` The body style of the vehicle, such as Sedan, Compact, or Station Wagon.
- `price: `The listed price of the car in currency.
- `vat:` Indicates the VAT status for the vehicle's price (e.g., VAT deductible, Price negotiable).
- `km:` The total mileage (in kilometers) of the vehicle, indicating its usage.
- `Type:` Condition of the vehicle, whether it's 'Used' or 'New'.
- `Fuel:` Type of fuel the vehicle uses, such as 'Diesel', 'Benzine', etc.
- `Gears:` The number of gears in the vehicle's transmission.
- `Comfort_Convenience:` Comfort and convenience features, such as 'Air conditioning', 'Leather steering wheel', 'Cruise control', and more.
- `Entertainment_Media:` Media features available in the vehicle, including 'Bluetooth', 'MP3', 'Radio', etc.
- `Extras:` Additional features like 'Alloy wheels', 'Sport suspension', etc.
- `Safety_Security:` Safety features like 'ABS', 'Airbags', 'Electronic stability control', 'Isofix', etc.
- `age:` Age of the car (calculated based on the model year).
- `Previous_Owners:` The number of previous owners the car has had.
- `hp_kW:` Engine power in kilowatts (kW), indicating the performance capacity of the engine.
- `Inspection_new: `Indicates whether the car has recently undergone an inspection (1 for yes, 0 for no).
- `Paint_Type:` The type of paint on the car, such as 'Metallic', 'Matte', etc.
- `Upholstery_type:` The material used for the interior upholstery, such as 'Cloth', 'Leather', etc.
- `Gearing_Type:` The type of transmission the car uses, either 'Automatic' or 'Manual'.
- `Displacement_cc:` The engine displacement in cubic centimeters (cc), indicating the size of the engine.
- `Weight_kg:` The total weight of the vehicle in kilograms.
- `Drive_chain:` The type of drivetrain, indicating whether it's 'Front' or 'Rear' wheel drive.
- `cons_comb:` The combined fuel consumption in liters per 100 kilometers.

### Key Features
- `Vehicle Specifications:` Covers details like make, model, body type, fuel type, and more.
- `Comfort & Safety Features:` Includes information on air conditioning, safety features, and other convenience options.
- `Performance Metrics: `Provides data on mileage, engine power, weight, and fuel consumption.
- `Pricing Information: `Insights into vehicle pricing, VAT status, and other cost-related details.

### Ideal Use Cases
- `Price Prediction:` Model car prices based on features like mileage, fuel type, and performance.
- `Market Analysis:` Explore trends and preferences in the used car market, by type, region, or other metrics.
- `Customer Segmentation:` Segment the dataset to analyze different customer preferences for car types, features, or price ranges.
- `Feature Importance:` Identify the most important factors influencing car prices (e.g., fuel type, mileage, age).


## How to run?

```bash
conda create -n car_price python=3.8 -y
```

```bash
conda activate car_price
```

```bash
pip install -r requirements.txt
```