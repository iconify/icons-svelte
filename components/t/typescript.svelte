<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv5b60b3j.css';
import '../../css/z/z8r7eipgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lv5b60b3j"/><path class="z8r7eipgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:typescript" {...props}></Icon>
