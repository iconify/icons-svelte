<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5bwus7zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f5bwus7zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:russian-cross" {...props}></Icon>
