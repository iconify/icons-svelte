<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpkanabje.css';
import '../../css/l/lc21qzuqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpkanabje"/><path class="lc21qzuqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-bold" {...props}></Icon>
