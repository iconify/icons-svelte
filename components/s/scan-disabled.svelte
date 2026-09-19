<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btq7sccff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="btq7sccff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scan-disabled" {...props}></Icon>
