<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz3p94bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wz3p94bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:terraform" {...props}></Icon>
