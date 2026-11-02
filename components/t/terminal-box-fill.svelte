<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er9zehb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er9zehb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-box-fill" {...props}></Icon>
