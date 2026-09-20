<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5tv_n05j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5tv_n05j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-line" {...props}></Icon>
