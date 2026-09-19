<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgenvkb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgenvkb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:silenced" {...props}></Icon>
