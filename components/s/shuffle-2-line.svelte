<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iadbdwbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iadbdwbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shuffle-2-line" {...props}></Icon>
