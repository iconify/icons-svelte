<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxghsl_ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wxghsl_ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wlan" {...props}></Icon>
