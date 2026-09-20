<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i2strbb_c.css';
import '../../css/f/fh575-bvo.css';
import '../../css/i/ii_b03b1m.css';
import '../../css/r/rm-lboqdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="i2strbb_c"/><path class="fh575-bvo"/><path class="ii_b03b1m"/><path class="rm-lboqdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:tumer-duotone" {...props}></Icon>
