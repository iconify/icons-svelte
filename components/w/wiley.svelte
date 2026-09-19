<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq59fpl6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vq59fpl6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:wiley" {...props}></Icon>
