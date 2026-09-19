<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztm991_5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztm991_5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wine-bottle" {...props}></Icon>
