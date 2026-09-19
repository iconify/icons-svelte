<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugxa7f5cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="ugxa7f5cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:traffic" {...props}></Icon>
