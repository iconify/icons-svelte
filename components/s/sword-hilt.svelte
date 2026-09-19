<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iamj04z-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iamj04z-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-hilt" {...props}></Icon>
