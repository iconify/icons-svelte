<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl038tb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bl038tb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:super-mushroom" {...props}></Icon>
