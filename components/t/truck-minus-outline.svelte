<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1u83iczg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1u83iczg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-minus-outline" {...props}></Icon>
