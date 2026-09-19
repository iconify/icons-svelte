<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5ix4pw3w.css';
import '../../css/y/yx_v63b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5ix4pw3w"/><path class="yx_v63b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:tag" {...props}></Icon>
