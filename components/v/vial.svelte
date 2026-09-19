<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcnuz9l5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wcnuz9l5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:vial" {...props}></Icon>
