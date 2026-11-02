<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvkdr3wzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvkdr3wzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:strikethrough-fill" {...props}></Icon>
