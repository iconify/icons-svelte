<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx3e_tbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1472};
const content = `<path class="mx3e_tbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stumbleupon" {...props}></Icon>
