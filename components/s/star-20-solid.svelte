<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0gng4b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j0gng4b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:star-20-solid" {...props}></Icon>
