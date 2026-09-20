<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l57hr9diu.css';
import '../../css/v/v-b9irtdp.css';
import '../../css/m/mhnfz8baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGUUWKNc3I" viewBox="0 0 291 291"><circle class="l57hr9diu"/><path class="v-b9irtdp"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 145.5 145.5; 45 145.5 145.5"/></path></symbol></defs><path class="mhnfz8baj"/><use width="291" height="291" href="#SVGUUWKNc3I" transform="translate(110.38 72.63)"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:time-afternoon" {...props}></Icon>
