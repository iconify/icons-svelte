<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtdwdp3he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtdwdp3he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:suitcase-line" {...props}></Icon>
