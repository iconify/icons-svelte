<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq9ivkx-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq9ivkx-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zoom" {...props}></Icon>
