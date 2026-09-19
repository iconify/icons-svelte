<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by7yhws7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="by7yhws7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:zed" {...props}></Icon>
