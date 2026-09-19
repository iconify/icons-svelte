<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po7c3mbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="po7c3mbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ship-wreck" {...props}></Icon>
