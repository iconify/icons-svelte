<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am90fyq1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am90fyq1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ticket-line" {...props}></Icon>
