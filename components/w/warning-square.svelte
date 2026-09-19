<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boqllab4b.css';
import '../../css/a/am0b34b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="boqllab4b"/><path class="am0b34b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-square" {...props}></Icon>
