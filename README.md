# PlanMySemester

A web-based tool to help students plan their academic semester by managing course dependencies and prerequisites.

## Features

- Add and manage courses with their prerequisites
- Track completed and pending courses
- Visualize course dependencies
- Get recommendations for course order based on prerequisites
- See available courses that can be taken based on completed prerequisites
- Real-time course summary with dependency information

## How to Use

1. **Add Courses**
   - Enter course code, name, and semester
   - Specify prerequisites (if any)
   - Mark if the course is completed
   - Click "Add Course" to save

2. **Prerequisites Format**
   - Use comma (,) for AND conditions
   - Use pipe (|) for OR conditions
   - Example: `CS101, CS102|CS103` means:
     - Must complete CS101 AND
     - Must complete either CS102 OR CS103

3. **View Course Information**
   - Hover over courses to see dependencies
   - Check available courses section for what you can take
   - Follow the recommended course order for optimal progression

## Technical Details

- Built with vanilla JavaScript, HTML, and CSS
- No external dependencies required
- Data persists in browser's local storage
- Responsive design for all screen sizes

## Getting Started

1. Clone the repository
2. Open `index.html` in your web browser
3. Start adding your courses and planning your semester!

## Contributing

Feel free to open issues or submit pull requests for any improvements you'd like to suggest.

## License

MIT License - feel free to use and modify for your needs. 