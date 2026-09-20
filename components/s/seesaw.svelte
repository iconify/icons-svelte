<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wejwxcbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wejwxcbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:seesaw" {...props}></Icon>
