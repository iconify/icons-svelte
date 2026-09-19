<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfjyxob3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xfjyxob3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:surrogate-key-database" {...props}></Icon>
