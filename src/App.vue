<template>
<iowa-bar
  iowa_bar_classes="iowa-bar--narrow"
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="hero-banner"></div>
</div>

<banner
  image="images/viewbook/sections/2020_10_14-Pentacrest-and-Cleary-Walkway-Drone-Fall-2020-jatorner-0025-min.jpg"
  banner_size="large"
  banner_vertical_alignment="vertical-center"
  banner_horizontal_alignment="horizontal-center"
  banner_classes=""
  banner_type="image"
  banner_overlay= "gradient-center"
  banner_text=''
  banner_title='Admitted <span>Students</span>'
  banner_title_classes='headline headline--uppercase'
/>

<div role="region" class="menu-group__wrapper">
  <div class="menu-group__container">
    <menuGroup
      :items="menu_items"
    />
  </div>
</div>

<verticalDots
  :sections="sections"
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="academic-life"></div>
</div>
<grid-panel
  link_url= 'https://admissions.uiowa.edu/academics/undergraduate-areas-of-study'
  image= ''
  headline= 'Academic Life'
  button_text= 'View Advising Center'
  button_link= 'https://advisingcenter.uiowa.edu'
  grid_panel_type= 'grid-panel grid-panel--asymmetrical'
  grid_panel_first_column= 'grid-panel__column-content-left grid-panel__content'
  grid_panel_second_column= 'grid-panel__column-image-right'
  grid_content_position= 'first'
  grid_panel_content=
    '<p>
      Iowa offers over 200 majors, minors and certificates. Students are encouraged to work
      across disciplines to find their passion. Throughout your college career, you will work
      with an academic adviser—either a professional adviser from the Academic Advising Center
      (AAC) or a faculty member or professional adviser in your major department. In addition
      to helping you choose classes, your academic adviser will help you explore interests and
      options, discover possible academic and career goals, and develop an academic plan to graduation.
    </p>'
  grid_panel_content_2= ''
  :card_grid = 'true'
  :areas_of_study = 'areas_of_study'
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="reach-higher"></div>
</div>

<grid-panel
  link_url= 'https://admissions.uiowa.edu/admitted-students/admitted-first-year-students'
  image= 'images/viewbook/sections/2018_11_01-THTR-3240-COSTUME-DESIGN-0077-min.JPG'
  headline= 'Reach Higher'
  button_text= 'Next Steps for Admitted Students'
  button_link= 'https://admissions.uiowa.edu/admitted-students/admitted-first-year-students'
  grid_panel_type= 'grid-panel grid-panel--asymmetrical'
  grid_panel_first_column= 'grid-panel__column-image-left'
  grid_panel_second_column= 'grid-panel__column-content-right grid-panel__content'
  grid_content_position= 'second'
  grid_panel_content= '<div class="text--gray element--bold-intro">Next Steps</div>'
  grid_panel_content_2=
    '<p>
      Now that you’ve come this far, you may be wondering,
      “What’s next?” We’ve prepared this resource to help
      you join the Hawkeye family
    </p>'
/>

<statWrapper
  :stats="stats_1"
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="your-new-home"></div>
</div>
<Aerial
  aerial_title='Your New Home!'
  aerial_image='images/viewbook/sections/12.jpg'
  grid_title_1='World-class hospital'
  grid_sub_1=' A nationally ranked, comprehensive medical center is just a short walk away.'
  grid_title_2='Best college town'
  grid_sub_2='Named the #1 Best College Town by reviews.org, Iowa City seamlessly blends a vibrant downtown with the heart of campus.'
  grid_title_3='Easy to get around'
  grid_sub_3=' Whether you like to walk, bike, or take the free bus system, residence halls are closely located to the center of campus and downtown Iowa City.'
  grid_title_4='Big ten athletics'
  grid_sub_4='Seating nearly 70,000, Kinnick Stadium is home to Hawkeye Football, just one of the 24 NCAA teams at Iowa.'
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="jump-in"></div>
</div>
<grid-panel
  link_url= 'https://admissions.uiowa.edu/admitted-students/admitted-first-year-students#opportunities'
  image= 'images/viewbook/sections/2016_06_26-ISS-Calendar-Shoot-CHEER-jatorner-0236-Edit-min.JPG'
  headline= 'JUMP IN'
  button_text= 'Opportunities For First Year Students'
  button_link= 'https://admissions.uiowa.edu/admitted-students/admitted-first-year-students#opportunities'
  grid_panel_type= 'grid-panel grid-panel--asymmetrical'
  grid_panel_first_column= 'grid-panel__column-content-left grid-panel__content'
  grid_panel_second_column= 'grid-panel__column-image-right'
  grid_content_position= 'first'
  grid_panel_content= '<div class="text--gray element--bold-intro">Student Opportunities</div>'
  grid_panel_content_2=
    '<p>
      With more than 500 student organizations on campus, you can get
      involved and connect with people who share your interests.
      First-year students are encouraged to explore and choose
      from the many activities available on campus.
    </p>'
