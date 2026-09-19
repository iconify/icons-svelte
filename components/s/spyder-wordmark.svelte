<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8mtlxpmv.css';
import '../../css/a/a-zj5lbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m8mtlxpmv"/><path class="a-zj5lbdq b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:spyder-wordmark" {...props}></Icon>
