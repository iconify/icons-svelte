<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkv75fisb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fkv75fisb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tornado" {...props}></Icon>
