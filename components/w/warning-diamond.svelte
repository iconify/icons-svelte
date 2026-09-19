<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvl9v5b9e.css';
import '../../css/o/oqfk99ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yvl9v5b9e"/><path class="oqfk99ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-diamond" {...props}></Icon>
