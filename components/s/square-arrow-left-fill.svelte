<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/outf-5w6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="outf-5w6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-left-fill" {...props}></Icon>
