// Custom JavaScript injection to change footer text with a clickable link
function custom_footer_script() {
    echo '
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const footerText = document.querySelector(".footer-text"); //footer-text(Enter your Copyright Text Class or ID)
            if (footerText) {
                footerText.innerHTML = \'Design and Develop by <strong><a href="https://dev-almuminpanna.pantheonsite.io" target="_blank" style="color: inherit; text-decoration: None;">Al Mumin Panna</a></strong>\';
            }
        });
    </script>
    ';
}
add_action('wp_footer', 'custom_footer_script');
