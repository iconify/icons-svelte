<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm1-5o2go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1-5o2go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sparkles-2-line" {...props}></Icon>
