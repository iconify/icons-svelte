<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amns9fbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="amns9fbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wmv" {...props}></Icon>
