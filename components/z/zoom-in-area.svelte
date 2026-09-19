<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q11_wkbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q11_wkbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zoom-in-area" {...props}></Icon>
