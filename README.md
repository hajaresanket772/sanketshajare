function getEmployees() {
    return [
        { name: "Alice", department: "engineer", salary: 7000 },
        { name: " Bob", department: " sales", salary: 50000 },
        { name: "charlie", department: " HR", salary: 4000 },
        { name: "Daisy", department: "engineer", salary: " 80000" }
    ];
    for (let emp of getEmployees) {
        if (emp.department === "engineer") {
            emp.salary += emp.salary * 0.10;
        } else if (emp.department === "sales") {
            emp.salary += emp.salary * 0.05;
        }
    }
    console.log(getEmployees);
}
