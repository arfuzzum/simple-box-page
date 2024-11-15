# The simple box page

The code in this repo has one job: To help you add a scalable box with round corners and a nice shadow to your Tableau dashboards.

## How to make it work
1. Add a webpage element to your dashboard
2. Set the URL to https://arfuzzum.github.io/simple-box-page/
3. Set the X and Y size and position of the webpage element
4. Add the sheet containing your report or visualisation
5. Set the X and Y size and position to the same as your webpage element
6. Set the outer padding to 40px for all sides, which a) nullifies the 20px box margin added to show the shadow and b) adds 20px more for a nice airy feel to your box component.

If your background colors are anything but white you can set the background color of both the webpage and the box by using URL parameters. 'bgColor' controls the page background color, while 'boxColor' controls the box background color.
- https://arfuzzum.github.io/simple-box-page/?bgColor=f5f5f5
- https://arfuzzum.github.io/simple-box-page/?bgColor=f5f5f5&boxColor=FFFFC5

The corner radius and shadow size cannot be changed.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/b906101a-5166-4a7a-8ee7-3d81e481a36b">
