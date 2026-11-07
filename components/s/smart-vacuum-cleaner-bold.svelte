<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql3j78bhl.css';
import '../../css/u/ueez_60su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3j78bhl"/><path clip-rule="evenodd" class="ueez_60su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-vacuum-cleaner-bold" {...props}></Icon>
