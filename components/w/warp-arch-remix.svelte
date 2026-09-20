<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tumn9_bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tumn9_bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:warp-arch-remix" {...props}></Icon>
