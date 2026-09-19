<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfb62obzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jfb62obzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:webstorm-wordmark" {...props}></Icon>
