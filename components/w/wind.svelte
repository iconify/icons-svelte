<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm1st8boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bm1st8boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wind" {...props}></Icon>
