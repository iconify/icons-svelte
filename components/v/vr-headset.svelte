<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr_fswb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nr_fswb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vr-headset" {...props}></Icon>
