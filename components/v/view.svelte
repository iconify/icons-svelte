<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqj70vbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cqj70vbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:view" {...props}></Icon>
