<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3dv7sbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="r3dv7sbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:x" {...props}></Icon>
