<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf5mnlbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf5mnlbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:volume-up-solid" {...props}></Icon>
