<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6npdccvb.css';
import '../../css/f/f7yrgob5n.css';
import '../../css/r/rkd56vgis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6npdccvb"/><path class="f7yrgob5n"/><path clip-rule="evenodd" class="rkd56vgis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stopwatch" {...props}></Icon>
