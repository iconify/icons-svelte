<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvolhxbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uvolhxbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tanning2" {...props}></Icon>
