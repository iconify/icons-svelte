<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7-h4bc3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z7-h4bc3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:veri" {...props}></Icon>
