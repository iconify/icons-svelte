<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qix83dbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qix83dbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:x-circle-multiple-thin" {...props}></Icon>
