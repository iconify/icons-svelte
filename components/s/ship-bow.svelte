<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi0x6kbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qi0x6kbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ship-bow" {...props}></Icon>
