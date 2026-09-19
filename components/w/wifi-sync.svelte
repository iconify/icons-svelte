<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkxbe4bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkxbe4bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-sync" {...props}></Icon>
