<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe62bdcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oe62bdcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:russian-orthodox-cross" {...props}></Icon>
