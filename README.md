# Professional-Job-Application-Tracker
# 💼 Job Application Tracker

A Python command-line application to track job applications, interviews, and follow-ups with statistics and Excel export capabilities.

## ✨ Features

- 📊 **Dashboard**: Quick overview of all applications with key metrics
- ➕ **Application Management**: Add, view, update, and delete job applications
- 📈 **Status Tracking**: Track applications through the entire hiring process
- 🔔 **Follow-up Reminders**: Never miss a follow-up date
- 📅 **Interview Management**: Schedule and track interview dates
- 📊 **Statistics**: Response rate, success rate, and active application counts
- 📤 **Excel Export**: Professional Excel reports with formatting
- 💾 **Data Persistence**: All data saved automatically in JSON format

## 🎯 Status Flow

- 📝 Applied → 👀 Under Review → 📅 Interview Scheduled → ✅ Interviewed → 🎉 Offer / ❌ Rejected

## 🛠️ Technologies Used

- Python 3.x
- openpyxl (Excel generation)
- JSON (data storage)
- datetime (date/time handling)

## 📦 Installation

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/job-application-tracker.git
cd job-application-tracker
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python job_tracker.py
```

## 💡 Usage

The application provides an interactive menu with the following options:

1. **Dashboard** - View metrics and upcoming events
2. **Add Application** - Record new job application
3. **View All Applications** - Display complete application history
4. **View by Status** - Group applications by current status
5. **Update Application Status** - Change application status
6. **Delete Application** - Remove an application
7. **Export to Excel** - Generate professional Excel report
8. **Exit** - Save and exit

## 📊 Dashboard Metrics

- **Total Applications**: All applications tracked
- **Active Applications**: Excluding rejected/withdrawn/ghosted
- **Response Rate**: Percentage of applications that received responses
- **Success Rate**: Percentage of applications that resulted in offers
- **Follow-ups Today**: Applications requiring follow-up today
- **Upcoming Interviews**: Scheduled interviews with dates

## 🔮 Future Enhancements

- Cover letter template generator
- Email integration for automated follow-ups
- Salary comparison analytics
- Company research notes
- Calendar integration
- Web interface version

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Abhivarshitha Chowdary**
- GitHub: [@abhivarshithachowdary3-sys](https://github.com/abhivarshithachowdary3-sys)

## 🙏 Acknowledgments

Built to help job seekers stay organized during their job search journey. Good luck! 🚀
