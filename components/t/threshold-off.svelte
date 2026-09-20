<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brwigubtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brwigubtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:threshold-off" {...props}></Icon>
