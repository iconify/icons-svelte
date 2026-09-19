<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh-kgyh0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rh-kgyh0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:wind-sock" {...props}></Icon>
