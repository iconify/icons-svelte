<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb7bx9bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1050,"height":1000};
const content = `<path class="sb7bx9bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:star" {...props}></Icon>
