---
layout: page
title: How to train a machine.. 
description: to guess numbers at random
img: assets/img/3.jpg
importance: 2
category: work
---

This is a simple and fun experiment where a model learns to guess a gaussian distribution using Generative Adversarial Network (or GAN). There are two networks, both adversaries to each other. 

It is like having two smart kids playing a game: one kid (the artist) tries to draw something that looks real, and the other kid (the inspector) tries to guess if the drawing is real or fake. The artist keeps improving the drawings so the inspector can’t tell the difference, and the inspector keeps getting better at spotting fakes. After playing this game many times, the artist becomes so good that the drawings look just like real photos. Here instead of drawing, the art is to generate samples of real numbers so that they follow a gaussian distribution.


<div style="text-align: center;">
    <div class="row">
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.html path="assets/img/ml_gan.gif" title="GAN training" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="caption">
        The frequency distribution (or PDF) of the guessed real number samples over epochs of training.
    </div>
</div>
