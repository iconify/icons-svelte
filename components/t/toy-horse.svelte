<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipb_7ybiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ipb_7ybiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:toy-horse" {...props}></Icon>
