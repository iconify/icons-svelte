<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcje_ok-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcje_ok-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:trade-mark-circle" {...props}></Icon>
