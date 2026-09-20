<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/danrfbc9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="danrfbc9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tyre-line" {...props}></Icon>