/>

<statWrapper
  :stats="stats_2"
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="reach-your-goals"></div>
</div>
<grid-panel
  link_url= 'https://stories.uiowa.edu/student-outcomes'
  image= 'images/viewbook/sections/2019_05_03-Cap-and-Gown-Commercial-Shoot-jatorner-1312-min.jpg'
  headline= 'Reach Your Goals'
  button_text= 'View Student Outcomes'
  button_link= 'https://stories.uiowa.edu/student-outcomes'
  grid_panel_type= 'grid-panel grid-panel--asymmetrical'
  grid_panel_first_column= 'grid-panel__column-image-left'
  grid_panel_second_column= 'grid-panel__column-content-right grid-panel__content'
  grid_content_position= 'second'
  grid_panel_content=
    '<p>
      Having big ideas isn’t enough—to excel in any career,
      you need to know how to share them and make them real.
      Iowa’s leadership in the study and craft of writing helps
      every Hawkeye learn communication skills that give them an
      edge. Dedicated career advising, thousands of on-campus
      job interviews, and countless opportunities for hands-on
      learning make Iowa grads stand out.
    </p>'
  grid_panel_content_2= ''
/>

<statWrapper
  :stats="stats_3"
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="your-next-steps"></div>
</div>
<div class="grid-panel grid-panel--split">
  <div class="grid-panel__column grid-panel__content">
    <headline
      headline_level= "h2"
      headline_class= "bold-headline--caps bold-headline headline"
      headline= "Your Next Steps"
    />
    <hr class="element--spacer-separator" />
        <h3 class="bold-headline bold-headline--serif bold-headline--underline">
          <span class="heading__heading">Housing.</span>
        </h3>

        <p>
          Living in the residence halls is a wonderful part of the Hawkeye experience. Visit our
          housing website to learn more about your new home, view video tours, and find details
          on furnishings, amenities, and floor plans.
        </p>

        <p>Apply in MyUI</p>
        <ul>
          <li>$75 Application Fee</li>
        </ul>

        <p>Explore Options and search for roommates</p>
        <ul>
          <li>Through May 3</li>
        </ul>

        <p>Find a roommate</p>
        <ul>
          <li>Through May 17</li>
        </ul>

        <p>Final room selection</p>
        <ul>
          <li>Starts in the summer</li>
        </ul>

        <p>
          <a href="https://housing.uiowa.edu" class="bttn bttn--secondary bttn--caps">

            View Housing
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <h3 class="bold-headline bold-headline--serif bold-headline--underline">
          <span class="heading__heading">Financial Aid.</span>
        </h3>

        <p>
          With help from the Office of Student Financial Aid, eligible students can receive
          assistance through scholarships, grants, work-study, and loans.
        </p>

        <p>
          You can track the status of your financial aid on MyUI under My Financial Aid To Do
          List. MyUI will indicate if the Office of Student Financial Aid has received your FAFSA
          and if you have completed all required forms.
        </p>

        <p>
          <a href="https://myui.uiowa.edu" class="bttn bttn--secondary bttn--caps">

            My Financial Aid To Do List
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <p>Types of Financial Aid</p>
        <ul>
          <li>Need, Merit, Employment Loans</li>
        </ul>

        <p>
          <a href="https://financialaid.uiowa.edu/types" class="bttn bttn--secondary bttn--caps">

            Types of Aid
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <p>File the Free Application for Federal Student Aid (FAFSA)</p>
        <ul>
          <li>Complete Annually</li>
        </ul>

        <p>
          <a href="https://fafsa.gov" class="bttn bttn--secondary bttn--caps">

            Fafsa.gov
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <p>View your financial aid offer</p>
        <ul>
          <li>Notifications begin in late-February</li>
        </ul>

        <p>
          <a href="https://financialaid.uiowa.edu/receivingfunds/notification" class="bttn bttn--secondary bttn--caps">

            Financial Aid Offer
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

  </div>
  <div class="grid-panel__column grid-panel__content">

        <h3 class="bold-headline bold-headline--serif bold-headline--underline">
          <span class="heading__heading">Before Orientation.</span>
        </h3>

        <p>We’re thrilled you’re thinking about becoming a Hawkeye, but there are several things you’ll need to do before that can happen.</p>

        <p>Set up your HawkID</p>
        <ul>
          <li>You received an email with instructions on how to do this.</li>
        </ul>

        <p>Set up your HawkID</p>
        <ul>
          <li>You received an email with instructions on how to do this.</li>
        </ul>

        <p>Upload your photo for your Iowa One Card</p>
        <ul>
          <li>The Iowa One Card is your official University of Iowa photo ID</li>
        </ul>

        <p>
          <a href="https://idcard.uiowa.edu/online-photo-submission" class="bttn bttn--secondary bttn--caps">

            Iowa One Card Photo
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <p>Take Placement Tests</p>
        <ul>
          <li>
            Beginning in May, you can start taking placement tests. Placement tests include math, chemistry, and world languages. You may not be able to register for certain
            classes without a placement test score. Tests must be completed 2 weeks prior to
            your orientation date
          </li>
        </ul>

        <p>
          <a href="https://newstudents.uiowa.edu/placement-tests" class="bttn bttn--secondary bttn--caps">

            Placement Tests
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <h3 class="bold-headline bold-headline--serif bold-headline--underline">
          <span class="heading__heading">Your Transition.</span>
        </h3>

        <p>Orientation</p>
        <ul>
          <li>
            First-year students will participate in an online Orientation
            experience designed to prepare them for their first semester
            and beyond. During online Orientation, students work with their
            academic adviser, plan their fall semester class schedule, and
            register for classes. In addition, they learn about the university
            and meet other new students.
          </li>
        </ul>

        <p>
          <a href="https://newstudents.uiowa.edu/orientation" class="bttn bttn--secondary bttn--caps">

            Orientation
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <p>Success at Iowa Course</p>
        <ul>
          <li>New undergraduate students are required to complete the online course, Success at Iowa.</li>
        </ul>

        <p>
          <a href="https://newstudents.uiowa.edu/success-iowa-online-course" class="bttn bttn--secondary bttn--caps">

            Success At Iowa
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>

        <p>ON IOWA!</p>
        <ul>
          <li>
            On Iowa! is the official Hawkeye welcome and will provide a
            comprehensive introduction to university life. During On Iowa!,
            students will learn about academic expectations, the differences
            between high school and college, and how to be successful at
            Iowa by setting goals, staying safe and healthy, and getting
            involved on campus.
          </li>
        </ul>

        <p>
          <a href="https://oniowa.uiowa.edu" class="bttn bttn--secondary bttn--caps">

            ON IOWA!
            <i class="fas fa-arrow-right"></i>
          </a>
        </p>
  </div>
