<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn8nh4bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xn8nh4bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-13-death" {...props}></Icon>
