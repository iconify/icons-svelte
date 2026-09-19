<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yccvg5xel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1120,"height":2208};
const content = `<path class="yccvg5xel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:wine-o" {...props}></Icon>
