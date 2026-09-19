<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swg-av1ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="swg-av1ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shadow-follower" {...props}></Icon>
