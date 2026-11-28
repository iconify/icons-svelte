<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnb4t44ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wnb4t44ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spray-to-cup-from-dispensing-machine-with-drink-cup-with-straw" {...props}></Icon>
