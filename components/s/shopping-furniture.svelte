<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y38j07b8s.css';
import '../../css/g/gco7s4pcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y38j07b8s"/><path class="gco7s4pcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-furniture" {...props}></Icon>
