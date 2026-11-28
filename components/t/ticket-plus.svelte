<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep8a0-bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep8a0-bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ticket-plus" {...props}></Icon>
