<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b14u329ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b14u329ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ssrn" {...props}></Icon>
