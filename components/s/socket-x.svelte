<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm_lp0ajf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_lp0ajf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:socket-x" {...props}></Icon>
