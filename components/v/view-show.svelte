<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeq8--beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xeq8--beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:view-show" {...props}></Icon>
