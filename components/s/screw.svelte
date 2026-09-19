<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tutls0qog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tutls0qog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:screw" {...props}></Icon>
