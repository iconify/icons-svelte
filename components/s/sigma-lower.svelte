<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgfcr4b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgfcr4b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sigma-lower" {...props}></Icon>
