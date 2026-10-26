<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnyabcb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnyabcb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:saudi-riyal" {...props}></Icon>
