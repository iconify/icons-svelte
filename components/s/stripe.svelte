<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3_p6ob_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3_p6ob_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stripe" {...props}></Icon>
