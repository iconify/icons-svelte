<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/u4vh7gcjc.css';
import '../../css/d/dnl8j0wnh.css';
import '../../css/u/u6t3q4b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4vh7gcjc"/><path class="dnl8j0wnh"/><path class="u6t3q4b3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-cirlce-add" {...props}></Icon>
