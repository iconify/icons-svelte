<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgzc5-b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tgzc5-b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-off-stroke-12" {...props}></Icon>
