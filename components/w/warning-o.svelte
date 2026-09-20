<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-o3w7b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l-o3w7b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:warning-o" {...props}></Icon>
