<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv9q3ib4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":358.28,"height":358.28,"left":0.11,"top":1.86};
const content = `<path clip-rule="evenodd" class="rv9q3ib4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spiffe-dark" {...props}></Icon>
