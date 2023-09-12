<!-- ***** Our Classes Start ***** -->
<template>
  
<section class="section" id="our-classes">
    <div class="container">
        <div class="row">
            <div class="col-lg-6 offset-lg-3">
                <div class="section-heading">
                    <h2>Our <em>Classes</em></h2>
                    <img src="/src/assets/images/line-dec.png" alt="">
                    <p>This training class is designed to provide a well-rounded workout that targets various muscle groups while improving cardiovascular fitness and flexibility.</p>
                </div>
            </div>
        </div>
        <div class="row" id="tabs">
          <div class="col-lg-4">
            <ul>
              <li><a href='#tabs-1'><img src="/src/assets/images/tabs-first-icon.png" alt="">First Training Class</a></li>
              <li><a href='#tabs-2'><img src="/src/assets/images/tabs-first-icon.png" alt="">Second Training Class</a></li>
              <li><a href='#tabs-3'><img src="/src/assets/images/tabs-first-icon.png" alt="">Third Training Class</a></li>
              <li><a href='#tabs-4'><img src="/src/assets/images/tabs-first-icon.png" alt="">Fourth Training Class</a></li>
              <div class="main-rounded-button"><a href="#">View All Schedules</a></div>
            </ul>
          </div>
          <div class="col-lg-8">
            <section class='tabs-content'>
              <article id='tabs-1'>
                <img src="/src/assets/images/training-image-01.jpg" alt="First Class">
                <h4>First Training Class</h4>
                <p>This beginner-friendly training class focuses on introducing participants to fundamental exercises that target major muscle groups and improve overall fitness....</p>
                <div class="main-button">
                    <a href="#">View Schedule</a>
                </div>
              </article>
              <article id='tabs-2'>
                <img src="/src/assets/images/training-image-02.jpg" alt="Second Training">
                <h4>Second Training Class</h4>
                <p>This class combines cardiovascular exercises with core-focused movements to enhance endurance and strengthen the core muscles.</p>
                <div class="main-button">
                    <a href="#">View Schedule</a>
                </div>
              </article>
              <article id='tabs-3'>
                <img src="/src/assets/images/training-image-03.jpg" alt="Third Class">
                <h4>Third Training Class</h4>
                <p>Fusce laoreet malesuada rhoncus. Donec ultricies diam tortor, id auctor neque posuere sit amet. Aliquam pharetra, augue vel cursus porta, nisi tortor vulputate sapien, id scelerisque felis magna id felis. Proin neque metus, pellentesque pharetra semper vel, accumsan a neque.</p>
                <div class="main-button">
                    <a href="#">View Schedule</a>
                </div>
              </article>
              <article id='tabs-4'>
                <img src="/src/assets/images/training-image-04.jpg" alt="Fourth Training">
                <h4>Fourth Training Class</h4>
                <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean ultrices elementum odio ac tempus. Etiam eleifend orci lectus, eget venenatis ipsum commodo et.</p>
                <div class="main-button">
                    <a href="#">View Schedule</a>
                </div>
              </article>
            </section>
          </div>
        </div>
    </div>
</section>
<!-- ***** Our Classes End ***** -->

<section class="section" id="schedule">
    <div class="container">
        <div class="row">
            <div class="col-lg-6 offset-lg-3">
                <div class="section-heading dark-bg">
                    <h2>Classes <em>Schedule</em></h2>
                    <img src="/src/assets/images/line-dec.png" alt="">
                    <p>Introduce fundamental exercises targeting major muscle groups.Combine cardiovascular exercises with core-focused movements for endurance and core strength.Rest and recovery. Encourage light activities like walking or stretching.</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <div class="filters">
                    <ul class="schedule-filter">
                        <li class="active" data-tsfilter="monday">Monday</li>
                        <li data-tsfilter="tuesday">Tuesday</li>
                        <li data-tsfilter="wednesday">Wednesday</li>
                        <li data-tsfilter="thursday">Thursday</li>
                        <li data-tsfilter="friday">Friday</li>
                    </ul>
                </div>
            </div>
            <div class="col-lg-10 offset-lg-1">
                <div class="schedule-table filtering">
                    <table>
                        <tbody>
                            <tr>
                                <td class="day-time">Fitness Class</td>
                                <td class="monday ts-item show" data-tsmeta="monday">10:00AM - 11:30AM</td>
                                <td class="tuesday ts-item" data-tsmeta="tuesday">2:00PM - 3:30PM</td>
                                <td>William G. Stewart</td>
                            </tr>
                            <tr>
                                <td class="day-time">Muscle Training</td>
                                <td class="friday ts-item" data-tsmeta="friday">10:00AM - 11:30AM</td>
                                <td class="thursday friday ts-item" data-tsmeta="thursday">2:00PM - 3:30PM</td>
                                <td>Paul D. Newman</td>
                            </tr>
                            <tr>
                                <td class="day-time">Body Building</td>
                                <td class="tuesday ts-item" data-tsmeta="tuesday">10:00AM - 11:30AM</td>
                                <td class="monday ts-item show" data-tsmeta="monday">2:00PM - 3:30PM</td>
                                <td>Boyd C. Harris</td>
                            </tr>
                            <tr>
                                <td class="day-time">Yoga Training Class</td>
                                <td class="wednesday ts-item" data-tsmeta="wednesday">10:00AM - 11:30AM</td>
                                <td class="friday ts-item" data-tsmeta="friday">2:00PM - 3:30PM</td>
                                <td>Hector T. Daigle</td>
                            </tr>
                            <tr>
                                <td class="day-time">Advanced Training</td>
                                <td class="thursday ts-item" data-tsmeta="thursday">10:00AM - 11:30AM</td>
                                <td class="wednesday ts-item" data-tsmeta="wednesday">2:00PM - 3:30PM</td>
                                <td>Bret D. Bowers</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</section>


</template>


<script>

export default{
    name:"ClassSchedule"
}
</script>
