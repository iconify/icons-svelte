<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo8_tu72j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo8_tu72j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wifi-refresh" {...props}></Icon>
