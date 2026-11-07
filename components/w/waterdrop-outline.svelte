<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uskchin6p.css';
import '../../css/r/rij0rxuxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uskchin6p"/><path clip-rule="evenodd" class="rij0rxuxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:waterdrop-outline" {...props}></Icon>
