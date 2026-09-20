<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gilwy0bbh.css';
import '../../css/m/m0qgp2bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gilwy0bbh"/><path class="m0qgp2bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:social-rewards-rating-star-2" {...props}></Icon>
