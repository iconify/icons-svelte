<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3w4lbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp3w4lbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:umbrella-filled" {...props}></Icon>
