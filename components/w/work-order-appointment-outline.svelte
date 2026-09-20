<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy072qbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vy072qbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-appointment-outline" {...props}></Icon>
