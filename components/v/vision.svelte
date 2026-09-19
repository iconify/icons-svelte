<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g0ppmrbfd.css';
import '../../css/u/u234q1bua.css';
import '../../css/m/miaafxb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="g0ppmrbfd"/><path class="u234q1bua"/><path class="miaafxb_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vision" {...props}></Icon>
