<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug54_cbfy.css';
import '../../css/w/wfiymubcg.css';
import '../../css/q/q5gb5d1vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ug54_cbfy"/><path class="wfiymubcg"/><path class="q5gb5d1vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rugby-20-bold" {...props}></Icon>
