<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rywgoibcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rywgoibcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trending-down-variant" {...props}></Icon>
