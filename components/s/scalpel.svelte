<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9_8gbccn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n9_8gbccn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scalpel" {...props}></Icon>
