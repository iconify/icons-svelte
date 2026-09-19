<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhyf54b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zhyf54b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:webpack" {...props}></Icon>