</div>

<banner
  image=""
  banner_size="small"
  banner_vertical_alignment="vertical-center"
  banner_horizontal_alignment="horizontal-center"
  banner_classes="bg--black banner--slim-title"
  banner_type=""
  banner_overlay= ""
  banner_text='$250 Acceptance Fee'
  banner_title='Accept Admission by May 3'
  banner_title_classes='headline headline--uppercase'
/>

<div class="v-dots-scroll-spacer">
  <div class="v-dots-scroll-target" id="be-a-hawkeye"></div>
</div>
<div class="image-grid">
  <div class="image-grid__section">
    <img class="card__img" :src="'images/viewbook/sections/cropped-kinnick.jpg'" alt="Alt Text" loading=lazy>
  </div>

  <div class="image-grid__section">
    <img class="card__img" :src="'images/viewbook/sections/cropped-herky.jpg'" alt="Alt Text" loading=lazy>
  </div>

  <div class="image-grid__section">
    <Modal>
      <template v-slot:modal-trigger>
        <img class="card__img" :src="'images/viewbook/sections/Pano6.jpg'" alt="Alt Text" loading=lazy>
      </template>
      <template v-slot:modal-content>
        <img :src="'images/viewbook/sections/campus-drone-image.jpg'" alt="Alt Text" loading=lazy>
      </template>
    </Modal>
  </div>

  <div class="image-grid__section grid__content bg-pattern--brain-reversed">
    <headline
      headline_level= "h2"
      headline_class= "bold-headline--caps bold-headline headline"
      headline= "Be a Hawkeye"
    />
  </div>

  <div class="image-grid__section">
    <img class="card__img" :src="'images/viewbook/sections/2016_07_05-Herky-On-Top-of-Old-Cap-jatorner-281-HDR-Edit-min.JPG'" alt="Alt Text" loading=lazy>
  </div>

  <div class="image-grid__section">
    <img class="card__img" :src="'images/viewbook/sections/2019_10_24-Fall-2019-Campus-Lifestyle-Shoot-jatorner-1939-min.jpg'" alt="Alt Text" loading=lazy>
  </div>
