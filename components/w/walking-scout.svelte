<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgu-vcc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sgu-vcc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:walking-scout" {...props}></Icon>
