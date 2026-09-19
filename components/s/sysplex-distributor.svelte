<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjnzkby1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tjnzkby1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sysplex-distributor" {...props}></Icon>
