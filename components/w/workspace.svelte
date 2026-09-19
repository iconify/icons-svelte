<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px_xisjvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="px_xisjvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:workspace" {...props}></Icon>
