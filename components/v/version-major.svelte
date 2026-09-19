<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg1yxfb0n.css';
import '../../css/s/stheyzbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eg1yxfb0n"/><path class="stheyzbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:version-major" {...props}></Icon>
