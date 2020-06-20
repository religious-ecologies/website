---
title: "Roman Catholic Dioceses in North America"
date: 2020-03-25
updated: 2020-03-26
abstract: "How mapping Roman Catholic dioceses illustrates key concepts of religious ecologies at a continental scale."
script: viz/catholic-dioceses.js
layout: visualization
thumbnail: dioceses.png
thumbdesc: "A screenshot showing the distribution of dioceses in North America."
---

<p>
  This is a map of Roman Catholic dioceses in North America, from the
  establishment of the first diocese in 1511 to the present.
</p>

<div class="grid-x grid-padding-x">
  <div class="cell medium-12 xlarge-10">
    <h4>Latin Rite Roman Catholic dioceses and archdioceses by year</h4>
    <svg id="chrono-map" width="100%"></svg>
  </div>
  <div id="controls" class="cell medium-12 xlarge-10">
    <div class="grid-x grid-padding-x">
      <div class="cell medium-6 xlarge-6">
        <label for="year" class="float-left">1511</label>
        <label for="year" class="float-right">2020</label>
        <input type="range" id="year" name="year" min="1511" max="2020" step="1" value="1800" />
        <p class="instructions">
          <small><strong>How to use this visualization:</strong> Adjust the slider
            to control the year displayed in the map. Hover over points on the
            map to see details about each diocese or archdiocese. Click on a
            diocese to zoom into that region; click anywhere else to zoom back
            out. The bar chart also displays the number of dioceses established
            in your selected decade.</small>
        </p>
      </div>
      <div class="cell medium-6 xlarge-6">
        <h4>Dioceses established per decade</h4>
        <svg id="barchart" width="100%"></svg>
      </div>
    </div>
  </div>
</div>

<p>There will be lots more interpretative text.</p>

<p>Here is a map of non-Latin Rite dioceses.</p>

<div class="grid-x grid-padding-x">
  <div class="cell medium-10 xlarge-9">
    <h4>Non&ndash;Latin Rite Dioceses in the Roman Catholic Church (Present Day)</h4>
    <svg id="rite-map" width="100%"></svg>
  </div>
</div>