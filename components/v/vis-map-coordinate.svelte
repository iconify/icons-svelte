<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th-l21bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="th-l21bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-map-coordinate" {...props}></Icon>
