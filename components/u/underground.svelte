<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p74fnccdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p74fnccdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:underground" {...props}></Icon>
