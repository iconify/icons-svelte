<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts_8b5bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ts_8b5bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scroll-unfurled" {...props}></Icon>
