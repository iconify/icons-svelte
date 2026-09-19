<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezhm6ccnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="ezhm6ccnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:speech" {...props}></Icon>
