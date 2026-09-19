<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5xpcbcrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="t5xpcbcrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squaref" {...props}></Icon>
