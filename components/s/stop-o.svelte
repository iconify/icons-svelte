<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvnkgjbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xvnkgjbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:stop-o" {...props}></Icon>
