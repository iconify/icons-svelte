<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgjfiebre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fgjfiebre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:ticket" {...props}></Icon>
