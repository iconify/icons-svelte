<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kb4cgpl.css';
import '../../css/r/r3njy2b3d.css';
import '../../css/j/jskd55kvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="r3njy2b3d"/><path class="jskd55kvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:volume-off-bold" {...props}></Icon>
