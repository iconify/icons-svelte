<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyunrr08p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xyunrr08p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:van" {...props}></Icon>
