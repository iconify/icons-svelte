<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh2bigb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rh2bigb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:splunk-wordmark" {...props}></Icon>
