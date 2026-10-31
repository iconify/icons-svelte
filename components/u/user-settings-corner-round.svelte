<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kavlb0b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kavlb0b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-settings-corner-round" {...props}></Icon>
