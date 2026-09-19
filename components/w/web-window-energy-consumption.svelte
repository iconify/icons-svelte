<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x1-7980yu.css';
import '../../css/j/j0b34b2wg.css';
import '../../css/l/lwfwi1v1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x1-7980yu"/><path class="j0b34b2wg"/><path class="lwfwi1v1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:web-window-energy-consumption" {...props}></Icon>
