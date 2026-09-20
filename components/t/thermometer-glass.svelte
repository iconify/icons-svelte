<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuk73z6nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG7ARWWbSl" viewBox="0 0 118 278"><path class="nuk73z6nh"/></symbol></defs><use width="118" height="278" href="#SVG7ARWWbSl" transform="translate(197 117)"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:thermometer-glass" {...props}></Icon>
