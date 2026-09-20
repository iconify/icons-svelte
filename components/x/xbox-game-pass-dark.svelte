<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmkivvb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmkivvb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xbox-game-pass-dark" {...props}></Icon>
