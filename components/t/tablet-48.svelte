<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzvt794yl.css';
import '../../css/u/ubmyk0c4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yzvt794yl"/><path class="ubmyk0c4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tablet-48" {...props}></Icon>
