<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhj2skbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhj2skbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:semi-closed-eye" {...props}></Icon>
