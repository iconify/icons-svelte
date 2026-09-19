<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am01m168f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="am01m168f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:volcano" {...props}></Icon>
