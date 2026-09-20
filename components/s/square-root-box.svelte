<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt-nwc72o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt-nwc72o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-root-box" {...props}></Icon>
