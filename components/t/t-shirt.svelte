<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vtmphkbxs.css';
import '../../css/y/ypen9ccxg.css';
import '../../css/q/q7ftzha2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtmphkbxs"/><path class="ypen9ccxg"/><path class="q7ftzha2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:t-shirt" {...props}></Icon>
