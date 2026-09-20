<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mogx3vbjy.css';
import '../../css/d/dvv7-cbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mogx3vbjy"/><path class="dvv7-cbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:traffic-cone-duotone" {...props}></Icon>
