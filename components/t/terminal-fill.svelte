<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awp290b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awp290b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-fill" {...props}></Icon>
