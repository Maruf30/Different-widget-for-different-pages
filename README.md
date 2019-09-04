# Different-widget-for-different-pages




<?php if ( is_page('testimonials') ) : ?>
       <?php if ( !dynamic_sidebar('testimonial_sidebar') ) : ?><?php endif ; ?>
 
        <?php elseif (is_page('contact')) : ?>
      <?php if ( !dynamic_sidebar('contact_sidebar') ) : ?> <?php endif ; ?>
         
         
         <?php elseif (is_page(147)) : ?>
          <?php if ( !dynamic_sidebar('matrix_nlp') ) : ?> <?php endif ; ?>
         
         
         <?php elseif (is_page(71)) : ?>
          <?php if ( !dynamic_sidebar('corporate_nlp_programs') ) : ?> <?php endif ; ?>
         
         
         <?php elseif (is_page(154)) : ?>
          <?php if ( !dynamic_sidebar('nlp_practitioner_certification') ) : ?> <?php endif ; ?>
         
         
          <?php elseif (is_page(165)) : ?>
          <?php if ( !dynamic_sidebar('nlp_master') ) : ?> <?php endif ; ?>
         
         
        <?php elseif (is_page(200)) : ?>
          <?php if ( !dynamic_sidebar('nlp_to_excellence') ) : ?> <?php endif ; ?>
         
        <?php else : ?>
           <?php if ( !dynamic_sidebar('unique_sidebar_id') ) : ?><?php endif ; ?>
        <?php endif; ?>
