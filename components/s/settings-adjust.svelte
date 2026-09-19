<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx4_2tenc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bx4_2tenc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:settings-adjust" {...props}></Icon>
