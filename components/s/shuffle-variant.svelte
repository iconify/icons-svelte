<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chm_rl1fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chm_rl1fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shuffle-variant" {...props}></Icon>
