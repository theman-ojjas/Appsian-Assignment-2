# Mini Project Manager

## Setup Instructions

### Backend (C# .NET)

1. Navigate to the backend folder:
   ```bash
   git clone https://github.com/theman-ojjas/Appsian-Assignment-2.git
   cd project-manager-server
   
2. Install dependencies (if any are managed via npm for tooling):

   ```bash
   dotnet tool install --global dotnet-ef
   dotnet ef migrations add InitialCreate
   dotnet ef database update

3. Build the project:

   ```bash
   dotnet build

4. Run the backend:

   ```bash
   dotnet run

### Frontend (React+ TypeScript)
Navigate to the frontend folder:

```bash
cd project-manager-ui
npm install
npm dev run
