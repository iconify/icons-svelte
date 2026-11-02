<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u67sr_bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u67sr_bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-align-start-fill" {...props}></Icon>
