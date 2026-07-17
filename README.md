class Igor : Programmer
{
    public override string[] Languages =>
    [
        "C#",
        "C++",
        "Java",
        "JavaScript",
        "Python"
    ];

    public override string[] Engines =>
    [
        "Unity",
        "Unreal Engine 5"
    ];

    public override string[] Tools =>
    [
        "Blender",
        "Cascadeur",
        "Git"
    ];

    public override bool HasCoffee => true;

    public override void DailyRoutine()
    {
        while (HasCoffee)
        {
            Code();
            CreateGame();
            FixBugs();
            LearnSomethingNew();
        }

        throw new CoffeeNotFoundException();
    }
}
