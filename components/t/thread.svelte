<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q974a834z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q974a834z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thread" {...props}></Icon>
