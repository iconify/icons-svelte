<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riv2d9n9z.css';
import '../../css/j/j10j52bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="riv2d9n9z"/><path class="j10j52bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-off-outline" {...props}></Icon>
