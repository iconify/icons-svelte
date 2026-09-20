<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1_hfx2hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1_hfx2hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:space-station" {...props}></Icon>
