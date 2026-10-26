<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h02ds3bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":358.28,"height":358.28,"left":0.11,"top":1.86};
const content = `<path clip-rule="evenodd" class="h02ds3bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spiffe" {...props}></Icon>
