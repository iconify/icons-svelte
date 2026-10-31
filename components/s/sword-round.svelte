<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n92ifub3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n92ifub3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sword-round" {...props}></Icon>
