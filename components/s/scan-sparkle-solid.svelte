<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn652xb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn652xb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-sparkle-solid" {...props}></Icon>
