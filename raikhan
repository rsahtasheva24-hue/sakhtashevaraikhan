using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter Product Name: ");
        string productName = Console.ReadLine();

        Console.Write("Enter Quantity: ");
        int quantity = int.Parse(Console.ReadLine());

        Console.Write("Enter Price per Item: ");
        double price = double.Parse(Console.ReadLine());

        Console.Write("Enter Discount Percentage: ");
        double discount = double.Parse(Console.ReadLine());

        Console.Write("Enter Delivery Distance in km: ");
        double distance = double.Parse(Console.ReadLine());

        Console.Write("Enter First Letter of Payment Method: ");
        char payment = char.Parse(Console.ReadLine());

        Console.Write("Is Express Delivery (true/false): ");
        bool express = bool.Parse(Console.ReadLine());

        double total = quantity * price;
        double discountAmount = total * (discount / 100);
        double finalPrice = total - discountAmount;

        Console.WriteLine("\n----- ORDER SUMMARY -----");
        Console.WriteLine("Product: " + productName);
        Console.WriteLine("Total Price: " + total);
        Console.WriteLine("Discount Amount: " + discountAmount);
        Console.WriteLine("Final Price: " + finalPrice);
    }
}
