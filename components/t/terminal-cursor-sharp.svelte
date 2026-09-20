<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpbd0nb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbd0nb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-cursor-sharp" {...props}></Icon>
