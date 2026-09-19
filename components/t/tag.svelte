<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iul73ibuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":840};
const content = `<path class="iul73ibuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:tag" {...props}></Icon>
