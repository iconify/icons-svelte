<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgb5kccst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kgb5kccst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:user" {...props}></Icon>
