<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skgps-b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skgps-b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:surprised-solid" {...props}></Icon>
