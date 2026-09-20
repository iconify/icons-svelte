<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llx_gbc1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":335.72,"height":217.4};
const content = `<path class="llx_gbc1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:walgreens" {...props}></Icon>
