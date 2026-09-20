<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad3lmgbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ad3lmgbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:travel-train" {...props}></Icon>
