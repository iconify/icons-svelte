<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-ep33b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r-ep33b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:timeline-progress" {...props}></Icon>
