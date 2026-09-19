<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpuj-nbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tpuj-nbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-stack-3d-down-right" {...props}></Icon>
