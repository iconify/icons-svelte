<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xru9etm2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xru9etm2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rstan" {...props}></Icon>
