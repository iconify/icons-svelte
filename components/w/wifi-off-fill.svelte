<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjmr10bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjmr10bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wifi-off-fill" {...props}></Icon>
