<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hghykk9oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1792};
const content = `<path class="hghykk9oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sort-numeric-desc" {...props}></Icon>
