<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbua0obei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbua0obei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wreath-fill" {...props}></Icon>
