<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl7z8j7sc.css';
import '../../css/f/fg6p2fbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="zl7z8j7sc"/><path class="fg6p2fbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:search" {...props}></Icon>
