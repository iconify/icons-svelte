<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9ts_2cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9ts_2cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:volume-x" {...props}></Icon>
