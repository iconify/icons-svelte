<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj1idbb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pj1idbb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:wine-bottle" {...props}></Icon>
