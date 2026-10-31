<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swxnh4qgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swxnh4qgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-close-corner-fill-round" {...props}></Icon>
