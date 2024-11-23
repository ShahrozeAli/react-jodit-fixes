# Custom Jodit React Integration

This repository showcases a custom implementation of the `Jodit React` component with fixes and enhancements to improve its functionality and resolve several known issues. The modifications aim to make the editor more robust and user-friendly, addressing key problems such as content disappearance, infinite re-rendering, copy-paste issues, and more.

## Features and Fixes

### Fixed Issues:

1. **Content Disappearing**:

   - Addressed the issue where editor content was unexpectedly disappearing under certain conditions.

2. **Infinite Re-rendering**:

   - Fixed the infinite rendering loop that caused performance degradation and erratic behavior.

3. **Copy-Paste Issues**:

   - Ensured line breaks are preserved during copy-paste.
   - Added sanitization for pasted content to prevent unwanted formatting or invalid HTML.

4. **Hard-coded Line Breaks**:

   - Resolved issues with unnecessary hard-coded line breaks that were not being removed, ensuring cleaner output.

5. **Double Paste Issue**:
   - Fixed the issue where pasted content would appear twice, ensuring proper handling of paste events.

### Enhancements:

1. **Custom Button Extensions**:

   - Introduced the ability to add custom buttons and toolbar options for enhanced functionality.

2. **Injecting Text at Cursor**:

   - Implemented functionality to inject custom text at the current cursor position in the editor.

3. **Cursor Position Fix**:
   - Resolved the issue where the cursor would reset to the top of the editor, ensuring it remains in the intended position.

## Contributing

Contributions are welcome! If you encounter any issues or have feature requests, please open an issue or submit a pull request.

## Author

- **GitHub**: [ShahrozeAli](https://github.com/ShahrozeAli)
- **Email**:
  - Primary: shehrozegoo1@gmail.com
  - Secondary: dev.shahroze@gmail.com

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy coding! 🎉
