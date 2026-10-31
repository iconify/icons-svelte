<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3qu93bwv.css';
import '../../css/w/wbb6ggb3t.css';
import '../../css/b/bhjcuuxbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="a3qu93bwv"/><path class="wbb6ggb3t"/><path class="bhjcuuxbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:trinidad-tobago" {...props}></Icon>
