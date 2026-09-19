<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2zmswy-h.css';
import '../../css/q/q6tuz1lwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m2zmswy-h"/><path class="q6tuz1lwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-mag" {...props}></Icon>
