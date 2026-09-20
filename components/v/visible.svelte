<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtb1766zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtb1766zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:visible" {...props}></Icon>
