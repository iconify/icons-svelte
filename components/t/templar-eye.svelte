<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0zb_5t_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0zb_5t_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:templar-eye" {...props}></Icon>
