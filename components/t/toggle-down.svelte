<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glk2itbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(0 1536) scale(1 -1)"><path class="glk2itbjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:toggle-down" {...props}></Icon>
