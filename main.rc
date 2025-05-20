use gtk::prelude::*;
use gtk::{Application, ApplicationWindow};
use gtk::glib;

fn main() -> glib::ExitCode {
    let app = Application::builder()
        .application_id("org.example.emptywindow")
        .build();

    app.connect_activate(|app| {
        let window = ApplicationWindow::builder()
            .application(app)
            .title("WIndow")
            .default_width(400)
            .default_height(300)
            .build();

        window.show();
    });
