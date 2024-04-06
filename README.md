
# IMAD Assignment

the purposr of this app is to create a basic calculator application


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Authors

- [@ST10459039](https://www.github.com/ST10459039)



public class MainActivity extends AppCompatActivity {
    private TextView resultDisplay;
    // Define buttons and other variables

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        resultDisplay = findViewById(R.id.result_display);
        // Initialize buttons and set onClickListeners

        // Example for addition button
        Button addButton = findViewById(R.id.add_button);
        addButton.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                // Perform addition
            }
        });

        // Implement other operations similarly
    }

    // Methods for calculations
    private void performAddition() {
        // Logic for addition
    }

    // Add methods for subtraction, multiplication, and division
}
