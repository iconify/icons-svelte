<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov9r0xb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov9r0xb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zones-areas-first-floor" {...props}></Icon>
