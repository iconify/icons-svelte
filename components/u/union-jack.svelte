<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek-sb1riu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ek-sb1riu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:union-jack" {...props}></Icon>
