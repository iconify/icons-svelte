<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5a7zsawl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p5a7zsawl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:volume-up-filled" {...props}></Icon>
