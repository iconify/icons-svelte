<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8px5wr7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8px5wr7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shuffle-line" {...props}></Icon>
