<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsi4b2blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsi4b2blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:upload" {...props}></Icon>
