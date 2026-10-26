<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivbs_oy6v.css';
import '../../css/g/ghclb9bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ivbs_oy6v"/><path class="ghclb9bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sanity" {...props}></Icon>
