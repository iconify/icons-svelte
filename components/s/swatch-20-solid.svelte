<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-zs35aly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h-zs35aly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:swatch-20-solid" {...props}></Icon>
