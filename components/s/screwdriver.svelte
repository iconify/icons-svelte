<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw4fqzb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jw4fqzb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:screwdriver" {...props}></Icon>
