<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj292lbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zj292lbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:wpr" {...props}></Icon>