</div>

<footerSection
  :contact_info="contact_info"
  :social_media_links="social_media_links"
/>

</template>

<script>
// In order to use components, you must import them from their files to your script.
// You must also register them in the `components` section of the `export default {}` area below.
// For ease of use, all currently usable components are imported here.
import Banner from './components/Banner.vue';
import Stat from './components/Stat.vue';
import statWrapper from './components/statWrapper.vue';
import IowaBar from './components/IowaBar.vue';
import GridPanel from './components/GridPanel.vue';
import Headline from './components/Headline.vue';
import verticalDots from './components/verticalDots.vue';
import linkButton from './components/linkButton.vue';
import Aerial from './components/Aerial.vue';
import menuGroup from './components/menuGroup.vue';
import footerSection from './components/footerSection.vue';
import Modal from './components/Modal.vue';

export default {
  name: 'App',

  // In addition to importing all components from their files, you must register them here for them to work.
  components: {
    Banner,
    Stat,
    statWrapper,
    IowaBar,
    Headline,
    verticalDots,
    GridPanel,
    linkButton,
    Aerial,
    menuGroup,
    Modal,
    footerSection
  },

  // This area is where we are currently importing the set props for our components.
  data() {
    return {
      areas_of_study: [
        {
          headline: 'Business, Economics, and Management',
          image: 'images/viewbook/areas/1.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/biz-econ-mgmt',
        },
        {
          headline: 'Education',
          image: 'images/viewbook/areas/2.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/edu',
        },
        {
          headline: 'Engineering and Computing',
          image: 'images/viewbook/areas/3.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/engr-comp',
        },
        {
          headline: 'Health Sciences',
          image: 'images/viewbook/areas/4.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/health-sci',
        },
        {
          headline: 'Languages, culture, and society',
          image: 'images/viewbook/areas/5.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/lang-cult-soc',
        },
        {
          headline: 'Life and natural sciences',
          image: 'images/viewbook/areas/6.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/life-nat-sci',
        },
        {
          headline: 'Math and quantitative sciences',
          image: 'images/viewbook/areas/7.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/math-quant-sci',
        },
        {
          headline: 'Preprofessional programs',
          image: 'images/viewbook/areas/8.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/preprofessional',
        },
        {
          headline: 'Social sciences and policy',
          image: 'images/viewbook/areas/9.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/soc-sci-pol',
        },
        {
          headline: 'Visual and performing arts',
          image: 'images/viewbook/areas/10.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/vis-perf-arts',
        },
        {
          headline: 'Writing, communications, literature, and media',
          image: 'images/viewbook/areas/11.jpg',
          link_url: 'https://admissions.uiowa.edu/academics/write-comm-media',
        },
        {
          headline: '',
          button_text: 'Browse by Major',
          button_link: 'https://admissions.uiowa.edu/academics/undergraduate-areas-of-study',
        }
      ],
      stats_1: [
        {
          headline: '34',
          headline_prefix: '#',
          headline_suffix: '',
          stat_description: 'BEST PUBLIC UNIVERSITY BY U.S. NEWS & WORLD REPORT',
          stat_content: 'Among the top 2% of universities worldwide.',
        },
        {
          headline: '15:1',
          headline_prefix: '',
          headline_suffix: '',
          stat_description: 'STUDENT-TO-FACULTY RATIO',
          stat_content: 'Get to know your professors.',
        },
        {
          headline: '200+',
          headline_prefix: '',
          headline_suffix: '',
          stat_description: 'AREAS OF STUDY',
          stat_content: 'Earn a degree that reflects your unique interests and career goals.',
        },
        {
          headline: '1 in 3',
          headline_prefix: '',
          headline_suffix: '',
          stat_description: 'UNDERGRADS PARTICIPATE IN RESEARCH',
          stat_content: 'Gain experience now.',
        }
      ],
      stats_2: [
        {
          headline: '500',
          headline_prefix: '',
          headline_suffix: '+',
          stat_description: 'STUDENT<br />  ORGANIZATIONS',
          stat_content: 'Or, start your own.',
        },
        {
          headline: '100',
          headline_prefix: '',
          headline_suffix: '+',
          stat_description: 'RESTAURANTS AND<br />  CAFÉS',
          stat_content: 'From vegan brunch to pie shakes.',
        },
        {
          headline: '400',
          headline_prefix: '',
          headline_suffix: '+',
          stat_description: 'ARTS PERFORMANCES Available EACH YEAR',
          stat_content: 'For $5 or less.',
        },
        {
          headline: '24',
          headline_prefix: '',
          headline_suffix: '',
          stat_description: 'NCAA DIVISION I<br />  TEAMS',
          stat_content: 'There’s nothing like a Hawkeye game.',
        }
      ],
      stats_3: [
        {
          headline: '96',
          headline_prefix: '',
          headline_suffix: '%',
          stat_description: 'OVERALL JOB/GRADUATE SCHOOL PLACEMENT RATE',
          stat_content: 'Business <strong>97%</strong><br />Education <strong>91%</strong><br />Engineering  <strong>96%</strong><br /> Liberal Arts and Sciences <strong>94%</strong><br /> Nursing <strong>99%</strong><br />Pharmacy <strong>97%</strong>',
        },
        {
          headline: '4,000',
          headline_prefix: '',
          headline_suffix: '+',
          stat_description: 'STUDENT<br />  INTERNSHIPS',
          stat_content: 'Everywhere from NASA to the Minnesota Vikings.',
        },
        {
          headline: '4,100',
          headline_prefix: '',
          headline_suffix: '+',
          stat_description: 'Employers have hired Iowa Graduates the past three years',
          stat_content: 'Gain real-world skills that make résumés stand out.',
        },
        {
          headline: '1,316',
          headline_prefix: '',
          headline_suffix: '+',
          stat_description: 'STUDENTS STUDIED ABROAD LAST YEAR',
          stat_content: 'Spanning the globe in 69 countries.',
        }
      ],
      menu_items: [
        {
          text: 'Admitted Checklist',
          url: 'https://admissions.uiowa.edu/admitted-students/admitted-first-year-students',
          item_class: 'bttn bttn--outline bttn--tertiary bttn--transparent bttn--caps bttn--apply'
        },
        {
          text:  'Schedule a Visit',
          url: 'https://admissions.uiowa.edu/visit-campus',
          item_class: 'bttn bttn--outline bttn--tertiary bttn--transparent bttn--caps bttn--visit'
        },
        {
          text: 'Contact Us',
          url: 'https://admissions.uiowa.edu/contact-us',
          item_class: 'bttn bttn--outline bttn--tertiary bttn--transparent bttn--caps bttn--ask'
        },
        {
          text: 'Accept Admission',
          url: 'https://myui.uiowa.edu',
          item_class: 'bttn bttn--outline bttn--tertiary bttn--transparent bttn--caps bttn--connect'
        },
      ],
      sections: [
        {
          section_title: 'Back to Top',
          section_id: 'hero-banner'
        },
        {
          section_title: 'Academic Life',
          section_id: 'academic-life'
        },
        {
          section_title: 'Reach Higher',
          section_id: 'reach-higher'
        },
        {
          section_title: 'Your New Home',
          section_id: 'your-new-home'
        },
        {
          section_title: 'Jump In',
          section_id: 'jump-in'
        },
        {
          section_title: 'Reach Your Goals',
          section_id: 'reach-your-goals'
        },
        {
          section_title: 'Your Next Steps',
          section_id: 'your-next-steps'
        },
        {
          section_title: 'Be a Hawkeye',
          section_id: 'be-a-hawkeye'
        },
      ],
      contact_info: '<p>Iowa City, Iowa 52242<br><a href="tel:319-335-3847"><i class="fas fa-phone"></i> 319-335-3847</a><br /></p>',
      social_media_links: [
        {
          text: 'Facebook',
          url: 'http://www.facebook.com/admissions.office',
          icon_class: 'fab fa-facebook-square'
        },
        {
          text: 'Instagram',
          url: 'http://instagram.com/iowaadmissions',
          icon_class: 'fab fa-instagram'
        },
        {
          text:  'Twitter',
          url: 'https://twitter.com/iowaadmissions',
          icon_class: 'fab fa-twitter-square'
        },
        {
          text: 'Youtube',
          url: 'http://www.youtube.com/uiowaadmissions',
          icon_class: 'fab fa-youtube'
        }
      ]
    }
  }
}
</script>

