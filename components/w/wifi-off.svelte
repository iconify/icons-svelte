<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uarocz_at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uarocz_at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wifi-off" {...props}></Icon>
