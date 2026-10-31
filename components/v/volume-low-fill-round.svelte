<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgp5_cbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgp5_cbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-low-fill-round" {...props}></Icon>
