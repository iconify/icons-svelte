<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc7aas1aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rc7aas1aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:shield-volcano-smoke-2" {...props}></Icon>
