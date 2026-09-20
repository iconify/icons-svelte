<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lcgysub4q"/><path class="x88hcibmd"/><path class="p4pz808-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ssv" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lcgysub4q) {
  fill: var(--svg-color--009cf2, #009cf2);
  d: path("M9.247 6.62a.38.38 0 0 1 0-.483l2.458-2.998a.38.38 0 0 1 .587 0l2.463 2.998a.38.38 0 0 1 0 .483l-2.463 2.913a.378.378 0 0 1-.587 0L9.242 6.62z");
}

:global(.p4pz808-l) {
  fill: var(--svg-color--009cf2, #009cf2);
  d: path("M5.695 11.133a.38.38 0 0 1-.004-.483L8.13 7.652a.38.38 0 0 1 .587 0l2.439 2.998a.38.38 0 0 1 0 .483l-2.444 2.913a.38.38 0 0 1-.578 0zm7.151 0a.38.38 0 0 1 0-.483l2.435-2.998a.38.38 0 0 1 .587 0l2.439 2.998a.38.38 0 0 1 0 .483l-2.444 2.913a.378.378 0 0 1-.577 0z");
}

:global(.x88hcibmd) {
  fill: var(--svg-color--00649b, #00649b);
  d: path("M9.247 17.948a.38.38 0 0 1 0-.483l2.458-2.998a.38.38 0 0 1 .456-.103a.4.4 0 0 1 .13.103l2.464 2.998a.38.38 0 0 1 0 .483l-2.463 2.912a.378.378 0 0 1-.587 0l-2.463-2.912z");
}

</style>
