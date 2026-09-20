<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irhhhosvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irhhhosvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-tennis" {...props}></Icon>
