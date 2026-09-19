<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygum6sb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygum6sb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:three-keys" {...props}></Icon>
