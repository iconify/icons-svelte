<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrgo91_7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrgo91_7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shrink-bulk-round" {...props}></Icon>
