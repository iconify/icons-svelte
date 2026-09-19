<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz6wm02jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bz6wm02jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:transform" {...props}></Icon>
