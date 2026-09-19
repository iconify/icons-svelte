<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3-kin2ph.css';
import '../../css/q/q6tuz1lwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y3-kin2ph"/><path class="q6tuz1lwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-mag-o" {...props}></Icon>
