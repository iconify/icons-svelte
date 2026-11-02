<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug4lk-61w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug4lk-61w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-3-line" {...props}></Icon>
