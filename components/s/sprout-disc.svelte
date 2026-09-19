<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpjtu2prx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpjtu2prx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sprout-disc" {...props}></Icon>
