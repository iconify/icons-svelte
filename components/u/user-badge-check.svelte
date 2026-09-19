<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pva9lf95q.css';
import '../../css/j/jwvtersej.css';
import '../../css/q/ql59r0c_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pva9lf95q"/><path class="jwvtersej"/><path class="ql59r0c_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:user-badge-check" {...props}></Icon>
