<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgorfdcox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mgorfdcox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:step-out-16" {...props}></Icon>
