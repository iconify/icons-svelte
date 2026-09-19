<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz4bcds_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bz4bcds_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:twirl-center" {...props}></Icon>
