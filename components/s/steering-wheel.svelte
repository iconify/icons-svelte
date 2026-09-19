<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7n4rvtdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y7n4rvtdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steering-wheel" {...props}></Icon>
