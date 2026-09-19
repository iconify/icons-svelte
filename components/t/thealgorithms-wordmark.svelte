<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcnuh7clv.css';
import '../../css/y/y3s_gsbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wcnuh7clv"/><path class="y3s_gsbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:thealgorithms-wordmark" {...props}></Icon>