<style lang="scss">
$imgpath: '../node_modules/@uiowa/uids/src/assets/images';
@import '../node_modules/@uiowa/uids/src/assets/scss/reset.scss';
@import '../node_modules/@uiowa/uids/src/components/typography/lists/lists.scss';
@import '../node_modules/@uiowa/uids/src/components/tables/tables.scss';
@import '../node_modules/@uiowa/uids/src/components/typography/paragraph/paragraph.scss';
@import '../node_modules/@uiowa/uids/src/components/colors/colors.scss';
@import '../node_modules/@uiowa/uids/src/components/grid/grid.scss';
@import '../node_modules/@uiowa/uids/src/components/viewbook/grid-panel/grid-panel.scss';
@import '../node_modules/@uiowa/uids/src/components/card/card.scss';
@import '../node_modules/@uiowa/uids/src/components/layouts/viewbook/viewbook.scss';

.image-grid__section {
  line-height: 0;
}

// Override and condense for smaller devices.
.menu-group__wrapper {
  transition: padding 0.5s ease;
  padding: 0.3rem 0;
  .menu-group__container .menu a {
    transition: margin 0.5s ease;
    margin: 0px .5rem;
    padding-bottom: 0.5rem;
  }
  .bttn--outline {
    border: none;
  }
}
@media (min-height: 1000px) {
  .menu-group__wrapper {
    padding: 1.875rem 0;
    .menu-group__container .menu a {
      margin: 0px 1.05rem;
    }
    .bttn--outline {
      border: 1px solid rgb(21, 21, 21);
    }
  }
}
.grid-panel--split {
  @media (min-width: 768px) {
    .grid-panel__column.grid-panel__content {
      padding: 0px 3.5rem 0px calc(3rem + 115px);
    }
  }
}
</style>
