<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t602nu8bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="t602nu8bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:stumbleupon" {...props}></Icon>
