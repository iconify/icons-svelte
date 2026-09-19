<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y30mei9nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y30mei9nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sap" {...props}></Icon>
