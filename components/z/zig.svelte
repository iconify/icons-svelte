<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhe8t8ahy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":176};
const content = `<path class="xhe8t8ahy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zig" {...props}></Icon>
