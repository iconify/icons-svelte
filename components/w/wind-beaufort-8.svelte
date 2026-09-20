<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlk5ymyap.css';
import '../../css/i/i27tkhlqe.css';
import '../../css/h/h64ocabvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGly5QtRGo" viewBox="0 0 342 234"><path class="vlk5ymyap"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 3552"/></path><path class="i27tkhlqe"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 1980"/></path></symbol></defs><use width="342" height="234" href="#SVGly5QtRGo" transform="translate(85 139)"/><path class="h64ocabvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:wind-beaufort-8" {...props}></Icon>
