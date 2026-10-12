<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrai4biei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zrai4biei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:slider-fill-20" {...props}></Icon>
