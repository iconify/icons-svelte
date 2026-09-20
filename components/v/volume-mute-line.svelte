<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5qp9qio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai5qp9qio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-mute-line" {...props}></Icon>
