<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0zrxx8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ln0zrxx8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:village" {...props}></Icon>
